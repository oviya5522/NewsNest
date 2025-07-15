# 📰 NewsNest - React News App

**NewsNest** is a category-based news application built with **React**. It fetches and displays top headlines using the [NewsAPI.org](https://newsapi.org) service and features a clean, responsive UI built with **Bootstrap**.

---

## 🚀 Features

- 🗂️ Browse news by categories:
  - Technology
  - Business
  - Health
  - Science
  - Sports
  - Entertainment
- ⚛️ Built with React (functional components and hooks)
- 🎨 UI styled using **Bootstrap 5** (Navbar, responsive layout)
- 🌐 Fetches real-time data using Fetch API
- 📱 Fully responsive design

---

## 🚧 Deployment Note

This project uses the free tier of NewsAPI, which **does not support frontend requests** from deployed sites like Netlify.  
As a result, the live version displays a `426 Upgrade Required` error.

✅ **However, it works perfectly on local development.**

---

## 🎯 Purpose of the Project

This project was built as part of a **web development internship** to demonstrate:

1. React.js fundamentals (functional components and hooks)
2. API integration and data fetching using Fetch API
3. UI styling with Bootstrap for responsive design
4. Handling real-world deployment/API limitations
5. Familiarity with deployment platforms like Netlify

---

## 🛠️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/oviya5522/newsnest.git

---
2. Navigate to the project directory:
    cd newsnest
---
3. Create a .env file in the root of your project and add your NewsAPI key:
    ```env
      VITE_API_KEY=your_newsapi_key_here
---
4. Install dependencies:
    npm install
---
5. Start the development server:
    npm run dev
---
6. Open your browser and go to:
    ```http://localhost:5173 (or the port Vite assigns)```
