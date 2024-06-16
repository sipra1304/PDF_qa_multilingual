 # Multilingual PDF Question Answering System 

## Overview

Welcome to the Multilingual PDF Question Answering System! This project is designed to help users interact with PDF documents by extracting text and answering questions related to the content. The system supports multiple languages, providing translated answers in English, Hindi, French, and Spanish.

## Features

- **PDF Upload:** Users can upload their PDF documents directly through the interface.
- **Text Extraction:** Utilizes Tesseract OCR to extract text from each page of the PDF.
- **Question Answering:** Employs pre-trained NLP models to answer user questions based on the content of the PDF.
- **Multilingual Support:** Provides answers in the user's preferred language, including English, Hindi, French, and Spanish.
- **Translation:** Uses state-of-the-art translation models to translate answers into the selected language.

## Tech Stack

- **Google Colab:** A cloud-based Jupyter notebook environment that provides free access to GPU resources.
- **Python:** The primary programming language used for implementing the functionalities.
- **Transformers Library (Hugging Face):** Includes pre-trained models for question answering, translation, and text extraction.
  - **LayoutLMForQuestionAnswering:** For document-based question answering.
  - **RobertaForQuestionAnswering:** For general question answering.
  - **T5ForConditionalGeneration:** For translation tasks.
- **PDF Processing Libraries:**
  - **pdf2image:** Converts PDF pages into images.
  - **Pillow:** Handles image processing tasks.
  - **pytesseract:** Performs OCR to extract text from images.
- **Google Colab Libraries:**
  - **google.colab:** Utilities for file upload/download in Google Colab.

## How It Works

1. **Upload PDF:**
   - Users upload their PDF files using the provided interface.
2. **Convert PDF to Images:**
   - Each page of the PDF is converted into an image.
3. **Extract Text:**
   - Text is extracted from each image using OCR.
4. **Answer Questions:**
   - Users input questions related to the PDF content.
   - The system uses NLP models to find and return answers.
5. **Translate Answers:**
   - Answers are translated into the user's preferred language if needed.

## Installation and Usage

### Instructions

1. **Open in Google Colab:**
   - Upload the notebook file `multilingual_pdf_qa_system.ipynb` to your Google Drive.
   - Open the notebook in Google Colab.

2. **Run the Notebook:**
   - Follow the instructions in the notebook to upload your PDF and start asking questions.

## Example Workflow

1. **Upload PDF:**
   - Upload your PDF document.
2. **Select Language:**
   - Choose your preferred language for answers.
3. **Ask Questions:**
   - Input your questions related to the PDF content.
4. **Get Answers:**
   - Receive answers in your selected language.

## Contributing

We welcome contributions to enhance the system's capabilities. Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Hugging Face](https://huggingface.co/) for providing pre-trained models and the `transformers` library.
- [Google Colab](https://colab.research.google.com/) for the free cloud-based Jupyter notebook environment.
