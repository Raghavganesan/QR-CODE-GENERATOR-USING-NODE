# QR-CODE-GENERATOR-USING-NODE

## Introduction
This is a simple Node.js command-line application that generates a QR code image from a URL you provide. It also saves the input URL to a text file for reference.

## Features
- Interactive prompt to input a URL using the `inquirer` package.
- Generates a QR code image (PNG format) from the URL using the `qr-image` package.
- Saves the input URL into a text file named `URL.txt`.
- Error handling for file operations.
- Easy to use and set up.

## Packages Used
- [inquirer](https://www.npmjs.com/package/inquirer) - For interactive command-line prompts.
- [qr-image](https://www.npmjs.com/package/qr-image) - To generate QR code images.
- [fs](https://nodejs.org/api/fs.html) - Node.js file system module to write files.


## How to Run
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Execute the app using `node your_script_name.js`.
4. Enter your URL when prompted.
5. The QR code image will be saved as `qr_image.png`, and the URL will be saved in `URL.txt`.

## Result
Upon successful completion, you will have:

<img width="1140" height="162" alt="image" src="https://github.com/user-attachments/assets/db1bb1b7-97ca-4160-908c-8e6c3be51606" />

- A QR code image `qr_image.png` representing your URL.

<img width="429" height="432" alt="image" src="https://github.com/user-attachments/assets/c967ca1c-3b4c-4a5a-977d-54ea9e866caa" />

- A text file `URL.txt` containing the saved URL.

<img width="562" height="169" alt="image" src="https://github.com/user-attachments/assets/d153439e-b237-4704-a6bb-ad201cb10ca5" />


