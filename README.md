

# PDF Text Extraction and Processing Assignment

## Overview
This assignment implements a **PDF text extraction pipeline** capable of handling both **digitally generated PDFs** and **scanned PDFs**. The solution combines traditional PDF parsing with **OCR (Optical Character Recognition)** to extract textual content, structure it, and prepare it for further analysis or downstream processing.

The notebook demonstrates how to automatically detect PDF type, apply the appropriate extraction strategy, and return clean, usable text data.

---

## Key Features
- Supports **text-based PDFs** using PDF parsing  
- Supports **scanned/image-based PDFs** using OCR  
- Automatic fallback from PDF parsing to OCR when required  
- Modular and extensible design  
- Outputs structured text suitable for analytics or ML pipelines  

---

## Technologies & Libraries Used
- **Python 3**
- **PyPDF2** – for extracting text from digital PDFs
- **pytesseract** – OCR engine for scanned PDFs
- **pdf2image** – converts PDF pages into images for OCR
- **Pillow (PIL)** – image processing
- **pandas** – structured data handling
- **pathlib / os / json** – file system and data utilities

---

