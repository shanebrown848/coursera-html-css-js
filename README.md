

# Module 5 Coding Assignment

This project is the **Module 5** assignment for the [HTML, CSS, and JavaScript for Web Developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers) course on Coursera. It completes a simple restaurant web application that dynamically displays a random menu category when clicking the **Specials** tile on the home page.

## Table of Contents

- [Overview](#overview)
- [Instructions](#instructions)
- [Key Features](#key-features)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Live Demo](#live-demo)
- [Credits](#credits)

## Overview

In this assignment, we modify an existing restaurant web app:
- Previously, clicking **Specials** always showed a specific category (like "SP").
- Now, each click on **Specials** loads a **random** category from the server, so users see a different category page (e.g., Lunch, Dinner, Sushi, etc.).

## Instructions

1. **Download the Starter Code**  
   The starter files were provided by the course in the `assignment5-solution-starter` folder. 
2. **Copy the Starter Code** into a local folder named `module5-solution`.
3. **Modify `js/script.js`** at the `TODO` steps to:
   - Fetch all categories from the server.
   - Pick a random category.
   - Dynamically inject that random category short name into the home snippet (`home-snippet.html`), replacing `{{randomCategoryShortName}}`.
4. **Test Locally** by opening `index.html` in your web browser.
5. **(Optional) Host on GitHub Pages** for easy sharing and peer review.

## Key Features

- **Dynamic Home Page Snippet**: Pulls the home page HTML (`home-snippet.html`) from the server.
- **Random Specials**: Clicking the **Specials** tile triggers a random category from `categories.json`.
- **AJAX Requests**: Uses `ajax-utils.js` to retrieve data from a Firebase backend.
- **Responsive Design**: Utilizes Bootstrap for a mobile-friendly layout.

## Folder Structure

```
module5-solution/
├── css/
│   ├── bootstrap.css
│   └── ... (other CSS files)
├── images/
│   └── ajax-loader.gif (Loading spinner)
├── js/
│   ├── ajax-utils.js
│   ├── script.js (Main JavaScript with TODO steps)
│   └── ...
├── snippets/
│   ├── home-snippet.html
│   ├── menu-item.html
│   ├── menu-items-title.html
│   └── ...
├── index.html
└── README.md (this file)
```

## Usage

1. **Clone or Download** this repository.
2. **Open `index.html`** in a web browser:
   - Double-click `index.html`, or
   - Use a local server (like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code).
3. **Click “Specials”** on the home page to see a random category page. 
4. **Return to Home** (using the logo in the navbar) and click **Specials** again to test another random category.

## Live Demo

If you have GitHub Pages enabled, you can access the live version at:

```
https://YOUR_GITHUB_USERNAME.github.io/REPOSITORY_NAME/module5-solution/index.html
```

Replace `YOUR_GITHUB_USERNAME` and `REPOSITORY_NAME` with your actual GitHub username and repo name.

## Credits

- **Course**: [HTML, CSS, and JavaScript for Web Developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers) by Johns Hopkins University  
- **Instructor**: Yaakov Chaikin  
- **Bootstrap**: [getbootstrap.com](https://getbootstrap.com)  
- **Firebase**: Hosted data for the menu categories and items  

---

Good luck and happy coding!
