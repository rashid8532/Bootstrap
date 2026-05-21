## Components
# 15. Bootstrap Components

Bootstrap provides many ready-made components that help create attractive and responsive websites quickly.

---

# 15.1 Bootstrap Typography

Typography means styling and formatting text.

Bootstrap provides classes for:

* Headings
* Text colors
* Alignment
* Font weight
* Display headings

---

# Headings

Bootstrap supports normal HTML headings:

```html id="vcb1p7"
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

---

# Display Headings

Large stylish headings:

```html id="n5m2t1"
<h1 class="display-1">Display 1</h1>
<h1 class="display-4">Display 4</h1>
```

---

# Text Color Classes

| Class          | Color  |
| -------------- | ------ |
| `text-primary` | Blue   |
| `text-success` | Green  |
| `text-danger`  | Red    |
| `text-warning` | Yellow |

---

# Text Alignment

```html id="t6r9n2"
<p class="text-center">Center Text</p>

<p class="text-end">Right Text</p>
```

---

# Font Weight

```html id="y8f3v4"
<p class="fw-bold">Bold Text</p>

<p class="fw-light">Light Text</p>
```

---

# Example

```html id="u2z8d7"
<div class="container">

    <h1 class="display-3 text-primary">
        Bootstrap Typography
    </h1>

    <p class="fw-bold text-success">
        This is styled text.
    </p>

</div>
```

---

# 15.2 Jumbotron

A Jumbotron is a large highlighted box used to display important content.

It was mainly used in older Bootstrap versions.

---

# Example

```html id="u0q2h4"
<div class="p-5 bg-light border rounded">

    <h1>Welcome</h1>

    <p>
        This is a simple jumbotron style section.
    </p>

</div>
```

---

# Uses of Jumbotron

* Website introduction
* Highlight important information
* Hero section on homepage

---

# 15.3 Button Group

Button Group combines multiple buttons together in a single line.

---

# Example

```html id="x6l1a3"
<div class="btn-group">

    <button class="btn btn-primary">
        Left
    </button>

    <button class="btn btn-success">
        Middle
    </button>

    <button class="btn btn-danger">
        Right
    </button>

</div>
```

---

# Vertical Button Group

```html id="k7m3q1"
<div class="btn-group-vertical">

    <button class="btn btn-primary">
        Top
    </button>

    <button class="btn btn-success">
        Middle
    </button>

    <button class="btn btn-danger">
        Bottom
    </button>

</div>
```

---

# Uses

* Navigation controls
* Toolbar design
* Multiple related actions

---

# 15.4 Glyphicons

Glyphicons are small icon images used in Bootstrap 3.

Examples:

* Search icon
* Edit icon
* Delete icon

---

# Example (Bootstrap 3)

```html id="u3j8e2"
<span class="glyphicon glyphicon-search"></span>
```

---

# Important Note

Modern Bootstrap versions (Bootstrap 4 and 5) do not include Glyphicons.

Developers now use icon libraries like:

* Font Awesome
* Bootstrap Icons

---

# 15.5 Pagination

Pagination is used to divide content into multiple pages.

Example:

* Previous
* 1
* 2
* 3
* Next

---

# Example

```html id="g2p8c0"
<ul class="pagination">

    <li class="page-item">
        <a class="page-link" href="#">
            Previous
        </a>
    </li>

    <li class="page-item">
        <a class="page-link" href="#">
            1
        </a>
    </li>

    <li class="page-item">
        <a class="page-link" href="#">
            2
        </a>
    </li>

</ul>
```

---

# Uses of Pagination

* Blog pages
* Search results
* Product listings

---

# 15.6 Pager

Pager provides simple next and previous navigation buttons.

Mostly used in older Bootstrap versions.

---

# Example

```html id="u5n7d2"
<ul class="pager">

    <li>
        <a href="#">Previous</a>
    </li>

    <li>
        <a href="#">Next</a>
    </li>

</ul>
```

---

# Uses

* Previous/Next article navigation
* Simple page movement

---

# 15.7 List Group

List Group is used to display items in list format with styling.

---

# Example

```html id="d6q9x5"
<ul class="list-group">

    <li class="list-group-item">
        Home
    </li>

    <li class="list-group-item">
        About
    </li>

    <li class="list-group-item">
        Contact
    </li>

</ul>
```

---

# Active Item Example

```html id="w4z7v9"
<ul class="list-group">

    <li class="list-group-item active">
        Active Item
    </li>

    <li class="list-group-item">
        Normal Item
    </li>

</ul>
```

---

# Uses

* Menus
* Notifications
* Sidebar links

---

# 15.8 Carousel

Carousel is a slideshow component used to display multiple images or content.

Features:

* Automatic sliding
* Previous/Next controls
* Indicators

---

# Example

```html id="n1j5m8"
<div id="demo" class="carousel slide" data-bs-ride="carousel">

    <div class="carousel-inner">

        <div class="carousel-item active">

            <img src="image1.jpg" class="d-block w-100">

        </div>

        <div class="carousel-item">

            <img src="image2.jpg" class="d-block w-100">

        </div>

    </div>

</div>
```

---

# Uses of Carousel

* Image slideshow
* Product showcase
* Banner advertisements

---

# Complete Example

```html id="a7f9k2"
<!DOCTYPE html>
<html>
<head>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</head>

<body>

<div class="container mt-4">

    <h1 class="text-primary">
        Bootstrap Components
    </h1>

    <button class="btn btn-success">
        Click Me
    </button>

</div>

</body>
</html>
```

---

# Quick Revision Notes

## Typography

* Text styling classes
* Display headings
* Alignment and colors

## Jumbotron

* Large highlighted section
* Used for introductions

## Button Group

* Multiple buttons together

## Glyphicons

* Icons in Bootstrap 3

## Pagination

* Multi-page navigation

## Pager

* Previous/Next navigation

## List Group

* Styled list items

## Carousel

* Image/content slideshow

