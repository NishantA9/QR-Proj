# QRGenerator

This project allows users to enter a URL, and it will generate a QR code image for that URL. The generated QR code can then be scanned to access the provided URL.
Let's start by setting up our project. Make sure you have Node.js installed on your machine. We'll use the inquirer package to get user input, the qr-image package to generate the QR code, and the fs module to handle file operations.
First, let's create our project directory and initialize it:

mkdir qr-code-generator
cd qr-code-generator
npm init -y

Next, we'll install the required dependencies: npm install inquirer qr-image fs
once everything is install, To run the project, simply execute the index.js file: node index.js or nodemon index.js (if nodemon is installed if not run this command: npm install -g nodemon
)

You will be prompted to enter a URL. After entering the URL, the script will generate a qr_img.png file with the QR code and a URL.txt file with the URL text. The QR image will be present in the directory of your project. Here is the live preview: https://nishanta9.github.io/QR-Proj/

Made by Nishant Acharekar


