# Bajaj Finserv Qualifier 2
# Lab Report Extractor API

This FastAPI-based web service processes lab report images and extracts lab test names, values, and reference ranges using OCR (Tesseract).

## Features

- Accepts lab report images via POST request
- Uses Tesseract OCR to extract text from the image
- Parses and returns structured lab test data
- Returns response in JSON format

##  Requirements

- Python 3.8+
- Tesseract OCR installed and available in system PATH
