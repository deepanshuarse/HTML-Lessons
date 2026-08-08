# Flexbox Practice

This file contains my **CSS Flexbox practice** using HTML and inline
CSS.

The goal of this practice is to understand how Flexbox controls the
layout, size, spacing, and alignment of elements.

## 📚 Concepts Practiced

### 1. Basic Flexbox

``` css
display: flex;
flex-direction: row;
```

Used to place elements next to each other in a horizontal row.

### 2. Fixed Width + `flex: 1`

``` css
width: 100px;
flex: 1;
```

The first element keeps a fixed width while the second element uses the
remaining available space.

### 3. Flex Ratios

``` css
flex: 1;
flex: 2;
```

Different `flex` values control how the remaining space is distributed
between elements.

For example:

-   `flex: 1` → takes 1 share
-   `flex: 2` → takes 2 shares

### 4. `justify-content: center`

``` css
justify-content: center;
```

Centers the flex items horizontally inside the container.

### 5. `justify-content: space-between`

``` css
justify-content: space-between;
```

Places equal space between the flex items.

### 6. `align-items: center`

``` css
align-items: center;
```

Aligns the flex items vertically in the center of the container.

## 🧪 Practice Examples

The HTML file contains examples demonstrating:

-   Basic row layouts
-   Fixed-width elements
-   Flexible elements
-   Different `flex` ratios
-   Horizontal centering
-   Space distribution with `space-between`
-   Vertical alignment with `align-items: center`
-   Borders and container heights

## 🛠️ Technologies

-   HTML5
-   CSS3
-   CSS Flexbox

## 🎯 What I Learned

Through this practice, I learned how to:

-   Create a Flexbox container
-   Arrange elements in rows
-   Give elements fixed and flexible widths
-   Distribute available space using `flex`
-   Center elements horizontally and vertically
-   Control spacing between elements

## ▶️ How to Run

Save the HTML code as something like:

``` text
flexbox-practice.html
```

Then open the file in a web browser.

------------------------------------------------------------------------

**Practice project --- learning CSS Flexbox step by step.**
