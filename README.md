Great work Aman 👍 This is a **complete professional IT company website layout** using Bootstrap 5. I’ll explain the whole code section by section in a simple way so you clearly understand the structure and logic.

---

# 🔹 1. Basic HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
```

* `<!DOCTYPE html>` → Tells browser this is HTML5.
* `lang="en"` → Website language is English (good for SEO).

---

## 🔹 Head Section

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

* `charset="UTF-8"` → Supports all characters.
* `viewport` → Makes site responsive on mobile.

---

## 🔹 Bootstrap & Icons

```html
<link href="bootstrap-icons.css">
<link href="bootstrap.min.css">
```

* Bootstrap CSS → Provides ready-made classes like `container`, `row`, `col-md-4`, `navbar`, etc.
* Bootstrap Icons → For icons like phone, code, camera.

---

## 🔹 Custom CSS

```html
<link rel="stylesheet" href="css/style.css">
```

This is your custom styling file.
Bootstrap gives base design, your CSS customizes it.

---

# 🔹 2. Navbar Section

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
```

### Important Classes:

* `navbar` → Bootstrap navbar
* `navbar-expand-lg` → Expands on large screens
* `navbar-dark bg-dark` → Dark theme
* `fixed-top` → Navbar stays fixed at top

---

### Inside Navbar:

```html
<a class="navbar-brand">Syntax Studio</a>
```

Company name / logo area.

```html
<button class="navbar-toggler">
```

This is the hamburger menu for mobile view.

```html
<div class="collapse navbar-collapse">
```

This collapses the menu on small screens.

```html
<ul class="navbar-nav ms-auto">
```

* `ms-auto` → Push menu to right side.

Each link:

```html
<li class="nav-item">
<a class="nav-link" href="#home">
```

This scrolls to sections using IDs like:

```html
<section id="home">
```

---

# 🔹 3. Hero Section

```html
<section id="home" class="hero-section d-flex align-items-center">
```

* `d-flex` → Flexbox
* `align-items-center` → Vertical center alignment

Inside it:

```html
<div class="hero-card">
```

This likely has styling in `style.css`.

Buttons:

```html
btn btn-primary
btn btn-outline-primary
```

Bootstrap button styles.

---

# 🔹 4. Services Section

```html
<section id="service" class="section">
```

### Layout:

```html
<div class="row g-4">
<div class="col-md-4">
```

* `row` → Bootstrap grid row
* `col-md-4` → 3 columns per row (12/4 = 3)
* `g-4` → Gap spacing

---

### Service Card Structure

```html
<div class="service-card">
  <div class="service-icon">
    <i class="bi bi-phone"></i>
  </div>
```

* `bi bi-phone` → Bootstrap icon
* Each service card is structured same way.

You created 6 service cards using grid system.

---

# 🔹 5. Solutions Section

```html
<section id="solution" class="section bg-light">
```

* `bg-light` → Light background color

Each card:

```html
<div class="solution-card">
<img src="images/solution1.jpg">
```

So this is image + content inside card.

You also used:

```html
<span class="brand-highlight">
```

This is custom styling class for highlighted text.

---

# 🔹 6. About Us Section

```html
<section id="aboutus">
```

Layout:

```html
<div class="row align-items-center g-5">
```

Two columns:

* Left → Content
* Right → Image

```html
<div class="col-lg-6">
```

50% width on large screens.

---

### Why Choose Us Items

Each feature:

```html
<div class="why-item">
  <div class="why-icon">
    <i class="bi bi-people"></i>
```

Icon + text side by side.

---

# 🔹 7. Contact Section

```html
<section id="contact" class="contact-section">
```

Split into 2 parts:

```html
col-lg-7 → Contact Form
col-lg-5 → Contact Info
```

---

## Contact Form

You used:

```html
<form>
<div class="row g-3">
```

Each input:

```html
<input class="form-control">
<select class="form-select">
<textarea class="form-control">
```

Bootstrap form classes:

* `form-control`
* `form-select`
* `form-check`

Checkbox:

```html
<input class="form-check-input">
```

Submit button:

```html
btn btn-primary w-100
```

* `w-100` → Full width

---

## Contact Info Card

Each info item:

```html
<div class="info-item">
<i class="bi bi-telephone">
```

You added:

* Phone
* Email
* Business Hours
* Social Icons

Good professional structure 👍

And I noticed you used your business format number:
**+91 87809 82731** ✔ (nice consistency Aman)

---

# 🔹 8. Footer Section

```html
<footer class="site-footer">
```

You created 4 columns:

```html
<footer-grid>
```

### 1️⃣ Brand

Company info + social icons

### 2️⃣ Quick Links

Navigation links

### 3️⃣ Services

List of services

### 4️⃣ Newsletter

Description section

---

### Footer Bottom

```html
<hr />
<div class="footer-bottom">
```

Contains:

* Copyright
* Privacy Policy
* Terms
* Cookie Policy

---

# 🔹 9. JavaScript

```html
<script src="bootstrap.bundle.min.js"></script>
```

Required for:

* Navbar collapse
* Dropdown
* Interactive components

```html
<script src="js/script.js"></script>
```


---

# 🔥 Overall Architecture (Professional Level)

Your structure follows this order:

1. Navbar
2. Hero
3. Services
4. Solutions
5. About
6. Contact
7. Footer

This is **standard corporate IT website structure** 👌

---

