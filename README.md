# 🔐 Authentication Form

This is a React-based authentication form project built using [Vite](https://vitejs.dev/) for fast development and [Tailwind CSS](https://tailwindcss.com/) for utility-first styling.

---

## 📁 Project Setup

Follow the steps below to set up and run the project locally.

---

## 🚀 Getting Started

### 1. Create the Project

Use the following commands to create a new React project using Vite:

npm create vite@latest authentication-form --template react
cd authentication-form

### 2. Install Dependencies

Install project and Tailwind CSS dependencies:

npm install
npm install -D tailwindcss @tailwindcss/vite
npx tailwindcss init -p

### 3. Configure Tailwind
Update your tailwind.config.js like this:

/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
In src/index.css, add the Tailwind directives:

css

@tailwind base;
@tailwind components;
@tailwind utilities;

### 4. Run the Development Server

npm run dev
Visit http://localhost:5173 in your browser.

🛠 Technologies Used
React

Vite

Tailwind CSS

📂 Folder Structure

authentication-form/
├── public/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── tailwind.config.js
└── postcss.config.js


🙋‍♂️ Author
Made with ❤️ by Hari

### ✅ Tip:
Replace `your-username` with your actual GitHub username before pushing.

Let me know if you also want:
- GitHub Pages or Vercel deployment instructions
- Form validation logic
- Firebase or other authentication integration guide