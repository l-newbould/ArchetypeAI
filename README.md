# ArchetypeAI

A project that analyzes character descriptions and classifies them into 12 archetypes in TV shows and movies using BERT.

Using the Hugging Face Transformers library, the project fine-tunes the distilbert-base-uncased model to achieve high accuracy and deploy a robust classification pipeline.

### Features

- Fine-tune a pre-trained model (distilbert-base-uncased) for text classification.
- Hyperparameter optimization using Optuna.
- Deploy model with Gradio.

### Installation

To set up this project, ensure the following packages are installed.

transformers (4.47.1)
datasets (3.2.0)
numpy (1.26.4)
optuna (4.1.0)
torch (2.0.1)
