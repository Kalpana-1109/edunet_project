Secure Data Hiding in Images Using Steganography

Overview

This project demonstrates how to securely hide and extract secret messages within an image using steganography. The approach modifies pixel values in an image to embed a message that can later be retrieved using a passcode.

Features

Encrypts a secret message into an image

Uses pixel manipulation to hide text data

Requires a passcode for decryption

Outputs a modified image with hidden data

Requirements

Ensure you have the following installed:

Python 3.x

OpenCV (cv2 library)

OS module (built-in with Python)

Installation

Clone the repository:

git clone https://github.com/yourusername/steganography.git
cd steganography

Install dependencies:

pip install opencv-python

Usage

Encrypting a Message

Place an image file (e.g., pic.jpg) in the project directory.

Run the script:

python steganography.py

Enter the secret message and a passcode when prompted.

The modified image (encryptedImage.jpg) will be generated.

Decrypting a Message

Run the script again:

python steganography.py

Enter the correct passcode.

If the passcode is correct, the hidden message will be displayed.

Notes

The encryption method is basic and modifies pixel values directly.

The implementation does not use sophisticated cryptographic methods.

Use with caution, as it is not resistant to advanced steganalysis techniques.

License

This project is open-source under the MIT License.

Author

P. Kalpana

Contribution

Feel free to fork the repository and submit pull requests to improve security, optimize performance, or add new features!

