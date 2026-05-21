# Bootstrap
## Introduction to bootstrap
# 12. Introduction to Bootstrap

## 12.1 What is Bootstrap

Bootstrap is a free and open-source front-end framework used for designing responsive and mobile-friendly websites quickly.

It contains:

* Ready-made CSS classes
* JavaScript components
* Responsive grid system
* Pre-designed buttons, forms, navigation bars, etc.

Bootstrap helps developers create attractive websites without writing large amounts of CSS from scratch.

### Simple Definition

> Bootstrap is a framework that makes web development faster and easier.

---

## 12.2 Features of Bootstrap

### 1. Responsive Design

Bootstrap automatically adjusts website layout according to screen size:

* Mobile
* Tablet
* Laptop
* Desktop

### 2. Grid System

Bootstrap provides a 12-column grid system for creating layouts easily.

### 3. Predefined CSS Classes

It includes ready-made classes for:

* Buttons
* Forms
* Tables
* Alerts
* Cards
* Navigation bars

### 4. JavaScript Components

Bootstrap provides interactive components like:

* Modals
* Carousel
* Dropdown menus
* Tooltips

### 5. Easy Customization

Developers can customize colors, fonts, spacing, and layouts.

### 6. Cross-Browser Compatibility

Bootstrap works properly on:

* Chrome
* Firefox
* Edge
* Safari

### 7. Faster Development

Using ready-made components saves development time.

---

## 12.3 Advantages of Bootstrap

| Advantage          | Description                      |
| ------------------ | -------------------------------- |
| Easy to Learn      | Simple classes and documentation |
| Saves Time         | Ready-made design components     |
| Responsive         | Works on all devices             |
| Consistent Design  | Uniform appearance across pages  |
| Mobile Friendly    | Optimized for smartphones        |
| Browser Compatible | Supports major browsers          |
| Open Source        | Free to use                      |

---

## 12.4 Downloading Bootstrap

There are two main ways to use Bootstrap.

## Method 1: Using CDN (Recommended)

CDN means Content Delivery Network.

You can directly link Bootstrap files from the internet without downloading them.

### Bootstrap CSS CDN

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
```

### Bootstrap JavaScript CDN

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

## Method 2: Download Bootstrap Files

Steps:

1. Go to the official Bootstrap website.
2. Download Bootstrap files.
3. Extract the ZIP file.
4. Use CSS and JS files in your project.

### Folder Structure

```text
bootstrap/
│
├── css/
│   └── bootstrap.min.css
│
├── js/
│   └── bootstrap.bundle.min.js
```

---

## 12.5 Linking Bootstrap

After downloading Bootstrap, link the CSS and JS files inside the HTML file.

### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>Bootstrap Example</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
</head>

<body>

    <h1 class="text-primary">Hello Bootstrap</h1>

    <!-- Bootstrap JS -->
    <script src="js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

---

# Important Bootstrap Classes

| Class         | Purpose                      |
| ------------- | ---------------------------- |
| `container`   | Creates responsive container |
| `row`         | Creates a row                |
| `col`         | Creates columns              |
| `btn`         | Creates button               |
| `btn-primary` | Blue button                  |
| `text-center` | Centers text                 |
| `bg-dark`     | Dark background              |
| `text-white`  | White text                   |

---

# Simple Bootstrap Example

```html
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<div class="container mt-5">

    <h1 class="text-primary">Welcome</h1>

    <button class="btn btn-success">
        Click Me
    </button>

</div>

</body>
</html>
```

---

# Quick Revision Notes

## Bootstrap

* Front-end framework
* Used for responsive web design
* Provides CSS and JS components

## Features

* Responsive layout
* Grid system
* Ready-made components
* Cross-browser support

## Advantages

* Faster development
* Easy customization
* Mobile-friendly

## Ways to Use

1. CDN
2. Download files

## Linking

* Use `<link>` for CSS
* Use `<script>` for JavaScript
