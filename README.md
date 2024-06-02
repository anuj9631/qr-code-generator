# QR Code Generator

This project is a QR Code Generator created using Node.js along with the packages `inquirer`, `qr-image`, and `fs`. It allows users to generate QR codes from text input (such as a URL) and save them as image files.

## Features

- Command-line interface for user interaction
- Generate QR codes from user-provided text or links
- Save QR codes as image files

## Prerequisites

- Node.js installed on your machine
- NPM (Node Package Manager)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/qr-code-generator.git
    ```

2. Navigate to the project directory:

    ```sh
    cd qr-code-generator
    ```

3. Install the required packages:

    ```sh
    npm install
    ```

## Usage

1. Run the application:

    ```sh
    node index.js
    ```

2. Follow the prompts to enter the text or link you want to convert into a QR code (e.g., `google.com`).

3. The generated QR code will be saved as an image file in the project directory.

## Packages Used

- [`inquirer`](https://www.npmjs.com/package/inquirer): For creating a command-line interface.
- [`qr-image`](https://www.npmjs.com/package/qr-image): For generating QR codes.
- [`fs`](https://nodejs.org/api/fs.html): For handling the file system to save QR code images.

## Example

```sh
$ node index.js
? Enter the text to generate QR code: google.com
QR code generated and saved as qrcode.png
