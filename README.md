# ☕ Klassy Cafe Website

Klassy Cafe is a modern and responsive restaurant website built using **HTML, CSS, and Vanilla JavaScript**.  
This project focuses on clean UI design, responsive layout, and interactive user experience without using any frontend framework.

---

## 🚀 Live Preview

Open `index.html` in your browser to view the project.

---

## 📌 Features

- Responsive navigation (Desktop & Mobile)
- Mobile hamburger menu
- Hero image slider (auto & manual)
- Food menu slider
- Meal offers tabs (Breakfast / Lunch / Dinner)
- Chefs section with social icons
- Reservation & contact form
- Clean and modern UI design

---

## 🛠 Technologies Used

- **HTML5** – Page structure
- **CSS3** – Styling and responsive layout
- **JavaScript (Vanilla JS)** – Interactivity and logic
- **Font Awesome** – Icons

---

## 📂 Project Structure

```

Klassy-Cafe/
│
├── index.html        # Main HTML file
├── file.css          # Main CSS file
├── images/           # Images and icons
└── README.md         # Project documentation

````

---

## 🧠 How It Works

### Navigation & Hamburger Menu
- Desktop uses a normal navigation bar
- Mobile uses a hamburger menu
- JavaScript toggles menu visibility using `data-visible`

---

### Hero Slider
- Images are placed inside a flex container
- JavaScript moves slides using `translateX`
- Auto slides every 5 seconds
- Manual navigation using left and right arrows

---

### Meal Offers Section
- Tabs: Breakfast, Lunch, Dinner
- Each meal item has a `data-meal` attribute
- JavaScript shows only selected meal items

Example:
```html
<div class="meal-box" data-meal="breakfast"></div>
````

CSS:

```css
.meal-box { display: none; }
.meal-box.show { display: flex; }
```

---

## 📱 Responsive Design

* Mobile-first approach
* Media queries used for small screens
* Layout adjusts automatically for different devices

---

## ▶️ How To Run

1. Download or clone the project
2. Open `index.html`
3. View in any modern browser (Chrome recommended)

---