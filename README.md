# OCR-Pipeline-Assignment-Handwritten-document-PII-Extraction

This project implements a complete OCR and PII (Personally Identifiable Information) extraction pipeline for handwritten documents. The pipeline is designed to work with scanned JPEG images of handwritten medical and clinic-style notes.

## Features

- Preprocessing using OpenCV (denoising, contrast enhancement, resizing)
- Tilt/deskew correction for slightly rotated documents
- OCR using Tesseract and EasyOCR (hybrid approach)
- Text cleaning and normalization
- PII detection using regex patterns (names, phone numbers, ages, IDs)
- Optional image redaction for sensitive regions

## Pipeline Flow

Input Image → Preprocessing → Deskew → OCR → Text Cleaning → PII Detection → Redaction

## Project Structure

ocr-pii-extraction-assignment/
│
├── notebook.ipynb
├── requirements.txt
├── images/
├── README.md
└── Results Screenshots

## Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

Make sure Tesseract OCR is installed and its path is correctly set in the notebook.

## How to Run

Open ocr_pipeline_assignment.ipynb in Jupyter and run all cells sequentially.

You can change the image_path variable to test different handwritten document images.

## Note:

This project is built as part of a technical assignment to demonstrate OCR processing, preprocessing, and PII extraction techniques for handwritten documents.

