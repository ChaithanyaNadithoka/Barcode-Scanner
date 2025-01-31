# Barcode Scanner using OpenCV & PyZbar

## Overview

This project is a simple barcode scanner built using OpenCV, PyZbar, and PIL. It processes an uploaded image, detects barcodes, highlights them with bounding boxes, and decodes the barcode data.

## Features

- Reads barcode images and extracts data
- Uses OpenCV for image processing and enhancement
- Utilizes PyZbar for barcode detection and decoding
- Displays the processed image with bounding boxes

## Requirements

Ensure you have the following dependencies installed:

- Python
- OpenCV
- NumPy
- PyZbar
- PIL (Pillow)
- Google Colab (for easy execution in a notebook environment)

## Installation

Run the following commands to install dependencies:

```bash
!apt-get update
!apt-get install -y zbar-tools libzbar-dev
!pip install pyzbar pillow opencv-python numpy
```

## Usage

1. Upload an image containing a barcode.
2. The script will preprocess the image and detect barcodes.
3. The barcode will be highlighted with a bounding box.
4. The decoded barcode data will be printed.

## Running the Code

Upload the script to Google Colab or run it in a local Python environment:

```python
python barcode_scanner.py
```

## Example Output

- Bounding box around detected barcode(s).
- Decoded barcode data printed in the console.

## License

This project is open-source and available under the MIT License.

## Author

Chaithanya N


