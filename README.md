# Online Image-to-PDF Converter Image-to-PDF Converter with HTML, CSS, JS, and NodeJS

An online image-to-PDF converter is a website that helps you convert your images to PDFs. This tool is useful because it provides an efficient way to store your images.

## Languages/Libraries/Frameworks Used

- HTML, CSS, and JavaScript
- NodeJS and npm
- <a href="https://www.npmjs.com/package/nodemon">Nodemon</a>: Nodemon is an important Node package that'll help you develop your project faster. It helps in restarting your server when you make changes to the project.
- <a href="https://www.expressjs.com/">Express.js</a> and express-generator: Express.js is the Nodefraemwork you'll use to build the web server. Express-generator is a library that'll help you create the necessary file and folders for Express.js to run efficiently.
- <a href="https://www.npmjs.com/package/express-session">Express-session</a>: This is an Express middleware library that'll help you manage the application sessions.
- <a href="https://pugjs.org/">Jade/Pug</a>: This is a JavaScript templating engine that'll help your render the address of the uploaded images in an HTML file.
- <a href="https://pdfkit.org/">PDFkit</a>: This a JavaScript library that we'll use to convert the images to PDF.
- <a href="https://www.npmjs.com/package/multer">Multer</a>: This ia a Node library that'll handle the file uploads.
- <a href="https://www.npmjs.com/package/sortablejs">Sortablejs</a>: This is a JavaScript drag-and-drop library that will be used in the frontend for rearranging our images before they are converted to PDF.

## Project Setup

1. Clone the Repository to your local machine using ZIP File or using the following git command:
```
git clone https://github.com/aniru-dh21/img2pdf.git
```

2. Install the dependencies using `npm` after changing the present working directory `cd img2pdf`:
```
npm install
```

After downloading this project on your local system (through either forking, git pull, or git clone), navigate to the project's directory (`cd img2pdf`) on your CLI and run this command:
```
set DEBUG=img2pdf:* & npm run devstart
```
