## Grid System of Bootstrap
# 14. Bootstrap Grid System

The Bootstrap Grid System is used to create responsive webpage layouts using rows and columns.

Bootstrap uses a **12-column grid system**.

---

# 14.1 Rows and Columns

## What is a Row?

A row is a horizontal section used to hold columns.

Bootstrap uses:

```html id="5nbg0w"
<div class="row">
</div>
```

---

## What is a Column?

Columns divide the row into sections.

Bootstrap provides classes like:

* `col`
* `col-6`
* `col-4`
* `col-md-6`

---

# Basic Structure

```html id="ux8n8n"
<div class="container">

    <div class="row">

        <div class="col">
            Column 1
        </div>

        <div class="col">
            Column 2
        </div>

    </div>

</div>
```

---

# Example of 12-Column System

```html id="k1u4f5"
<div class="row">

    <div class="col-6 bg-primary text-white">
        6 Columns
    </div>

    <div class="col-6 bg-success text-white">
        6 Columns
    </div>

</div>
```

Here:

* `6 + 6 = 12`

---

# More Examples

## 3 Equal Columns

```html id="0brh5m"
<div class="row">

    <div class="col-4">Column 1</div>

    <div class="col-4">Column 2</div>

    <div class="col-4">Column 3</div>

</div>
```

---

# Important Points

| Element     | Purpose                |
| ----------- | ---------------------- |
| `container` | Main wrapper           |
| `row`       | Creates horizontal row |
| `col`       | Creates column         |

---

# 14.2 Grid Layout

A grid layout arranges webpage content into rows and columns.

Bootstrap grid system is:

* Flexible
* Responsive
* Mobile-friendly

---

# Types of Grid Layouts

## 1. Equal Width Layout

```html id="ib80t0"
<div class="row">

    <div class="col bg-info">
        Column 1
    </div>

    <div class="col bg-warning">
        Column 2
    </div>

</div>
```

Bootstrap automatically divides space equally.

---

## 2. Unequal Width Layout

```html id="qgv74c"
<div class="row">

    <div class="col-8 bg-primary text-white">
        Large Section
    </div>

    <div class="col-4 bg-dark text-white">
        Small Section
    </div>

</div>
```

---

# Nested Grid Layout

A row can contain another row inside a column.

```html id="x3o4ee"
<div class="container">

    <div class="row">

        <div class="col-6 bg-info">

            Parent Column

            <div class="row">

                <div class="col-6 bg-warning">
                    Child 1
                </div>

                <div class="col-6 bg-success">
                    Child 2
                </div>

            </div>

        </div>

    </div>

</div>
```

---

# 14.3 Responsive Grid Classes

Responsive grid classes automatically adjust layout for different screen sizes.

Bootstrap screen sizes:

| Screen Size    | Class Prefix |
| -------------- | ------------ |
| Extra Small    | `col-`       |
| Small Devices  | `col-sm-`    |
| Medium Devices | `col-md-`    |
| Large Devices  | `col-lg-`    |
| Extra Large    | `col-xl-`    |

---

# Example

```html id="j8g9ut"
<div class="row">

    <div class="col-md-6 bg-primary text-white">
        Left Side
    </div>

    <div class="col-md-6 bg-success text-white">
        Right Side
    </div>

</div>
```

### Working:

* On medium and larger screens → 2 columns
* On small screens → columns stack vertically

---

# Multi-Device Example

```html id="yn1x8z"
<div class="row">

    <div class="col-sm-12 col-md-6 col-lg-4 bg-info">
        Column 1
    </div>

    <div class="col-sm-12 col-md-6 col-lg-4 bg-warning">
        Column 2
    </div>

    <div class="col-sm-12 col-md-12 col-lg-4 bg-success">
        Column 3
    </div>

</div>
```

---

# Responsive Layout Behavior

| Screen  | Layout              |
| ------- | ------------------- |
| Mobile  | Full width columns  |
| Tablet  | Two-column layout   |
| Desktop | Three-column layout |

---

# 14.4 Container and Fluid Container

Bootstrap provides two main containers.

---

# 1. `.container`

* Fixed responsive width
* Leaves margins on sides

```html id="j4j1k0"
<div class="container bg-light p-3">

    Fixed Width Container

</div>
```

---

# 2. `.container-fluid`

* Full width container
* Uses complete screen width

```html id="zn3w6g"
<div class="container-fluid bg-primary text-white p-3">

    Full Width Container

</div>
```

---

# Difference Between Container Types

| Container Type     | Width                  |
| ------------------ | ---------------------- |
| `.container`       | Fixed responsive width |
| `.container-fluid` | 100% width             |

---

# Complete Grid Example

```html id="v1kq1n"
<!DOCTYPE html>
<html>
<head>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

</head>

<body>

<div class="container">

    <div class="row">

        <div class="col-md-4 bg-primary text-white p-3">
            Column 1
        </div>

        <div class="col-md-4 bg-success text-white p-3">
            Column 2
        </div>

        <div class="col-md-4 bg-danger text-white p-3">
            Column 3
        </div>

    </div>

</div>

</body>
</html>
```

---

# Important Grid Rules

1. Always place columns inside rows.
2. Always place rows inside containers.
3. Total columns in one row should generally equal 12.
4. Use responsive classes for mobile-friendly layouts.

---

# Quick Revision Notes

## Grid System

* Based on 12 columns
* Used for responsive layouts

## Rows and Columns

* `row` → horizontal section
* `col` → vertical section

## Responsive Classes

* `col-sm-*`
* `col-md-*`
* `col-lg-*`

## Containers

* `.container` → fixed width
* `.container-fluid` → full width
