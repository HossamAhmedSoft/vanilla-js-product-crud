# Vanilla JavaScript Product Management System (CRUD)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20ES6-F7DF1E?logo=javascript&logoColor=black)
![Storage](https://img.shields.io/badge/Storage-HTML5%20LocalStorage-success)
![License](https://img.shields.io/badge/License-MIT-green)

A responsive single-page web application implementing a complete **Product Management System (CRUD)** using **pure Vanilla JavaScript**. Features client-side state management, tax/discount calculation, bulk creation, search filtering, and persistent browser storage.

---

## Features

- **Automated Price Aggregation:** Dynamically computes total product cost combining base price, taxes, advertising costs, and discounts in real-time with visual color feedback.
- **Full CRUD Capabilities:**
  - **Create:** Add single products or batch generate up to 100 inventory units via count multiplier.
  - **Read:** Formats records into a dynamically populated HTML data table.
  - **Update:** Pre-fills form fields into edit mode, updating existing records in-place without page reload.
  - **Delete:** Supports single record deletion or clearing the entire database (`Delete All`).
- **Dual Search Modes:** Filter inventory records in real-time by either **Product Title** or **Category** with instant DOM updates.
- **Persistence:** Serializes inventory catalog to browser `localStorage` as JSON.

---

## Architecture & Code Structure

```
vanilla-js-product-crud/
├── index.html     # Semantic data entry layout and table container
├── demo.js        # Core CRUD logic, search algorithms, and localStorage persistence
├── styles.css     # Dark-themed dashboard styling and responsive grid
└── .gitignore     # Excludes node_modules and local editor files
```

---

## Getting Started

No build tools or external package dependencies required. Simply open `index.html` in your web browser, or launch a local server:

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```

Open `http://localhost:8080` to interact with the application.

---

## Author & License

- **Developer:** Hossam Ahmed ([@KabtinBandar](https://github.com/KabtinBandar))
- **License:** MIT
