# Resizing Image Api  
  - This is an ImageApi resizing project, that takes a picture's name, length and width, and resizes it
  - img file, contains the images to be resized
  - thumbs file is the output file after resizing an image
  - Used Caching in case the picture was already Resized
  - Unit testing was made using Jasmine
  
## Important notes  
  - This project was developed on Ubuntu
  - Cross-platform Pathing wasn't applied, so It will raise FileNotFound error if it's being run on Windows
   
## How to use the Api
 - URL path : http://localhost:5000/api
 - Parameters

   | Parameter     | Query string  |
   | ------------- | ------------- |
   |  Image        |     filename  |
   |  Length       |     len       |
   |  Width        |     wid       |
 
 ### Sample URL  : http://localhost:5000/api?filename=img2&len=600&wid=600
 
<h2>Built With </h2>

-   [Node.js](https://nodejs.org/en/)
-   [Express](https://expressjs.com/)
-   [TypeScript](https://www.npmjs.com/package/typescript)
-   [Jasmine](https://jasmine.github.io/)
-   [Sharp](https://www.npmjs.com/package/sharp)
