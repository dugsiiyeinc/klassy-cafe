```md
#  Klassy Cafe Website

Klassy Cafe is a modern and responsive restaurant website built using **HTML and CSS**.  
This project focuses on clean UI design, responsive layout, and interactive user experience without using any frontend framework.

---

## Repository

GitHub: https://github.com/dugsiiyeinc/klassy-cafe

---

##  Features

- Responsive navigation (Desktop & Mobile)
- Mobile hamburger menu
- Hero image slider (auto & manual)
- Food menu slider
- Meal offers tabs (Breakfast / Lunch / Dinner)
- Chefs section with social icons
- Reservation & contact form
- Clean and modern UI design

---

## Technologies Used

- **HTML** – Page structure
- **CSS** – Styling and responsive layout
- **JavaScript** – Interactivity and logic
- **Font Awesome** – Icons

---

##  Project Structure

Each section of the website lives in its **own folder**:

```

klassy-cafe/
│
├── about/
│   └── about.html
│   └── about.css
│
├── chefs/
│   └── chefs.html
│   └── chefs.css
│
├── contact-us/
│   └── contact.html
│   └── contact.css
│
├── footer/
│   └── footer.html
|   └── footer.css
│
├── home/
│   └── home.html
│   └── home.css
│
├── meal-offers/
│   └── meal.html
│   └── meal.css
│
├── menu/
│   ├── menu.html
│   └── menu.css
│
├── images/
│   └── (all project images)
│
├── index.html
├── style.css
├── README.md

````

---

##  How It Works

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

## Responsive Design

* Mobile-first approach
* Media queries used for small screens
* Layout adjusts automatically for different devices

---

## How To Run

1. Download or clone the project
2. Open `index.html`
3. View in any modern browser (Chrome recommended)

---

## 👥 Contributors

* **@cabdraxmaanibnufaisal-alt**
* **@hamda-Mohan**

---