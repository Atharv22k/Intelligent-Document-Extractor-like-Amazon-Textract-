# Intelligent Document Extractor (like Amazon Textract)

## Overview

The Intelligent Document Extractor is a tool designed to extract structured data from various types of documents using advanced machine learning techniques. This project aims to provide functionalities similar to Amazon Textract, enabling users to automatically extract text, forms, tables, and other structured data from scanned documents.

## Features

- **Text Extraction**: Extracts printed and handwritten text from documents.
- **Form Recognition**: Identifies and extracts key-value pairs from forms.
- **Table Extraction**: Detects and extracts data from tables within documents.
- **Document Classification**: Classifies documents into predefined categories.
- **PIL Integration**: Integrates with Optical Character Recognition (OCR) engines for text extraction.

## Installation

To get started with the Intelligent Document Extractor, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Atharv22k/Intelligent-Document-Extractor-like-Amazon-Textract-.git
    cd Intelligent-Document-Extractor-like-Amazon-Textract-
    ```

2. **Set Up a Virtual Environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Document Extractor**:
    ```sh
    python main.py --input path/to/document.pdf --output path/to/output
    ```

2. **Specify Extraction Type**:
    - For text extraction: `--type text`
    - For form recognition: `--type form`
    - For table extraction: `--type table`

    Example:
    ```sh
    python main.py --input path/to/document.pdf --output path/to/output --type text
    ```

## Directory Structure

```
Intelligent-Document-Extractor-like-Amazon-Textract-/
├── data/
│   ├── input/
│   └── output/
├── src/
│   ├── text_extraction.py
│   ├── form_recognition.py
│   ├── table_extraction.py
│   └── document_classification.py
├── tests/
│   ├── test_text_extraction.py
│   ├── test_form_recognition.py
│   ├── test_table_extraction.py
│   └── test_document_classification.py
├── requirements.txt
├── README.md
└── main.py
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

## Acknowledgements

- Inspired by [Amazon Textract](https://aws.amazon.com/textract/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)

## Contact

For any inquiries or support, please contact [Atharv22k](https://github.com/Atharv22k).
