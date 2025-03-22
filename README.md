# QR Code Generator

This is a **QR Code Generator** that allows you to generate QR codes for various types of data. The generator supports the following types:

- **Number**
- **Social Media**
- **Website Link**
- **Image URL**
- **Gmail**
- **Text**
- **WiFi**
- **Phone Number**
- **SMS**
- **VCard (Contact)**
- **Email**
- **Bitcoin**
- **YouTube**
- **Location**
- **Calendar Event**
- **PDF URL**

## Features

- Generates a QR code based on different types of data.
- Supports common use cases like website links, email addresses, phone numbers, and more.
- Easy to use and integrate into your projects.

## Installation

To use this QR Code generator, follow the steps below:

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/qr-code-generator.git
    ```

2. Navigate into the project folder:

    ```bash
    cd qr-code-generator
    ```

3. Install dependencies:

    For Python:

    ```bash
    pip install -r requirements.txt
    ```

    Or for Node.js:

    ```bash
    npm install
    ```

## Usage

You can generate QR codes by specifying the data type and input. Here's a list of supported types:

### 1. **Number**

To generate a QR code for a number, simply input the number.

### 2. **Social Media**

Generate QR codes for social media platforms like Facebook, Instagram, etc. Input the profile URL.

### 3. **Website Link**

For generating QR codes for website links, provide the full URL.

### 4. **Image URL**

Provide an image URL to generate a QR code pointing to the image.

### 5. **Gmail**

To create a QR code for a Gmail address, input the Gmail address.

### 6. **Text**

You can generate a QR code for a piece of text, such as a note or message.

### 7. **WiFi**

For WiFi, provide the SSID, password, and encryption type.

### 8. **Phone Number**

Generate a QR code for a phone number that can be scanned to call directly.

### 9. **SMS**

Provide the phone number and message for SMS QR codes.

### 10. **VCard (Contact)**

Create a QR code to store contact information using the vCard format.

### 11. **Email**

Generate a QR code for an email address that opens the default email client.

### 12. **Bitcoin**

For Bitcoin addresses, input the wallet address.

### 13. **YouTube**

Generate QR codes for YouTube video URLs.

### 14. **Location**

Generate QR codes with geographic location (latitude and longitude).

### 15. **Calendar Event**

Create a QR code for adding an event to the calendar.

### 16. **PDF URL**

Generate a QR code for a PDF document URL.

## Example

```python
import qrcode

# Example: Generate QR for a website link
qr_data = "https://example.com"
qr = qrcode.make(qr_data)
qr.show()
