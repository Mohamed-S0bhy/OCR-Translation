# 📄 OCR Translation Web App

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-orange)

An end-to-end web application that extracts text from documents/images and translates between English and Arabic.

![Demo GIF](./demo.gif) *(Add a screen recording later)*

## ✨ Features

- **Text Extraction**:
  - Supports images (JPG/PNG), PDFs, Word docs, and text files
  - Dual OCR engines: EasyOCR (default) and PyTesseract (optional)

- **Translation**:
  - Bidirectional English ↔ Arabic translation
  - Powered by Helsinki-NLP models from Hugging Face
  - Preserves text formatting and layout

- **Web Interface**:
  - Drag & drop file upload
  - Real-time processing
  - Responsive design (works on mobile)

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mohamed-S0bhy/OCR-Translation.git
   cd OCR-Translation
