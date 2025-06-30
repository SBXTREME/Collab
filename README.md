# Collab - Talk to Your PDF Without Knowledge Graph

This repository contains a Jupyter Notebook that allows you to interact with PDF documents using natural language, without relying on a Knowledge Graph (KG).  
The main notebook is: `talk_to_your_pdf_without_KG.ipynb`.

## Features

- Upload and process PDF files directly in a Jupyter Notebook.
- Ask questions about the content of the PDF using natural language.
- Get answers extracted and summarized from the document.
- No external Knowledge Graph required.

## Getting Started

### Prerequisites

- Python 3.9+
- Google Collab Environment ( Free to use with T4 GPU )

### Required Python Packages

!pip install langchain sentence-transformers PyPDF2 faiss-cpu

### Usage

1. Open the notebook in Google Colab or your local Jupyter environment:
    - [Open in Google Colab](https://colab.research.google.com/github/SBXTREME/Collab/blob/main/talk_to_your_pdf_without_KG.ipynb)

2. Run each cell in order, following the instructions provided in the notebook.

3. Upload your PDF file in the collab env.

4. Ask questions about your PDF in the provided input cells.

## Example

```python
# Example usage in the notebook:
# Upload your PDF, then:
question = "What is Tenecteplase?"
answer = ask_pdf(question)
print(answer)
```

## Notes

- For best results, use clear and concise questions.
