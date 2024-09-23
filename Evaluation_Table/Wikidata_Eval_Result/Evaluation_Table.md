# Evaluation Metrics Table

The following table presents the evaluation metrics for three different language models: **Alpaca-LoRA-13B**, **Model-2**, and **Model-3**. These metrics provide insights into the performance of each model across various categories, such as Movie, Music, Sport, Book, Military, Computer, Space, Politics, Nature, and Culture. The evaluation metrics include average precision, average recall, average F1 score, average ontological confidence, and various types of hallucinations (subjective and objective).

| LLM Name           | Evaluation Metrics | avg_precision | avg_recall | avg_f1 | avg_onto_conf | avg_sub_halluc | avg_sub_halluc | avg_rel_halluc | avg_obj_halluc |
|--------------------|--------------------|---------------|------------|--------|----------------|----------------|----------------|----------------|----------------|
| Alpaca-LoRA-13B    | Movie              |               |            |        |                |                |                |                |                |
|                    | Music              |               |            |        |                |                |                |                |                |
|                    | Sport              |               |            |        |                |                |                |                |                |
|                    | Book               |               |            |        |                |                |                |                |                |
|                    | Military           |               |            |        |                |                |                |                |                |
|                    | Computer           |               |            |        |                |                |                |                |                |
|                    | Space              |               |            |        |                |                |                |                |                |
|                    | Politics           |               |            |        |                |                |                |                |                |
|                    | Nature             |               |            |        |                |                |                |                |                |
|                    | Culture            |               |            |        |                |                |                |                |                |
|--------------------|--------------------|---------------|------------|--------|----------------|----------------|----------------|----------------|----------------|
| Model-2            | Movie              |               |            |        |                |                |                |                |                |
|                    | Music              |               |            |        |                |                |                |                |                |
|                    | Sport              |               |            |        |                |                |                |                |                |
|                    | Book               |               |            |        |                |                |                |                |                |
|                    | Military           |               |            |        |                |                |                |                |                |
|                    | Computer           |               |            |        |                |                |                |                |                |
|                    | Space              |               |            |        |                |                |                |                |                |
|                    | Politics           |               |            |        |                |                |                |                |                |
|                    | Nature             |               |            |        |                |                |                |                |                |
|                    | Culture            |               |            |        |                |                |                |                |                |
|--------------------|--------------------|---------------|------------|--------|----------------|----------------|----------------|----------------|----------------|
| Model-3            | Movie              |               |            |        |                |                |                |                |                |
|                    | Music              |               |            |        |                |                |                |                |                |
|                    | Sport              |               |            |        |                |                |                |                |                |
|                    | Book               |               |            |        |                |                |                |                |                |
|                    | Military           |               |            |        |                |                |                |                |                |
|                    | Computer           |               |            |        |                |                |                |                |                |
|                    | Space              |               |            |        |                |                |                |                |                |
|                    | Politics           |               |            |        |                |                |                |                |                |
|                    | Nature             |               |            |        |                |                |                |                |                |
|                    | Culture            |               |            |        |                |                |                |                |                |
|--------------------|--------------------|---------------|------------|--------|----------------|----------------|----------------|----------------|----------------|

## Models Description

### Alpaca-LoRA-13B
Alpaca-LoRA-13B is a 13 billion parameter language model fine-tuned with the LoRA (Low-Rank Adaptation) technique. This model is designed to perform well on a variety of natural language processing tasks by leveraging a large-scale dataset and fine-tuning to adapt to specific domains and use cases.

### Model-2
Model-2 is another advanced language model that has been trained to understand and generate human-like text. It has been evaluated across multiple categories to benchmark its performance in terms of precision, recall, F1 score, ontological confidence, and hallucination rates.

### Model-3
Model-3 is a state-of-the-art language model that focuses on minimizing subjective and objective hallucinations while maintaining high performance across diverse domains. This model aims to improve reliability and accuracy in text generation tasks.

## Evaluation Metrics
The evaluation metrics used for these models are as follows:
- **avg_precision**: The average precision score across different categories.
- **avg_recall**: The average recall score across different categories.
- **avg_f1**: The average F1 score, which is the harmonic mean of precision and recall.
- **avg_onto_conf**: The average ontological confidence score, indicating the model's confidence in its predictions.
- **avg_sub_halluc**: The average subjective hallucination rate, measuring the frequency of subjective errors.
- **avg_rel_halluc**: The average relational hallucination rate, measuring the frequency of relational errors.
- **avg_obj_halluc**: The average objective hallucination rate, measuring the frequency of objective errors.
