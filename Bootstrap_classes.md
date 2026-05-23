## Bootstrap classes
# 13. Bootstrap Classes

## 13.1 Using Bootstrap Classes

In Bootstrap, classes are predefined CSS styles that help design web pages quickly.

Bootstrap classes are added inside the `class` attribute of HTML elements.

### Syntax

```html id="8gqq1q"
<tag class="bootstrap-class">Content</tag>
```

### Example

```html id="fwy1k3"
<h1 class="text-primary">Welcome</h1>
```

Here:

* `text-primary` changes text color to blue.

---

# Common Bootstrap Classes

| Class          | Purpose          |
| -------------- | ---------------- |
| `text-primary` | Blue text        |
| `text-danger`  | Red text         |
| `bg-dark`      | Dark background  |
| `text-white`   | White text       |
| `p-3`          | Padding          |
| `m-3`          | Margin           |
| `fw-bold`      | Bold text        |
| `text-center`  | Center alignment |

---

# Example

```html id="3mrj9t"
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<h1 class="text-center text-success">
    Bootstrap Classes
</h1>

<p class="bg-dark text-white p-3">
    This is a paragraph using Bootstrap classes.
</p>

</body>
</html>
```

---

# 13.2 Bootstrap Containers

A container is used to keep webpage content properly aligned and responsive.

Bootstrap provides two main types of containers.

---

## 1. `.container`

* Fixed width container
* Width changes according to screen size

### Example

```html id="m8p9g4"
<div class="container bg-light p-3">
    Fixed Width Container
</div>
```

---

## 2. `.container-fluid`

* Full width container
* Takes 100% screen width

### Example

```html id="agx7j9"
<div class="container-fluid bg-warning p-3">
    Full Width Container
</div>
```

---

# Difference Between Containers

| Container Type     | Width                  |
| ------------------ | ---------------------- |
| `.container`       | Fixed responsive width |
| `.container-fluid` | Full screen width      |

---

# Complete Example

```html id="azf61n"
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<div class="container bg-info p-3">
    Normal Container
</div>

<div class="container-fluid bg-success text-white p-3 mt-3">
    Fluid Container
</div>

</body>
</html>
```

---

# 13.3 Bootstrap Buttons

Bootstrap provides stylish ready-made buttons using button classes.

---

# Basic Button Class

```html id="u3ez3k"
<button class="btn">Button</button>
```

---

# Button Types

| Class         | Button Color |
| ------------- | ------------ |
| `btn-primary` | Blue         |
| `btn-success` | Green        |
| `btn-danger`  | Red          |
| `btn-warning` | Yellow       |
| `btn-dark`    | Black        |
| `btn-light`   | Light        |
| `btn-info`    | Sky blue     |

---

# Example

```html id="rj7q66"
<button class="btn btn-primary">Primary</button>

<button class="btn btn-success">Success</button>

<button class="btn btn-danger">Danger</button>
```

---

# Large and Small Buttons

```html id="wwg46l"
<button class="btn btn-primary btn-lg">
    Large Button
</button>

<button class="btn btn-secondary btn-sm">
    Small Button
</button>
```

---

# Full Example

```html id="bvrfzi"
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body class="p-4">

<button class="btn btn-primary">
    Save
</button>

<button class="btn btn-success">
    Submit
</button>

<button class="btn btn-danger">
    Delete
</button>

</body>
</html>
```

---

# 13.4 Bootstrap Utilities

Utilities are helper classes used for:

* Spacing
* Alignment
* Colors
* Display
* Sizing

They reduce the need for custom CSS.

---

# Spacing Utilities

## Margin Classes

| Class  | Meaning             |
| ------ | ------------------- |
| `m-3`  | Margin on all sides |
| `mt-3` | Margin top          |
| `mb-3` | Margin bottom       |
| `ms-3` | Margin left         |
| `me-3` | Margin right        |

---

## Padding Classes

| Class  | Meaning           |
| ------ | ----------------- |
| `p-3`  | Padding all sides |
| `pt-3` | Padding top       |
| `pb-3` | Padding bottom    |

---

# Text Utilities

| Class         | Purpose     |
| ------------- | ----------- |
| `text-center` | Center text |
| `text-start`  | Left align  |
| `text-end`    | Right align |
| `fw-bold`     | Bold text   |

---

# Background Utilities

| Class        | Purpose          |
| ------------ | ---------------- |
| `bg-primary` | Blue background  |
| `bg-success` | Green background |
| `bg-danger`  | Red background   |

---

# Display Utilities

| Class     | Purpose       |
| --------- | ------------- |
| `d-none`  | Hide element  |
| `d-block` | Block display |
| `d-flex`  | Flex display  |

---

# Example

```html id="4s5t6i"
<!DOCTYPE html>
<html>
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<h1 class="text-center text-primary mt-4">
    Bootstrap Utilities
</h1>

<div class="bg-success text-white p-4 m-4">
    Utility Classes Example
</div>

</body>
</html>
```

---

# Quick Revision Notes

## Bootstrap Classes

* Predefined CSS styles
* Added using `class=""`

## Containers

* `.container` → fixed width
* `.container-fluid` → full width

## Buttons

* Use `btn`
* Example: `btn-primary`, `btn-success`

## Utilities

* Spacing classes
* Text alignment
* Background colors
* Display helpers

btn.primary
