# 🖼️ Pinterest-Inspired Gallery Web Page

A clean, responsive image gallery inspired by **Pinterest**, built using **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**. This project showcases a masonry grid layout with live search functionality and a modern UI.

---

## 🚀 Features

- 🔍 **Live Search** – Instantly filter images based on user input.
- 🧱 **Masonry Grid Layout** – Dynamic card arrangement using Tailwind CSS.
- 🎨 **Modern UI** – Clean design with hover effects and smooth interactions.
- ⚡ **Fast & Lightweight** – No frameworks, just HTML + CSS + JS.
- 📱 **Responsive Design** – Works beautifully across all screen sizes.

---

## 🛠️ Tech Stack

- `HTML5`
- `CSS3` (Tailwind CDN + Custom)
- `JavaScript (Vanilla)`
- `Remix Icon` CDN

---

## 📂 Project Structure

```plaintext
📁 Project Folder
├── 📄 index.html       # Main HTML file
├── 🎨 style.css        # Custom styling & Tailwind utilities
└── ⚙️ script.js        # Dynamic card rendering & search logic
```

---

## 📸 How It Works

```js
// Sample card data
let arr = [
  {
    name: "Shinchan",
    image:
      "https://w0.peakpx.com/wallpaper/1004/1005/HD-wallpaper-shinchan.jpg",
  },
  ...
];

// Renders cards into the container
function showTheCards() {
  let clutter = "";
  arr.forEach((obj) => {
    clutter += `<div class="box">...</div>`;
  });
  document.querySelector(".container").innerHTML = clutter;
}

// Filters cards based on search input
function handleSearchFunctionality() {
  input.addEventListener("input", function () {
    let filteredArr = arr.filter((obj) =>
      obj.name.toLowerCase().startsWith(input.value.toLowerCase())
    );
    ...
  });
}
```

---

## 🧪 Getting Started

1. Clone or download the repository.
2. Open `index.html` in any browser.
3. Explore the masonry layout and try searching for images!

---

## 🔮 Future Enhancements

- 🖼️ Modal Image Preview
- 🏷️ Category Filters
- 🌙 Dark Mode Toggle
- ☁️ Backend Integration for dynamic image loading

---

## 🙋‍♂️ Author

**Krish Balana**  
🎓 Student @ Chandigarh University  
🌐 [LinkedIn](https://www.linkedin.com/in/krishbalana) • 🐙 [GitHub](https://github.com/krishbalana)

---

> Built with ❤️ using Tailwind CSS + JavaScript
