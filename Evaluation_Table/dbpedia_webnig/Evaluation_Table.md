# Evaluation Metrics Table

The following table presents the evaluation metrics for three different language models: **Alpaca-LoRA-13B**, **LLAMA3**, and **Vicuna-13B**. These metrics provide insights into the performance of each model across various categories, such as University, Musical Work, Airport, Building, Athlete, Politician, Company, Celestial Body, Astronaut, Comics Character, Means of Transportation, Monument, Food, Written Work, Sports Team, City, Artist, Scientist, and Film. The evaluation metrics include average precision, average recall, average F1 score, average ontological confidence, and various types of hallucinations (subjective, relational, and objective).

### Combined Performance Metrics for LLM Models
| LLM Name           | Evaluation Metrics | avg_precision | avg_recall | avg_f1 | avg_onto_conf| avg_sub_halluc | avg_rel_halluc | avg_obj_halluc |
|--------------------|--------------------|---------------|------------|--------|--------------|----------------|----------------|----------------|
|LLama 3-8B          | University         | 0.58          | 0.41       | 0.46   | 0.65         | 0.36           | 0.00           | 0.06           |
|                    | Musicalwork        | 0.33          | 0.27       | 0.29   | 0.71         | 0.30           | 0.48           | 0.29           |
|                    | Airport            | 0.50          | 0.38       | 0.42   | 0.72         | 0.29           | 0.01           | 0.15           |
|                    | Building           | 0.51          | 0.45       | 0.46   | 0.86         | 0.15           | 0.00           | 0.13           |
|                    | Athlete            | 0.57          | 0.51       | 0.53   | 0.86         | 0.15           | 0.00           | 0.14           |
|                    | Politician         | 0.56          | 0.53       | 0.53   | 0.91         | 0.10           | 0.08           | 0.20           |
|                    | Company            | 0.64          | 0.54       | 0.57   | 0.67         | 0.34           | 0.11           | 0.36           |
|                    | Celestialbody      | 0.62          | 0.61       | 0.61   | 0.93         | 0.08           | 0.10           | 0.42           |
|                    | Astronaut          | 0.54          | 0.50       | 0.51   | 0.85         | 0.16           | 0.02           | 0.46           |
|                    | Comicscharacter    | 0.49          | 0.47       | 0.48   | 0.94         | 0.07           | 0.45           | 0.16           |
|                    | Meanoftransportation | 0.42        | 0.33       | 0.35   | 0.69         | 0.32           | 0.00           | 0.22           |
|                    | Monument           | 0.20          | 0.19       | 0.19   | 0.85         | 0.16           | 0.00           | 0.15           |
|                    | Food               | 0.63          | 0.59       | 0.60   | 0.90         | 0.11           | 0.02           | 0.10           |
|                    | Writtenwork        | 0.60          | 0.58       | 0.58   | 0.93         | 0.08           | 0.11           | 0.33           |
|                    | Sportsteam         | 0.58          | 0.56       | 0.56   | 0.94         | 0.07           | 0.07           | 0.12           |
|                    | City               | 0.16          | 0.17       | 0.17   | 0.83         | 0.18           | 0.04           | 0.66           |
|                    | Artist             | 0.45          | 0.35       | 0.38   | 0.77         | 0.24           | 0.01           | 0.08           |
|                    | Scientist          | 0.74          | 0.65       | 0.68   | 0.84         | 0.17           | 0.01           | 0.25           |
|                    | Film               | 0.45          | 0.39       | 0.41   | 0.84         | 0.17           | 0.01           | 0.18           |
|--------------------|--------------------|---------------|------------|--------|--------------|----------------|----------------|----------------|
|                    | **Average**        | 0.50          | 0.44       | 0.46   | 0.83         | 0.18           | 0.09           | 0.24           |
|--------------------|--------------------|---------------|------------|--------|--------------|-----------------|----------------|---------------|
| Mistral            | University         | 0.34          | 0.11       | 0.16   | 0.90         | 0.01           | 0.10           | 0.03          |
|                    | Musicalwork        | 0.16          | 0.11       | 0.12   | 0.79         | 0.32           | 0.21           | 0.24          |
|                    | Airport            | 0.25          | 0.10       | 0.14   | 0.79         | 0.00           | 0.21           | 0.16          |
|                    | Building           | 0.39          | 0.13       | 0.19   | 0.87         | 0.04           | 0.13           | 0.13          |
|                    | Athlete            | 0.40          | 0.14       | 0.21   | 0.90         | 0.02           | 0.10           | 0.21          |
|                    | Politician         | 0.46          | 0.16       | 0.23   | 0.91         | 0.02           | 0.09           | 0.18          |
|                    | Company            | 0.48          | 0.20       | 0.27   | 0.76         | 0.11           | 0.24           | 0.29          |
|                    | Celestialbody      | 0.57          | 0.25       | 0.33   | 0.92         | 0.01           | 0.08           | 0.43          |
|                    | Astronaut          | 0.46          | 0.13       | 0.20   | 0.90         | 0.01           | 0.10           | 0.53          |
|                    | Comicscharacter    | 0.42          | 0.14       | 0.21   | 0.92         | 0.58           | 0.08           | 0.14          |
|                    | Meanoftransportation | 0.29        | 0.10       | 0.14   | 0.78         | 0.03           | 0.22           | 0.30          |
|                    | Monument           | 0.16          | 0.05       | 0.08   | 1.00         | 0.00           | 0.00           | 0.00          |
|                    | Food               | 0.47          | 0.16       | 0.24   | 0.94         | 0.03           | 0.06           | 0.07          |
|                    | Writtenwork        | 0.39          | 0.13       | 0.20   | 0.97         | 0.03           | 0.08           | 0.26          |
|                    | Sportsteam         | 0.25          | 0.08       | 0.12   | 0.88         | 0.04           | 0.15           | 0.19          |
|                    | City               | 0.03          | 0.01       | 0.01   | 0.89         | 0.03           | 0.11           | 0.42          |
|                    | Artist             | 0.33          | 0.11       | 0.17   | 0.78         | 0.00           | 0.22           | 0.10          |
|                    | Scientist          | 0.60          | 0.33       | 0.39   | 0.82         | 0.02           | 0.18           | 0.32          |
|                    | Film               | 0.40          | 0.22       | 0.26   | 0.84         | 0.04           | 0.16           | 0.27          |
|--------------------|--------------------|---------------|------------|--------|--------------|----------------|----------------|---------------|
|                    | **Average**        | 0.33          | 0.16       | 0.20   | 0.81         | 0.07           | 0.16           | 0.19          |
|--------------------|--------------------|---------------|------------|--------|--------------|-----------------|----------------|---------------|
| Alpaca-LoRA-13B    | University         | 0.29          | 0.16       | 0.20   | 0.89         | 0.13           | 0.11           | 0.26          |
|                    | Musicalwork        | 0.18          | 0.15       | 0.15   | 0.85         | 0.32           | 0.15           | 0.33          |
|                    | Airport            | 0.28          | 0.18       | 0.20   | 0.94         | 0.12           | 0.06           | 0.45          |
|                    | Building           | 0.35          | 0.27       | 0.29   | 0.93         | 0.17           | 0.07           | 0.32          |
|                    | Athlete            | 0.38          | 0.30       | 0.32   | 0.94         | 0.11           | 0.06           | 0.27          |
|                    | Politician         | 0.39          | 0.27       | 0.30   | 0.92         | 0.15           | 0.08           | 0.38          |
|                    | Company            | 0.35          | 0.21       | 0.25   | 0.95         | 0.17           | 0.05           | 0.44          |
|                    | Celestialbody      | 0.52          | 0.44       | 0.47   | 0.96         | 0.12           | 0.04           | 0.49          |
|                    | Astronaut          | 0.34          | 0.21       | 0.25   | 0.87         | 0.08           | 0.13           | 0.58          |
|                    | Comicscharacter    | 0.52          | 0.41       | 0.45   | 0.93         | 0.62           | 0.07           | 0.42          |
|                    | Meanoftransportation | 0.13        | 0.09       | 0.10   | 0.97         | 0.18           | 0.03           | 0.36          |
|                    | Monument           | 0.11          | 0.07       | 0.08   | 0.97         | 0.13           | 0.03           | 0.31          |
|                    | Food               | 0.38          | 0.30       | 0.31   | 0.92         | 0.12           | 0.08           | 0.26          |
|                    | Writtenwork        | 0.39          | 0.35       | 0.36   | 0.90         | 0.20           | 0.10           | 0.50          |
|                    | Sportsteam         | 0.41          | 0.28       | 0.31   | 0.90         | 0.11           | 0.10           | 0.24          |
|                    | City               | 0.10          | 0.09       | 0.09   | 0.96         | 0.07           | 0.04           | 0.68          |
|                    | Artist             | 0.35          | 0.22       | 0.26   | 0.83         | 0.07           | 0.17           | 0.26          |
|                    | Scientist          | 0.42          | 0.33       | 0.34   | 0.92         | 0.14           | 0.08           | 0.43          |
|                    | Film               | 0.18          | 0.14       | 0.15   | 0.82         | 0.08           | 0.18           | 0.33          |
|--------------------|--------------------|---------------|------------|--------|--------------|----------------|----------------|----------------|
|                    | **Average**        | 0.27          | 0.23       | 0.25   | 0.91         | 0.16           | 0.17           | 0.23          |
|--------------------|------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
| Vicuna             | University             | 0.31          | 0.19       | 0.23   | 0.92          | 0.11           | 0.08           | 0.21           |
|                    | Musicalwork            | 0.20          | 0.18       | 0.18   | 0.89          | 0.32           | 0.11           | 0.27           |
|                    | Airport                | 0.33          | 0.24       | 0.27   | 0.92          | 0.03           | 0.08           | 0.27           |
|                    | Building               | 0.48          | 0.33       | 0.38   | 0.98          | 0.02           | 0.02           | 0.22           |
|                    | Athlete                | 0.33          | 0.26       | 0.29   | 0.92          | 0.01           | 0.08           | 0.13           |
|                    | Politician             | 0.39          | 0.28       | 0.32   | 0.89          | 0.11           | 0.11           | 0.29           |
|                    | Company                | 0.49          | 0.37       | 0.41   | 1.00          | 0.09           | 0.00           | 0.36           |
|                    | Celestialbody          | 0.48          | 0.46       | 0.46   | 0.97          | 0.05           | 0.03           | 0.46           |
|                    | Astronaut              | 0.40          | 0.28       | 0.32   | 0.87          | 0.06           | 0.13           | 0.28           |
|                    | Comicscharacter        | 0.41          | 0.41       | 0.40   | 0.97          | 0.64           | 0.03           | 0.28           |
|                    | Meanoftransportation   | 0.22          | 0.17       | 0.18   | 0.94          | 0.14           | 0.06           | 0.41           |
|                    | Monument               | 0.04          | 0.05       | 0.05   | 0.94          | 0.18           | 0.06           | 0.31           |
|                    | Food                   | 0.43          | 0.39       | 0.39   | 0.94          | 0.05           | 0.06           | 0.20           |
|                    | Writtenwork            | 0.40          | 0.34       | 0.36   | 0.92          | 0.12           | 0.08           | 0.33           |
|                    | Sportsteam             | 0.52          | 0.38       | 0.42   | 0.91          | 0.04           | 0.09           | 0.11           |
|                    | City                   | 0.12          | 0.12       | 0.12   | 0.98          | 0.04           | 0.02           | 0.67           |
|                    | Artist                 | 0.30          | 0.21       | 0.23   | 0.89          | 0.03           | 0.11           | 0.13           |
|                    | Scientist              | 0.52          | 0.43       | 0.46   | 0.95          | 0.05           | 0.05           | 0.30           |
|                    | Film                   | 0.23          | 0.19       | 0.20   | 0.94          | 0.30           | 0.06           | 0.19           |
|--------------------|------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
|                    | **Average**            | 0.36          | 0.26       | 0.29   | 0.92          | 0.11           | 0.07           | 0.27           |
|--------------------|------------------------|---------------|------------|--------|---------------|----------------|----------------|----------------|
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
