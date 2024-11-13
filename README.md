# Wholesome Bites Bakery Website Documentation

## Overview
Welcome to the Wholesome Bites Bakery website! This document provides essential information on how to navigate, manage, and update your website.

### Project Details
- **Client**: Wholesome Bites Bakery
- **Website URL**: [Insert Live Link]
- **Technologies Used**: HTML, CSS

## Table of Contents
1. [Accessing the Website](#accessing-the-website)
2. [Website Structure](#website-structure)
3. [Updating Content](#updating-content)
4. [Images](#images)
5. [Troubleshooting](#troubleshooting)
6. [FAQs](#faqs)
7. [Contact Information](#contact-information)

## Accessing the Website
To access the Wholesome Bites Bakery website, use the following link: https://rachelmorgan22.github.io/Wholesome-Bites-Bakery/. You can view it in any modern web browser (Chrome, Firefox, Safari).

## Website Structure
The website consists of the following pages:
- **Home**: The main landing page featuring bakery highlights.
- **About**: Information about the bakery’s history and mission.
- **Menu**: A detailed list of bakery items.
- **Contact**: Contact information and a form for inquiries.

### Folder Structure
/wholesome-bites-bakery ├── index.html ├── about/ │ └── index.html ├── menu/ │ └── index.html ├── contact/ │ └── index.html ├── css/ │ └── styles.css └── images/ └── [image files]


## Updating Content
To update text or images on any page, follow these steps:

1. **Open the HTML File**: Use a code editor like Visual Studio Code to open the relevant HTML file (e.g., `index.html` for the homepage).
2. **Edit Text**: Locate the text you want to change and edit it directly within the `<body>` section of the HTML file.
3. **Update Images**: To change an image, replace the file in the `/images` folder with the new image (make sure it has the same name) or update the `<img>` tag in the HTML to point to a new image.

## Images
All images are stored in the `/images` folder. Make sure to optimize images for web use to improve loading speed.

### Adding New Images
1. Place the new image file in the `/images` folder.
2. Update the HTML file to include the new image using the following format:
   ```html
   <img src="images/your-image-file.jpg" alt="Description of the image">
   
Troubleshooting
404 Errors: If you encounter a 404 error, check the links in your navigation to ensure they point to the correct pages.
Images Not Displaying: Verify that the image file names match those referenced in the HTML code and that they are located in the /images folder.
FAQs
Q: How do I change the background color of the website?
A: Open the styles.css file and look for the body selector. Modify the background-color property to your desired color.

Q: Can I add a new page?
A: Yes! Create a new HTML file in the root directory or relevant folder, and link to it from the navigation menu in the existing HTML files.

Contact Information
If you have any questions or need further assistance, please contact me:

Name: Rachel Morgan 
Email: rachelmorgan134@hotmail.com
