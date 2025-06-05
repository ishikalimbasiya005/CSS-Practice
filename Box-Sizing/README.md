# Box-Sizing CSS Example

This project demonstrates the CSS `box-sizing` property with two common values: `content-box` and `border-box`.

---

## Description

The HTML file shows two headings styled with different box-sizing models:

1. **Content Box** (`box-sizing: content-box`)
   - Default box-sizing model.
   - The width and height only include the content.
   - Padding, border, and margin are added outside the specified size, increasing the total element size.
   - Example text:  
     `This is Content Box [padding + margin + border = actual size]`

2. **Border Box** (`box-sizing: border-box`)
   - Includes padding and border within the element’s width and height.
   - Makes sizing easier to manage as the total size stays consistent.
   - Example text: `This is Border Box`

---

## How to Use

1. Link the HTML file with your CSS file (e.g., `style.css`) containing the box-sizing styles.
2. Open the HTML file in a browser to see the difference between content-box and border-box.
3. Modify the CSS to experiment with the box-sizing property.
