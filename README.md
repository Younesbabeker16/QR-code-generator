# Custom QR Code Generator

A fully-featured, modern, and customizable QR Code Generator built with Python and CustomTkinter.

## Features
- **Multiple Input Types**: Standard Text/URL, WhatsApp, Email, and Phone number links.
- **Custom Styling**: Change foreground and background colors.
- **Advanced Patterns**: Choose between classic squares, rounded dots, circular modules, and bar styles.
- **Logo Support**: Upload and center any image/logo inside your QR code (supports transparency).
- **High Error Correction**: Automatically adjusts error correction to ensure the QR code remains scannable even with a logo.
- **Modern UI**: Clean dark-mode interface built with CustomTkinter.

## Installation

1. Ensure you have Python 3.8+ installed.
2. Navigate to the project directory:
   ```bash
   cd qr_code_generator
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main application:
```bash
python main.py
```

- Enter your desired link or text.
- Adjust colors and styles.
- (Optional) Browse for a logo image.
- Click **Generate Preview** to see the result.
- Click **Export PNG** to save a high-resolution version of your custom QR code.
