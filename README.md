# 📍 E-Commerce Product Image Swapper

This project simulates a key feature of an e-commerce product page: swapping the main product image based on user selection. When the user clicks on a color variant (e.g., "gold" or "silver"), the main image updates to reflect that choice.

This project demonstrates handling `onclick` events to dynamically update the `src` attribute of an `<img>` element.

![Project Demo GIF](demo4.gif)
*(Demo GIF shows the user clicking the "gold" and "silver" buttons, and the earring image changing accordingly)*

---

### 🛠️ Technologies Used

* **HTML5:** For the semantic structure of the product card and buttons.
* **CSS3:** For styling the product card, image, and the custom "gold" and "silver" buttons (using gradients, box-shadow, and border-radius).
* **JavaScript (ES6+):**
    * `getElementById("imageChange")` to select the main image element.
    * `onclick` event handlers (`goldChange()`, `silverChange()`) to trigger the image swap.
    * Updating the `.src` attribute of the image element to point to a new URL.

---

### 📖 What I Learned from this Project

* How to efficiently select a specific DOM element using its ID.
* How to use JavaScript functions to dynamically change the attributes (like `src`) of an HTML element in response to user events.
* Building a clean, modern, and reusable component for an e-commerce website.