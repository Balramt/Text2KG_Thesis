# Leveraging Large Language Models for KG Construction and Reasoning

This repository is part of the research project on **Leveraging Large Language Models for KG Construction and Reasoning** using Large Language Models (LLMs). The benchmark aims to evaluate LLMs for extracting knowledge graph triples from natural language while adhering to a given ontology. The focus is on key evaluation metrics such as precision, recall, F1-score, ontology conformance, and hallucination rates.

This repository contains evaluation scripts, datasets, and results for models evaluated on DBpedia and Wikidata datasets.

---

## Datasets

1. **DBpedia-WebNLG**
   -This datasets is created using WebNLG corpus alignments, covering 19 ontologies.
   - 19 ontologies, 4,860 sentences.
   - Includes ground truth triples aligned with ontology structure and constraints.

3. **Wikidata-TekGen**
   - This datasets is created using Wikidata and TekGen corpus.  
   - It contains 10 ontologies, 13,474 sentences.
   - Structured based on Wikidata’s ontology with domain/range constraints for extracted triples.

### Example Test Input

Test Sentence:  
```json
{
  "id": "ont_movie_test_1",
  "sent": "The movie Inception was directed by Christopher Nolan."
}
```

Ontology: **Movie Ontology**

### Expected Output

```json
{
  "id": "ont_movie_test_1",
  "triples": [
    {
      "sub": "Inception",
      "rel": "directed by",
      "obj": "Christopher Nolan"
    }
  ]
}
```

## Structure of the Repository

### Folders

- `src/`: Contains the main source code for data processing, evaluation, and LLM interaction.
- `data/`: Contains the benchmark datasets, including ontologies and test sentences for DBpedia and Wikidata.
  - `dbpedia_webnlg/`: DBpedia dataset files.
    - `ground_truth/`: Ground truth triples for evaluation.
    - `input_prompts/`: Input sentences fed to the LLM models.
  - `wikidata_tekgen/`: Wikidata-TekGen dataset files.
    - `ontologies/`: The 10 ontologies used in this dataset.
    - `input_prompts/`: Input sentences fed to the LLM models.
- `results/`: Contains evaluation results.
  - `avg_eval_statistics/`: Average results across multiple evaluation cases.
  - `llm_responses/`: Raw responses from models like Alpaca-LoRA-13B and Vicuna-13B.
  - `eval_metrics/`: Aggregated evaluation metrics.

---

## How to Use

1. **Setup**:  
   - Clone the repository.
   - Install the required dependencies using `pip install -r requirements.txt`.

2. **Evaluate a Model**:  
   - To evaluate a specific ontology, use the `Individual_Onto_Evaluation.ipynb` notebook.
   - To evaluate multiple test cases and compute average metrics, run the `combine_avg.ipynb` notebook.

3. **Example Command**:
   ```bash
   python combine_avg.ipynb
   ```
