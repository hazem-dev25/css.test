# 🎨 CSS Background Properties Demo

This is a simple HTML and CSS project created to demonstrate how background properties work in CSS using a `<div>` element with repeated text.

## 🔧 What This Project Shows

- How to set a background image.
- How to control image position, repeat, and size.
- The effect of `background-attachment: fixed` when scrolling.

## 🧱 Code Breakdown

### ✅ HTML
A single `<div>` contains multiple `<p>` elements with the same text to create enough content for scrolling.

### ✅ CSS

``css
div {
    color: #000000;
    font-size: 25px; 
    background-color: blanchedalmond;
    background-repeat: no-repeat;
    background-image: url("your-image.jpeg");
    background-attachment: fixed;
    background-position: 10px 20px;
    background-size: cover;
    padding: 30px;
}
🧠 Explanation:
background-color: Adds a soft background color behind the image.

background-image: Sets a background image (make sure to replace "your-image.jpeg" with the actual image file).

background-repeat: no-repeat: Prevents the image from repeating.

background-position: 10px 20px: Moves the image 10px from the left and 20px from the top.

background-attachment: fixed: Fixes the background image in place when scrolling.

background-size: cover: Scales the image to fully cover the div.

padding: Adds inner spacing so the text doesn’t touch the edges.

📷 Result Preview
When viewed in a browser, you’ll see the text scrolling while the background image stays fixed. This creates a nice parallax-like effect.

🧑‍💻 Author
Hazem – Learning CSS one step at a time 💪

💡 Feel free to fork this and play with different background settings to understand them bette
