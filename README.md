# Huggingface-Pipeline

This repository contains a Jupyter Notebook that demonstrates how to use the Hugging Face `transformers` library for natural language processing (NLP) tasks using pipelines.

## Features

- Utilizes the `transformers` library by Hugging Face
- Demonstrates pre-trained model usage for NLP tasks
- Easy-to-use pipeline setup for inference

## Installation

To run the notebook locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   If the `requirements.txt` file is not available, install manually:
   ```bash
   pip install transformers torch
   ```

## Usage

Open and run the Jupyter Notebook:

```bash
jupyter notebook "huggingface pipeline.ipynb"
```

Follow the instructions inside the notebook to explore various NLP tasks like text classification, named entity recognition (NER), and more.

## Contributing

Feel free to contribute to this project by submitting pull requests or raising issues.

## Author

Dheemanth Macherla

## License

This project is licensed under the MIT License.

