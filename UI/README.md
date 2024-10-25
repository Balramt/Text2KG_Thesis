# Text to RDF Triple Generator along with Knowledge grapgh with LLM model

This project provides an interactive UI for generating RDF triples from text files using large language models, specifically Llama 3 and Mistral, and visualizing the results as a knowledge graph. Built using Gradio, this application allows users to upload a text file, select a model, and generate entity-relationship triples automatically.

## Features

- **File Upload and Model Selection**: Choose between Llama 3 or Mistral models for RDF triple generation based on the uploaded text file.
- **Triple Extraction**: Generates RDF triples (subject, relation, object) from model output.
- **Knowledge Graph Visualization**: Constructs and displays a knowledge graph from the generated triples using `networkx` and `matplotlib`.
- **User Interface**: A Gradio interface for easy interaction, suitable for quick testing and experimentation.

## Requirements

To run this project, install the required Python packages:
```bash
pip install torch transformers matplotlib networkx gradio
```

## How It Works

### 1. Model Setup

The application loads the selected model (either Llama 3 or Mistral) using Hugging Face's `transformers` library with optimized 4-bit quantization to improve speed and reduce memory usage. The model is used for text generation, extracting relevant information from the text input.

### 2. Triple Generation

After text is generated based on the user input:
- **Named Entity Recognition (NER)**: Recognizes and extracts entities within the provided text.
- **Relation Extraction**: Identifies relationships between entities to structure output as triples.
- **Parsing**: Parses the generated text for a consistent (subject, relation, object) format.

### 3. Knowledge Graph Construction

The `networkx` library is used to visualize relationships by creating a directed graph from extracted triples, with entities as nodes and relations as labeled edges. The graph is then saved and displayed.

## How to Use

1. **Upload a Text File**: Upload a text file that contains text for triple generation.
2. **Select Model**: Choose between the Llama 3 and Mistral models.
3. **Generate RDF Triples**: Click on "Generate RDF Triples" to extract entities and relationships.
4. **View Results**:
   - **Extracted Triples**: The output field will show extracted triples in RDF format.
   - **Knowledge Graph**: An image of the generated knowledge graph is displayed, illustrating entity relationships visually.

## Code Explanation

### Core Functions

- `generate_text`: Generates a text response from the selected model based on the input prompt.
- `extract_test_output`: Parses the model output to isolate and structure relevant information.
- `parse_model_output`: Formats the generated output as RDF triples for knowledge graph creation.
- `generate_knowledge_graph`: Visualizes the knowledge graph based on extracted RDF triples using `networkx`.

### Gradio Interface

- **File Input**: Allows users to upload a text file for processing.
- **Dropdown Menu**: Enables selection of Llama 3 or Mistral as the model.
- **Output Fields**: Displays generated RDF triples and an image of the constructed knowledge graph.

## Launching the Application

Run the notebook or Python script to start the Gradio app. To share the app publicly, enable `share=True` in `demo.launch()`.
