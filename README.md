# PDF Square

PDF Square is an online PDF tool built using Python and the Django framework. It provides various features for manipulating PDF files securely, including converting PDF to Word, PDF to image, and vice versa, locking PDF files, compressing PDF files, and merging PDF files.

## Features

- **PDF to Word Conversion**: Convert PDF files to Word documents with ease.
- **PDF to Image Conversion**: Convert PDF pages to images (e.g., JPEG, PNG).
- **Image to PDF Conversion**: Convert images to PDF format.
- **PDF Locking**: Secure your PDF files by adding passwords for viewing, printing, or editing.
- **PDF Compression**: Reduce the file size of PDF documents for easier sharing and storage.
- **PDF Merging**: Merge multiple PDF files into a single document.

## Security

PDF Square ensures the security and privacy of user files by employing the following measures:

- **No File Storage**: User files are not stored anywhere on the server or in any database. Files are processed in memory and discarded after processing, ensuring maximum privacy and security.
- **Encryption**: All file transfers between the client and server are encrypted using industry-standard protocols (e.g., HTTPS) to prevent unauthorized access.
- **Password Protection**: Users can optionally add password protection to their PDF files to control access.

## Requirements

To run PDF Square locally, you need to have the following installed:

- Python 3.x
- Django
- Other dependencies listed in `requirements.txt`

## Installation

1. Clone this repository to your local machine.
2. Install dependencies using pip:

   ```bash
   pip install -r requirements.txt
