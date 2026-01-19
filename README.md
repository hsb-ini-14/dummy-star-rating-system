# Star Rating Component

An interactive and responsive **Star Rating System Component** built with **React, Vite, and Tailwind CSS**.
This project demonstrates half-star selection, smooth UI feedback, and clean component-based design.

🔗 **Live Demo:** [https://hsb-ini-14.github.io/dummy-star-rating-system/](https://hsb-ini-14.github.io/dummy-star-rating-system/)

---

## ✨ Features

* ⭐ 5-star rating system
* ➗ Supports half-star and full-star selection
* 🖱 Click left/right side of a star for half/full rating
* 📱 Fully responsive layout
* 🎨 Styled with Tailwind CSS
* ⚡ Built using Vite for fast development

---

## 🛠️ Tech Stack

* **React** – UI components & state management
* **Vite** – Fast build tool & dev server
* **Tailwind CSS** – Utility-first styling
* **Boxicons** – Icon set for stars
* **GitHub Pages** – Deployment

---

## 📁 Project Structure

```text
dummy-star-rating-system/
├── src/
│   ├── components/
│   │   ├── Rating.jsx
│   │   └── Star.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/hsb-ini-14/dummy-star-rating-system.git
cd dummy-star-rating-system
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start the development server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 🌍 Deployment to GitHub Pages

This project is deployed using **gh-pages**.

### Steps used:

1. Install gh-pages

```bash
npm install --save-dev gh-pages
```

2. Set base path in `vite.config.js`

```js
export default defineConfig({
  base: "/dummy-star-rating-system/",
});
```

3. Add scripts to `package.json`

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

4. Deploy

```bash
npm run deploy
```

---

## 🧩 How It Works

* The rating value is stored using React `useState`
* Five `Star` components are rendered dynamically
* Each star has two invisible click zones:

  * Left half → half-star rating
  * Right half → full-star rating
* Star icons change based on the current rating value
* Tailwind utility classes handle layout and responsiveness

---

## 📸 Preview

> Add a screenshot or GIF of the star rating component here for better presentation.

---

## 🙌 Acknowledgements

* Icons by [Boxicons](https://boxicons.com/)
* Styling powered by [Tailwind CSS](https://tailwindcss.com/)
* Build tool by [Vite](https://vitejs.dev/)

---

## 👤 Author

**Harsh Singh Bhaduria**

* GitHub: [https://github.com/hsb-ini-14](https://github.com/hsb-ini-14)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub — it really helps! 😊
