# Celebrity Page - Virat Kohli

This project is a simple HTML webpage showcasing information about the legendary Indian cricketer, Virat Kohli. It includes a biography, a gallery, and cricket statistics, with a stylish design featuring background images, colors, and fonts.

## Table of Contents

- [Description](#description)
- [Preview](#preview)
- [Features](#features)
- [Installation](#installation)
  - [Pushing to GitHub](#pushing-to-github)
  - [Deploying on Netlify](#deploying-on-netlify)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

The Celebrity Page provides details about Virat Kohli, including his biography, a gallery with an image, and cricket statistics. The page is designed with a background image, color schemes, and fonts to enhance the visual appeal.

## Preview

![Virat Kohli Celebrity Page](link-to-preview-image)

## Features

- Biography section
- Gallery with an image of Virat Kohli
- Cricket statistics including ODI, Test Match, T20I, and IPL records
- Stylish design with background image, colors, and fonts

## Installation

### Pushing to GitHub

1. *Clone the Repository:*
   - Copy the repository URL from your GitHub repository.
   - Open a terminal or command prompt on your computer.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command, replacing `<repository-url>` with the URL you copied:

     bash
     git clone <repository-url>
     

2. *Copy Your Code:*
   - Copy the HTML code and the associated CSS from your code editor.

3. *Paste Code into Local Repository:*
   - Open the project in your preferred code editor.
   - Replace the existing files or create new files (e.g., `index.html`, `style.css`) and paste the code.

4. *Commit Changes:*
   - In the terminal, navigate to your local repository.
   - Run the following commands:

     bash
     git add .
     git commit -m "Initial commit with HTML and CSS code"
     

5. *Push to GitHub:*
   - Push your code to the GitHub repository:

     bash
     git push origin main
     

### Deploying on Netlify

1. *Create a Netlify Account:*
   - If you don't have a Netlify account, sign up at [Netlify](https://www.netlify.com/).

2. *Install Netlify CLI:*
   - Open your terminal and run:

     bash
     npm install -g netlify-cli
     

3. *Login to Netlify:*
   - Run:

     bash
     netlify login
     

   - Follow the prompts to log in with your Netlify account.

4. *Navigate to Your Project Directory:*
   - In the terminal, go to your project directory.

5. *Deploy to Netlify:*
   - Run the following command:

     bash
     netlify init
     

   - Follow the prompts to link your project to Netlify.

6. *Specify Build Settings:*
   - When prompted for the build command, enter:

     bash
     npm run build
     

   - For the publish directory, enter:

     bash
     build
     

7. *Deploy the Site:*
   - After the initialization, run:

     bash
     netlify deploy
     

   - Follow the prompts, and Netlify will provide you with a live URL for your deployed site.

Now your code is on GitHub, and your site is live on Netlify. Netlify will automatically rebuild and deploy your site whenever you push changes to your GitHub repository.