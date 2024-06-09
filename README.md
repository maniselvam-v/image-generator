Random Image Generator
This project generates and displays random images using the Lorem Picsum image service. It creates a simple HTML page with a specified number of images, each with random dimensions.

Table of Contents
Overview
Features
Technologies Used
Setup
Usage
Customization
Contributing
License
Overview
The Random Image Generator project demonstrates how to use the Lorem Picsum image service to display random images with varying dimensions on a web page. The project uses HTML, CSS, and JavaScript to dynamically create and append images to the DOM.

Features
Generates a specified number of random images
Uses Lorem Picsum to fetch random images
Randomizes image dimensions for variety
Simple and easy to customize
Technologies Used
HTML
CSS
JavaScript
Lorem Picsum (for random images)
Setup
To set up the project locally, follow these steps:

Clone the repository or download the source code:

bash
Copy code
git clone https://github.com/your-username/random-image-generator.git
Navigate to the project directory:

bash
Copy code
cd random-image-generator
Open the index.html file in your preferred web browser.

Usage
Simply open the index.html file in a web browser to see the random images generated and displayed. The images will have random dimensions and will change every time the page is refreshed.

Customization
To customize the number of images or the range of dimensions, modify the JavaScript code in the index.html file:

Number of Images: Change the value of the rows variable to control the number of images displayed. The total number of images will be rows * 3.
Image Dimensions: Adjust the getRandomNumber function to change the range of dimensions for the images.
Example
To display 20 images and increase the range of dimensions:

javascript
Copy code
const rows = 7; // This will create 21 images (rows * 3)

const getRandomNumber = () => Math.floor(Math.random() * 200) + 300; // Range: 300 to 499
Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more information.
