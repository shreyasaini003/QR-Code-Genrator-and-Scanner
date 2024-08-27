# QR Code Generator and Scanner

This project is a simple Python application that allows you to generate and scan QR codes. It provides an easy way to encode data into a QR code image and decode data from an existing QR code.

## Features

- **QR Code Generation:** Enter any text or data, and the application generates a QR code image file.
- **QR Code Scanning:** Upload a QR code image to decode and retrieve the embedded data.

## Technologies Used

- Python
- `qrcode` library for QR code generation
- `pyzbar` library for QR code decoding
- `PIL` (Pillow) for image processing

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/qr-code-generator-scanner.git
   cd qr-code-generator-scanner
   ```

2. Install the required dependencies:

   ```bash
   pip install qrcode[pil] pyzbar pillow
   ```

## Usage

1. Run the script:

   ```bash
   python main.py
   ```

2. Follow the on-screen prompts to either generate a new QR code or scan an existing one.

### Generating a QR Code

- Choose the option to generate a QR code.
- Enter the data you want to encode.
- Provide a filename to save the QR code image.

### Scanning a QR Code

- Choose the option to scan a QR code.
- Enter the path to the image file containing the QR code.
- The application will output the decoded data.

## Example

### Generating a QR Code

```
1. Generate QR Code
2. Scan QR Code
Enter your choice: 1
Enter data to encode: https://github.com/your-username
Enter filename to save QR Code: my_qr_code.png
QR Code generated successfully!
```

### Scanning a QR Code

```
1. Generate QR Code
2. Scan QR Code
Enter your choice: 2
Enter image path: my_qr_code.png
Scanned data: https://github.com/your-username
```

