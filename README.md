# 📦 Product Inventory & Analytics Dashboard

An interactive, browser-based inventory management mini-project built using **HTML, CSS, and JavaScript**. This project demonstrates core JavaScript concepts through product management, price validation, inventory calculations, and financial analytics.

## 🌐 Live Demo

**Live Website:** [View Live Project](https://inventory-dashboard0.onrender.com)

> Replace `YOUR_LIVE_WEBSITE_URL_HERE` with your deployed website URL after publishing the project.

## 📌 Project Overview

The Product Inventory & Analytics Dashboard allows users to add products, validate product information, categorize items based on their prices, and calculate the total inventory value.

It also generates a formatted inventory report and demonstrates JavaScript array methods and functions through an interactive interface.

## ✨ Features

- **Interactive Product Input:** Add a product name and price using browser prompts.
- **Demo Mode:** Run the application instantly with sample inventory data.
- **Input Validation:** Validate product names and prices, with up to three attempts.
- **Product Categorization:** Automatically classify products as Budget, Standard, or Premium.
- **Inventory Management:** Detect duplicate product names.
- **Financial Analytics:** Calculate the total value of inventory.
- **Affordable Product Filtering:** Identify products priced below $200.
- **Formatted Reports:** Generate uppercase product reports with prices.
- **Tax and Discount Calculation:** Calculate adjusted totals using tax and discount values.
- **Console-Style Output:** View program results directly on the webpage and in the browser console.
- **Clear Output:** Reset the displayed results with one click.

## 🛠️ Technologies Used

- **HTML5** — Structure and layout
- **CSS3** — Styling and responsive presentation
- **JavaScript (ES6+)** — Application logic and interactivity
- **Git & GitHub** — Version control and project hosting
- **GitHub Pages / Render** — Static website deployment

## 📂 Project Structure

```text
inventory-dashboard/
├── index.html       # Main webpage
├── style.css        # Styling and layout
├── script.js        # Inventory logic and analytics
├── render.yaml      # Render deployment configuration
├── README.md        # Project documentation
└── .gitignore       # Git ignored files
```

## 🧠 JavaScript Concepts Demonstrated

This project applies the following fundamental JavaScript concepts:

- Variables, arrays, objects, and data initialization
- Conditional statements: `if`, `else`, and `switch`
- Loops: `for`, `for...of`, and `forEach()`
- Loop control statements: `break` and `continue`
- Regular functions and arrow functions
- Function parameters, default parameters, and scope
- Array methods: `forEach()`, `filter()`, and `map()`
- Type conversion and input validation
- Template literals and string formatting
- DOM manipulation and event listeners
- Basic financial calculations

## 🚀 How to Run Locally

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:

   ```bash
   cd inventory-dashboard
   ```

3. Open `index.html` in your browser.

Alternatively, use a local development server:

```bash
npx serve .
```

## 🌍 How to Deploy

### Option 1: GitHub Pages

1. Push the project files to a GitHub repository.
2. Open the repository on GitHub.
3. Navigate to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Click **Save** and wait for deployment.

Your website URL will generally follow this format:

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`

### Option 2: Render

1. Push the project files to GitHub.
2. Sign in to [Render](https://render.com/).
3. Select **New → Static Site**.
4. Connect your GitHub repository.
5. Set the publish directory to `.` and leave the build command empty.
6. Create the static site and copy the live URL provided by Render.

## 🧪 Sample Output

Using the demo option with a Monitor priced at $150:

```text
--- Initializing Inventory System ---
[Prompt executed: User adds "Monitor" at "$150"]

--- Processing Inventory Roster (forEach) ---
* Item: Laptop ($800) -> Category: Premium
* Item: Mouse ($25) -> Category: Budget
* Item: Monitor ($150) -> Category: Standard

--- Financial Analytics ---
Total Inventory Value: $975
Filtered Affordable Items (Under $200): ["Mouse", "Monitor"]
Formatted Report List: ["LAPTOP: $800", "MOUSE: $25", "MONITOR: $150"]
```

The application also displays a bonus calculation that applies a 10% tax and a $50 discount.

## 🎯 Project Objective

The primary objective of this project is to strengthen practical JavaScript skills by combining programming fundamentals, data processing, validation, and DOM interaction into a working mini-project.

## 🔮 Future Improvements

- Add, edit, and delete products directly in the dashboard.
- Display inventory in a structured table.
- Add search, sorting, and category filters.
- Store inventory data using Local Storage.
- Include charts for inventory and financial analytics.
- Add export functionality for inventory reports.

## 👨‍💻 Author

**VEERA PURNIMA VENKATA**

GitHub:https://github.com/25A31A05HJ

---

⭐ If you find this project useful, consider giving the repository a star!
