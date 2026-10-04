# 🖼️ Dynamic Gallery

A simple and responsive **Dynamic Gallery** created using **HTML and CSS**.
The gallery uses **CSS Flexbox** to arrange multiple image columns, with each column containing images in a different order.

## 📌 Project Overview

This project demonstrates how to create a multi-column image gallery using:

* HTML5
* CSS3
* Flexbox
* Images

Each column has a width of **25%**, creating a four-column gallery layout.

## ✨ Features

* 📷 Four-column image gallery
* 🎨 Simple and clean design
* 📐 Flexbox-based layout
* 🔄 Different image arrangements in each column
* 📱 Basic responsive structure
* 🧩 Easy to customize

## 🛠️ Technologies Used

| Technology | Purpose                          |
| ---------- | -------------------------------- |
| HTML5      | Creating the webpage structure   |
| CSS3       | Styling and layout               |
| Flexbox    | Creating the four-column gallery |

## 📂 Project Structure

```text
Dynamic-Gallery/
│
├── index.html
├── 1.png
├── 2.png
├── 3.png
├── 4.png
└── README.md
```

## 💻 HTML Structure

The main gallery is created using a `.container` that contains four `.box` elements.

```html
<div class="container">

    <div class="box">
        <img src="1.png" alt="">
        <img src="2.png" alt="">
        <img src="3.png" alt="">
        <img src="4.png" alt="">
    </div>

    <div class="box">
        <img src="4.png" alt="">
        <img src="2.png" alt="">
        <img src="1.png" alt="">
        <img src="3.png" alt="">
    </div>

</div>
```

## 🎨 CSS Concepts Used

### 1. Flexbox

```css
.container {
    display: flex;
}
```

Flexbox is used to arrange the four image columns horizontally.

### 2. Column Width

```css
.box {
    width: 25%;
}
```

Each column occupies **25% of the container width**, resulting in four equal columns.

### 3. Image Width

```css
img {
    width: 100%;
}
```

Each image automatically takes the complete width of its column.

### 4. Box Sizing

```css
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
```

This resets the default margin and padding and
