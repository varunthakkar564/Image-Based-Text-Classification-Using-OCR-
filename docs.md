# Image Based Text Classification Using OCR - Documentation

Welcome to the documentation for Image Based Text Classification Using OCR! This document provides detailed information about the architecture, functionality, and usage of the Image Based Text Classification Using OCR project.

## Overview

Image Based Text Classification Using OCR is a Streamlit web application designed to extract text from images, perform spell-checking, sentiment analysis, and extract keywords from the extracted text.

## Architecture

It consists of the following components:

1. **Frontend**: Developed using Streamlit, provides a user-friendly interface for uploading images and interacting with the application.
2. **Backend**: Utilizes Python libraries such as pytesseract, TextBlob, and scikit-learn for text extraction, spell-checking, sentiment analysis, and keyword extraction.
3. **Tesseract OCR**: Integrated for text extraction from images.
4. **TextBlob**: Used for sentiment analysis.
5. **Other Libraries**: Various other libraries such as difflib, PIL, and re are used for text processing and manipulation.



### Installation

To install, follow these steps:

1. Clone the repository: git clone https://github.com/varunthakkar564/Image-Based-Text-Classification-Using-OCR-
2. Navigate to the project directory: cd Image-Based-Text-Classification-Using-OCR-
3. Install dependencies: pip install -r requirements.txt


### Running the Application

To run, execute the following command: streamlit run main.py


## APIs and Interfaces

The application exposes the following APIs and interfaces:

- `extract_text(image)`: Extracts text from an image using Tesseract OCR.
- `spell_check(text)`: Performs spell-checking on the extracted text.
- `analyze_sentiment(text)`: Analyzes the sentiment of the extracted text.
- `extract_keywords(text)`: Extracts keywords from the extracted and corrected text.

## Tutorials and Guides

For detailed usage instructions and tutorials, refer to the [README.md](README.md) file in the repository.

## FAQs and Troubleshooting

If you encounter any issues or have questions, please refer to the FAQs section in the [README.md](README.md) file.

## Contributing

We welcome contributions from the community! If you'd like to contribute to this industrial project, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.
