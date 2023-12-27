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

3. Run the command to access the application server:
```
set DEBUG=img2pdf:* & npm run devstart
```

4. Once you get a success message, it means the server is already running.

5. Open your web browser and type `http://localhost:3000/` in the search bar.

## Workflow of the Project

1. Firstly, define a route that returns the `index` HTML file when the root URL `/` is reached.

2. Within `index` HTML file, create a form that accepts only image file (png, jpg) and then send it to the server at a defined route.
