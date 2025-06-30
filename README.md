# interactive-sales-dashboard
An AI-powered sales performance dashboard using HTML, JavaScript, Plotly.js, and JSON file upload. Built with help from Generative AI (ChatGPT).
# 🧠 Interactive Sales Dashboard (AI-Powered)

This project is a fully interactive and visually rich **Sales Performance Dashboard** built using **HTML**, **JavaScript**, and **Plotly.js**.  
It supports uploading JSON data and was developed with the assistance of **Generative AI (ChatGPT)** for coding, UI design, and feature planning.

---

## 🌟 Features

- 📁 Upload JSON sales transaction data
- 📅 Sales Over Time (line chart)
- 🛍️ Sales by Product Category (bar chart)
- 👨‍🦰👩‍🦰 Sales by Gender (pie chart)
- 👥 Age vs Spend (scatter plot)
- 💰 Average Order Value (KPI card)
- 🎨 Modern glassmorphism-style UI

---

## 📂 How to Use

1. **Clone or download** this repository.
2. Open the `sales_dashboard.html` file in any modern browser.
3. Click the **file upload** button and upload a `.json` file with sales transaction records in this format:

```json
[
  {
    "Transaction ID": 1,
    "Date": "2023-11-24",
    "Customer ID": "CUST001",
    "Gender": "Male",
    "Age": 34,
    "Product Category": "Beauty",
    "Quantity": 3,
    "Price per Unit": 50,
    "Total Amount": 150
  }
]
