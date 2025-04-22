# Scanned PDF Effect

This project provides a Python script to apply a scanned-like effect to PDF documents. It converts each page of a PDF into an image, adds noise, applies a slight rotation, blurs the image, and then converts the processed images back into a single PDF.

## Features

- Converts PDF pages to images.
- Applies a realistic scanned effect (noise, rotation, blur) to each page image.
- Converts processed images back into a single PDF.

## Installation

The script requires the following Python libraries:

- `opencv-python-headless`
- `numpy`
- `PyMuPDF`

You can install them using pip:

```bash
!pip install opencv-python-headless numpy PyMuPDF
