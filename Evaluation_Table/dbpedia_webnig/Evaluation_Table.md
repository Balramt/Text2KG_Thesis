# Evaluation Metrics Table

The following table presents the evaluation metrics for three different language models: **Alpaca-LoRA-13B**, **LLAMA3**, and **Vicuna-13B**. These metrics provide insights into the performance of each model across various categories, such as University, Musical Work, Airport, Building, Athlete, Politician, Company, Celestial Body, Astronaut, Comics Character, Means of Transportation, Monument, Food, Written Work, Sports Team, City, Artist, Scientist, and Film. The evaluation metrics include average precision, average recall, average F1 score, average ontological confidence, and various types of hallucinations (subjective, relational, and objective).

### Combined Performance Metrics for LLM Models

| LLM Model Name      | Ontology                | avg_precision | avg_recall | avg_f1 | avg_onto_conf | avg_sub_halluc | avg_rel_halluc | avg_obj_halluc |
|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| **Alpaca-LoRA-13B** | University              | 0.29          | 0.16       | 0.20   | 0.89          | 0.13           | 0.11           | 0.26           |
|                     | Musical Work            | 0.18          | 0.15       | 0.15   | 0.85          | 0.32           | 0.15           | 0.33           |
|                     | Airport                 | 0.28          | 0.18       | 0.20   | 0.94          | 0.12           | 0.06           | 0.45           |
|                     | Building                | 0.35          | 0.27       | 0.29   | 0.93          | 0.17           | 0.07           | 0.32           |
|                     | Athlete                 | 0.38          | 0.30       | 0.32   | 0.94          | 0.11           | 0.06           | 0.27           |
|                     | Politician              | 0.39          | 0.27       | 0.30   | 0.92          | 0.15           | 0.08           | 0.38           |
|                     | Company                 | 0.35          | 0.21       | 0.25   | 0.95          | 0.17           | 0.05           | 0.44           |
|                     | Celestial Body          | 0.52          | 0.44       | 0.47   | 0.96          | 0.12           | 0.04           | 0.49           |
|                     | Astronaut               | 0.34          | 0.21       | 0.25   | 0.87          | 0.08           | 0.13           | 0.58           |
|                     | Comics Character        | 0.52          | 0.41       | 0.45   | 0.93          | 0.62           | 0.07           | 0.42           |
|                     | Means of Transportation | 0.13          | 0.09       | 0.10   | 0.97          | 0.18           | 0.03           | 0.36           |
|                     | Monument                | 0.11          | 0.07       | 0.08   | 0.97          | 0.13           | 0.03           | 0.31           |
|                     | Food                    | 0.38          | 0.30       | 0.31   | 0.92          | 0.12           | 0.08           | 0.26           |
|                     | Written Work            | 0.39          | 0.35       | 0.36   | 0.90          | 0.20           | 0.10           | 0.50           |
|                     | Sports Team             | 0.41          | 0.28       | 0.31   | 0.90          | 0.11           | 0.10           | 0.24           |
|                     | City                    | 0.10          | 0.09       | 0.09   | 0.96          | 0.07           | 0.04           | 0.68           |
|                     | Artist                  | 0.35          | 0.22       | 0.26   | 0.83          | 0.07           | 0.17           | 0.26           |
|                     | Scientist               | 0.42          | 0.33       | 0.34   | 0.92          | 0.14           | 0.08           | 0.43           |
|                     | Film                    | 0.18          | 0.14       | 0.15   | 0.82          | 0.08           | 0.18           | 0.33           |
|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
|                     | University              | 0.29          | 0.10       | 0.15   | 0.78          | 0.22           | 0.00           | 0.06           |
|                     | Musical Work            | 0.25          | 0.17       | 0.19   | 0.67          | 0.33           | 0.39           | 0.31           |
|                     | Airport                 | 0.23          | 0.11       | 0.14   | 0.76          | 0.24           | 0.02           | 0.12           |
|                     | Building                | 0.35          | 0.13       | 0.19   | 0.92          | 0.08           | 0.01           | 0.09           |
|                     | Athlete                 | 0.42          | 0.21       | 0.27   | 0.89          | 0.11           | 0.00           | 0.20           |
|                     | Politician              | 0.50          | 0.21       | 0.28   | 0.87          | 0.13           | 0.07           | 0.16           |
|                     | Company                 | 0.41          | 0.16       | 0.23   | 0.63          | 0.37           | 0.11           | 0.33           |
|**LLama3**           | Celestial Body          | 0.31          | 0.15       | 0.19   | 0.98          | 0.02           | 0.03           | 0.26           |
|                     | Astronaut               | 0.53          | 0.17       | 0.24   | 0.79          | 0.21           | 0.00           | 0.54           |
|                     | Comics Character        | 0.55          | 0.22       | 0.30   | 1.00          | 0.00           | 0.53           | 0.04           |
|                     | Means of Transportation | 0.24          | 0.10       | 0.13   | 0.73          | 0.27           | 0.00           | 0.21           |
|                     | Monument                | 0.05          | 0.02       | 0.03   | 0.72          | 0.28           | 0.11           | 0.21           |
|                     | Food                    | 0.45          | 0.18       | 0.25   | 0.85          | 0.15           | 0.01           | 0.13           |
|                     | Written Work            | 0.38          | 0.16       | 0.21   | 0.84          | 0.16           | 0.07           | 0.23           |
|                     | Sports Team             | 0.44          | 0.16       | 0.22   | 0.88          | 0.12           | 0.06           | 0.14           |
|                     | City                    | 0.10          | 0.06       | 0.07   | 0.83          | 0.17           | 0.04           | 0.69           |
|                     | Artist                  | 0.38          | 0.14       | 0.20   | 0.86          | 0.14           | 0.01           | 0.06           |
|                     | Scientist               | 0.62          | 0.36       | 0.42   | 0.87          | 0.13           | 0.00           | 0.37           |
|                     | Film                    | 0.25          | 0.17       | 0.19   | 0.83          | 0.17           | 0.02           | 0.30           |
|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| **Average**         |                         | **0.36**      | **0.15**   | **0.20** | **0.81**    | **0.19**       | **0.10**       | **0.23**       |
|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| LLM Model Name      | Ontology         | avg_precision | avg_recall | avg_f1 | avg_onto_conf | avg_rel_halluc | avg_sub_halluc | avg_obj_halluc |
|---------------------|------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
|                     | University       | 0.34          | 0.11       | 0.16   | 0.90          | 0.10           | 0.01           | 0.03           |
|                     | Musical Work     | 0.16          | 0.11       | 0.12   | 0.79          | 0.21           | 0.32           | 0.24           |
|                     | Airport          | 0.25          | 0.10       | 0.14   | 0.79          | 0.21           | 0.00           | 0.16           |
|                     | Building         | 0.39          | 0.13       | 0.19   | 0.87          | 0.13           | 0.04           | 0.13           |
|                     | Athlete          | 0.40          | 0.14       | 0.21   | 0.90          | 0.10           | 0.02           | 0.21           |
|                     | Politician       | 0.46          | 0.16       | 0.23   | 0.91          | 0.09           | 0.02           | 0.18           |
|                     | Company          | 0.48          | 0.20       | 0.27   | 0.76          | 0.24           | 0.11           | 0.29           |
|                     | Celestial Body   | 0.57          | 0.25       | 0.33   | 0.92          | 0.08           | 0.01           | 0.43           |
|                     | Astronaut        | 0.46          | 0.13       | 0.20   | 0.90          | 0.10           | 0.01           | 0.53           |
|                     | Comics Character | 0.42          | 0.14       | 0.21   | 0.92          | 0.08           | 0.58           | 0.14           |
|                     | Transportation   | 0.29          | 0.10       | 0.14   | 0.78          | 0.22           | 0.03           | 0.30           |
|                     | Monument         | 0.16          | 0.05       | 0.08   | 1.00          | 0.00           | 0.00           | 0.00           |
|                     | Food             | 0.47          | 0.16       | 0.24   | 0.94          | 0.06           | 0.03           | 0.07           |
|                     | Written Work     | 0.39          | 0.13       | 0.19   | 0.97          | 0.03           | 0.08           | 0.26           |
|                     | Sports Team      | 0.25          | 0.08       | 0.12   | 0.85          | 0.15           | 0.04           | 0.19           |
|                     | City             | 0.03          | 0.01       | 0.01   | 0.89          | 0.11           | 0.03           | 0.42           |
|                     | Artist           | 0.33          | 0.11       | 0.17   | 0.78          | 0.22           | 0.00           | 0.10           |
|                     | Scientist        | 0.60          | 0.33       | 0.39   | 0.82          | 0.18           | 0.02           | 0.32           |
|                     | Film             | 0.40          | 0.22       | 0.26   | 0.84          | 0.16           | 0.04           | 0.27           |
|---------------------|------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| **Average**         |                  | **0.36**      | **0.14**   | **0.19** | **0.87**      | **0.12**       | **0.08**       | **0.23**     |

|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| **Vicuna-13B**      | University              | 0.31          | 0.19       | 0.23   | 0.92          | 0.11           | 0.08           | 0.21           |
|                     | Musical Work            | 0.20          | 0.18       | 0.18   | 0.89          | 0.32           | 0.11           | 0.27           |
|                     | Airport                 | 0.33          | 0.24       | 0.27   | 0.92          | 0.03           | 0.08           | 0.27           |
|                     | Building                | 0.48          | 0.33       | 0.38   | 0.98          | 0.02           | 0.02           | 0.22           |
|                     | Athlete                 | 0.33          | 0.26       | 0.29   | 0.92          | 0.01           | 0.08           | 0.13           |
|                     | Politician              | 0.39          | 0.28       | 0.32   | 0.89          | 0.11           | 0.11           | 0.29           |
|                     | Company                 | 0.49          | 0.37       | 0.41   | 1.00          | 0.09           | 0.00           | 0.36           |
|                     | Celestial Body          | 0.48          | 0.46       | 0.46   | 0.97          | 0.05           | 0.03           | 0.46           |
|                     | Astronaut               | 0.40          | 0.28       | 0.32   | 0.87          | 0.06           | 0.13           | 0.28           |
|                     | Comics Character        | 0.41          | 0.41       | 0.40   | 0.97          | 0.64           | 0.03           | 0.28           |
|                     | Means of Transportation | 0.22          | 0.17       | 0.18   | 0.94          | 0.14           | 0.06           | 0.41           |
|                     | Monument                | 0.04          | 0.05       | 0.05   | 0.94          | 0.18           | 0.06           | 0.31           |
|                     | Food                    | 0.43          | 0.39       | 0.39   | 0.94          | 0.05           | 0.06           | 0.20           |
|                     | Written Work            | 0.40          | 0.34       | 0.36   | 0.92          | 0.12           | 0.08           | 0.33           |
|                     | Sports Team             | 0.52          | 0.38       | 0.42   | 0.91          | 0.04           | 0.09           | 0.11           |
|                     | City                    | 0.12          | 0.12       | 0.12   | 0.98          | 0.04           | 0.02           | 0.67           |
|                     | Artist                  | 0.30          | 0.21       | 0.23   | 0.89          | 0.03           | 0.11           | 0.13           |
|                     | Scientist               | 0.52          | 0.43       | 0.46   | 0.95          | 0.05           | 0.05           | 0.30           |
|                     | Film                    | 0.23          | 0.19       | 0.20   | 0.94          | 0.30           | 0.06           | 0.19           |
|---------------------|-------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|

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
