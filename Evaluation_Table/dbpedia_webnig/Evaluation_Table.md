# Evaluation Metrics Table

The following table presents the evaluation metrics for three different language models: **Alpaca-LoRA-13B**, **LLAMA3**, and **Vicuna-13B**. These metrics provide insights into the performance of each model across various categories, such as University, Musical Work, Airport, Building, Athlete, Politician, Company, Celestial Body, Astronaut, Comics Character, Means of Transportation, Monument, Food, Written Work, Sports Team, City, Artist, Scientist, and Film. The evaluation metrics include average precision, average recall, average F1 score, average ontological confidence, and various types of hallucinations (subjective, relational, and objective).

| LLM Model Name  | Ontology                | avg_precision | avg_recall | avg_f1 | avg_onto_conf | avg_sub_halluc | avg_rel_halluc | avg_obj_halluc |
|-----------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| Alpaca-LoRA-13B | University              | 0.29          | 0.16       | 0.20   | 0.89          | 0.13           | 0.30           | 0.06           |
|                 | Musical Work            | 0.20          | 0.11       | 0.13   | 0.49          | 0.39           | 0.51           | 0.31           |
|                 | Airport                 | 0.33          | 0.11       | 0.17   | 0.63          | 0.02           | 0.37           | 0.12           |
|                 | Building                | 0.33          | 0.11       | 0.17   | 0.83          | 0.02           | 0.17           | 0.09           |
|                 | Athlete                 | 0.41          | 0.15       | 0.22   | 0.73          | 0.00           | 0.27           | 0.20           |
|                 | Politician              | 0.44          | 0.14       | 0.21   | 0.73          | 0.07           | 0.27           | 0.16           |
|                 | Company                 | 0.39          | 0.15       | 0.21   | 0.55          | 0.11           | 0.45           | 0.33           |
|                 | Celestial Body          | 0.29          | 0.14       | 0.18   | 0.91          | 0.03           | 0.09           | 0.26           |
|                 | Astronaut               | 0.44          | 0.12       | 0.18   | 0.66          | 0.00           | 0.34           | 0.54           |
|                 | Comics Character        | 0.36          | 0.12       | 0.19   | 0.59          | 0.53           | 0.41           | 0.04           |
|                 | Means of Transportation | 0.19          | 0.06       | 0.09   | 0.62          | 0.00           | 0.38           | 0.21           |
|                 | Monument                | 0.00          | 0.00       | 0.00   | 0.49          | 0.11           | 0.51           | 0.21           |
|                 | Food                    | 0.31          | 0.09       | 0.14   | 0.64          | 0.00           | 0.36           | 0.27           |
|                 | Written Work            | 0.37          | 0.15       | 0.20   | 0.76          | 0.01           | 0.24           | 0.23           |
|                 | Sports Team             | 0.43          | 0.15       | 0.22   | 0.71          | 0.00           | 0.29           | 0.11           |
|                 | City                    | 0.41          | 0.16       | 0.22   | 0.71          | 0.03           | 0.26           | 0.15           |
|-----------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| LLAMA3          | University              | 0.15          | 0.05       | 0.07   | 0.43          | 0.02           | 0.58           | 0.23           |
|                 | Musical Work            | 0.20          | 0.11       | 0.13   | 0.49          | 0.39           | 0.51           | 0.31           |
|                 | Airport                 | 0.33          | 0.11       | 0.17   | 0.63          | 0.02           | 0.37           | 0.12           |
|                 | Building                | 0.33          | 0.11       | 0.17   | 0.83          | 0.02           | 0.17           | 0.09           |
|                 | Athlete                 | 0.41          | 0.15       | 0.22   | 0.73          | 0.00           | 0.27           | 0.20           |
|                 | Politician              | 0.44          | 0.14       | 0.21   | 0.73          | 0.07           | 0.27           | 0.16           |
|                 | Company                 | 0.39          | 0.15       | 0.21   | 0.55          | 0.11           | 0.45           | 0.33           |
|                 | Celestial Body          | 0.29          | 0.14       | 0.18   | 0.91          | 0.03           | 0.09           | 0.26           |
|                 | Astronaut               | 0.44          | 0.12       | 0.18   | 0.66          | 0.00           | 0.34           | 0.54           |
|                 | Comics Character        | 0.36          | 0.12       | 0.19   | 0.59          | 0.53           | 0.41           | 0.04           |
|                 | Means of Transportation | 0.19          | 0.06       | 0.09   | 0.62          | 0.00           | 0.38           | 0.21           |
|                 | Monument                | 0.00          | 0.00       | 0.00   | 0.49          | 0.11           | 0.51           | 0.21           |
|                 | Food                    | 0.31          | 0.09       | 0.14   | 0.64          | 0.00           | 0.36           | 0.27           |
|                 | Written Work            | 0.37          | 0.15       | 0.20   | 0.76          | 0.01           | 0.24           | 0.23           |
|                 | Sports Team             | 0.43          | 0.15       | 0.22   | 0.71          | 0.00           | 0.29           | 0.11           |
|                 | City                    | 0.41          | 0.16       | 0.22   | 0.71          | 0.03           | 0.26           | 0.15           |
|-----------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| Vicuna-13B      | University              | 0.24          | 0.08       | 0.12   | 0.70          | 0.00           | 0.30           | 0.06           |
|                 | Musical Work            | 0.20          | 0.11       | 0.13   | 0.49          | 0.39           | 0.51           | 0.31           |
|                 | Airport                 | 0.33          | 0.11       | 0.17   | 0.63          | 0.02           | 0.37           | 0.12           |
|                 | Building                | 0.33          | 0.11       | 0.17   | 0.83          | 0.02           | 0.17           | 0.09           |
|                 | Athlete                 | 0.41          | 0.15       | 0.22   | 0.73          | 0.00           | 0.27           | 0.20           |
|                 | Politician              | 0.44          | 0.14       | 0.21   | 0.73          | 0.07           | 0.27           | 0.16           |
|                 | Company                 | 0.39          | 0.15       | 0.21   | 0.55          | 0.11           | 0.45           | 0.33           |
|                 | Celestial Body          | 0.29          | 0.14       | 0.18   | 0.91          | 0.03           | 0.09           | 0.26           |
|                 | Astronaut               | 0.44          | 0.12       | 0.18   | 0.66          | 0.00           | 0.34           | 0.54           |
|                 | Comics Character        | 0.36          | 0.12       | 0.19   | 0.59          | 0.53           | 0.41           | 0.04           |
|                 | Means of Transportation | 0.19          | 0.06       | 0.09   | 0.62          | 0.00           | 0.38           | 0.21           |
|                 | Monument                | 0.00          | 0.00       | 0.00   | 0.49          | 0.11           | 0.51           | 0.21           |
|                 | Food                    | 0.31          | 0.09       | 0.14   | 0.64          | 0.00           | 0.36           | 0.27           |
|                 | Written Work            | 0.37          | 0.15       | 0.20   | 0.76          | 0.01           | 0.24           | 0.23           |
|                 | Sports Team             | 0.43          | 0.15       | 0.22   | 0.71          | 0.00           | 0.29           | 0.11           |
|                 | City                    | 0.41          | 0.16       | 0.22   | 0.71          | 0.03           | 0.26           | 0.15           |
|-----------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|

## Models Description

### Alpaca-LoRA-13B
Alpaca-LoRA-13B is a 13 billion parameter language model fine-tuned with the LoRA (Low-Rank Adaptation) technique. This model is designed to perform well on a variety of natural language processing tasks by leveraging a large-scale dataset and fine-tuning to adapt to specific domains and use cases.

### LLAMA3
LLAMA3 is an advanced language model that has been trained to understand and generate human-like text. It has been evaluated across multiple categories to benchmark its performance in terms of precision, recall, F1 score, ontological confidence, and hallucination rates.

### Vicuna-13B
Vicuna-13B is a robust language model evaluated on various domains. It aims to achieve a balance between high performance and low hallucination rates, ensuring reliable and accurate text generation across different contexts.

## Evaluation Metrics
The evaluation metrics used for these models are as follows:
- **avg_precision**: The average precision score across different categories.
- **avg_recall**: The average recall score across different categories.
- **avg_f1**: The average F1 score, which is the harmonic mean of precision and recall.
- **avg_onto_conf**: The average ontological confidence score, indicating the model's confidence in its predictions.
- **avg_sub_halluc**: The average subjective hallucination rate, measuring the frequency of subjective errors.
- **avg_rel_halluc**: The average relational hallucination rate, measuring the frequency of relational errors.
- **avg_obj_halluc**: The average objective hallucination rate, measuring the frequency of objective errors.
