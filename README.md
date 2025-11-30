# ICT-PROJECT-AUTO-WHEEL-WEBSITE
# 25F-0685 || 25F-0529 || 25F-0555
# BS(CS) || 1B || Introduction to Information and Communication Technology
this an ICT project for website Auto Wheel
# 🚗 AUTOWHEEL — Because your Drive matters  
# 🚗 AUTOWHEEL — Premium Car Marketplace

A complete multi-page automotive website built using **HTML, CSS, and JavaScript**.
AUTOWHEEL allows users to **buy cars, sell cars, view services, contact the team, and manage authentication pages (login & signup).**

This project focuses on clean UI, responsive layouts, and beginner-friendly JavaScript functionality such as navigation toggles, form handling, animations, and dynamic footer years.

---

## 📁 Project Structure

```
AUTOWHEEL/
│
├── index.html
├── about.html
├── services.html
├── buy-cars.html
├── sell-cars.html
├── servicing.html
├── contactus.html
├── login.html
├── signup.html
│
├── css/
│   ├── index.css
│   ├── about.css
│   ├── services.css
│   ├── buy-cars.css
│   ├── sell-cars.css
│   ├── servicing.css
│   ├── contact.css
│   ├── login.css
│   └── signup.css
│
├── js/
│   ├── index.js
│   ├── about.js
│   ├── services.js
│   ├── buy-car.js
│   ├── sell.js
│   ├── servicing-detail.js
│   ├── common.js / contact.js
│   ├── login.js
│   └── signup.js
│
└── assets/
    └── logo.webp
```

---

# 🌐 Pages Overview

## 1️⃣ Home Page — `index.html`

* Hero section with image.
* Navbar with hamburger.
* Service cards.
* Footer with auto year.
* JS:

  * `toggleMenu()`
  * Footer year dynamic update.

---

## 2️⃣ About Page — `about.html`

* Gradient hero section.
* Owners section (3 owners).
* “Why Choose Us” features.
* Mobile navbar.
* JS:

  * Navbar toggle
  * Footer year update.

---

## 3️⃣ Services Page — `services.html`

* Large hero section.
* Grid layout of service cards.
* **Each card redirects using data-target attributes**.
* Fade-in animations on scroll.
* Clean rounded footer design.

---

## 4️⃣ Buy Cars Page — `buy-cars.html`

* Four car listings:

  * Image
  * Title
  * Price
  * Description
* Scroll reveal animations.
* Navbar toggle.
* Footer year update.

---

## 5️⃣ Sell Cars Page — `sell-cars.html`

* Complete car listing form:

  * Model
  * Year
  * Mileage
  * Price
  * Upload images
* JavaScript:

  * Shows alert on submit.
  * Resets form.
  * Navigation toggle.

---

## 6️⃣ Servicing Page — `servicing.html`

* Three service center cards.
* Each with:

  * Image
  * Service name
  * Description
  * City/location
* Footer + navbar similar to other pages.

---

## 7️⃣ Contact Page — `contactus.html`

* Hero section.
* Contact form (Name, Email, Message).
* Form uses `onsubmit="return false;"`.
* Footer with dynamic copyright.

---

## 8️⃣ Login Page — `login.html`

* Entire page rendered via JS.
* Includes:

  * Email
  * Password
  * Login button
  * Redirect to signup
* JS handles:

  * localStorage DB login checking
  * Redirects to profile page on success

---

## 9️⃣ Signup Page — `signup.html`

* JS renders signup form.
* Saves new user in localStorage.
* After creating account:

  * Saves auth session
  * Redirects to profile page

---

# 🎨 CSS System

Each page has a separate CSS file.

### Key features:

* Palette:

  * `#3674B5`
  * `#578FCA`
  * `#A1E3F9`
  * `#D1F8EF`
* Responsive navbar + hamburger.
* Card UI design across pages.
* Glass card effects (About).
* Smooth animations.
* Modern shadows and rounded edges.

---

# 🧠 JavaScript Overview

### Common Behaviors

* `toggleMenu()` for responsive navbar.
* Auto footer year using:

  ```
  new Date().getFullYear()
  ```
* Scroll animations (Buy Cars & Services).
* Form alerts (Sell Car).
* LocalStorage-based login/signup system.

### Page-Specific JS

| Page        | Functionality                     |
| ----------- | --------------------------------- |
| index.js    | Navbar + Year                     |
| about.js    | Navbar + Year                     |
| services.js | Card redirects + fade-in          |
| buy-car.js  | Scroll animation + nav toggle     |
| sell.js     | Form submit alert + toggle        |
| login.js    | JS-rendered login form + DB login |
| signup.js   | Save user + auto login            |


Open:

```
index.html

Website will appear at:

```
https://hashimnagi.github.io/ICT-PROJECT-AUTO-WHEEL-WEBSITE/
```

---

# 📝 Features Summary

* Multi-page responsive website
* Dynamic JS interactions
* Scroll animations
* LocalStorage-based login system
* Clean automotive theme
* Complete Buy/Sell system 
* Modern UI with custom color palette

---


Developed by **AUTOWHEEL Team(25F-0685 || 25F-0529 || 25F-0555)**
(Owner names inside about.html)

---

