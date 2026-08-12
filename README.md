# Image Encryption Tool - Task 02

## Prodigy InfoTech Cyber Security Internship

### Objective
Develop a simple image encryption tool using pixel manipulation. The tool allows users to encrypt and decrypt images using a basic mathematical operation on pixel values.

## Features
- Upload an image
- Encrypt image using pixel manipulation
- Decrypt the encrypted image
- Uses a user-defined encryption key
- Supports RGB images
- Download encrypted and decrypted images

## Technologies Used
- Python
- Google Colab
- Pillow (PIL)

## How It Works
The program modifies the RGB values of each pixel using a mathematical operation and an encryption key.

For encryption, the key is added to each RGB value.

For decryption, the negative value of the same key is used to restore the original pixel values.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Upload an image.
4. Enter/use the encryption key.
5. Run the encryption process.
6. Save and download the encrypted image.
7. Run the decryption process to restore the original image.

## Sample Encryption
The original image is transformed by modifying its pixel values.

## Sample Decryption
The encrypted image is processed using the reverse operation to restore the original image.

## Author
Sanchita Kalbage
