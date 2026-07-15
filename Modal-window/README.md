# Modal Window Project 🖼️

A clean, interactive modal window built with HTML, CSS, and Vanilla JavaScript. This project is a practical exercise in front-end web development, focusing heavily on DOM manipulation, event listeners, and dynamic CSS class handling.

## 🚀 Features

- **Multiple Triggers:** Three separate buttons to trigger the modal window.
- **Interactive UI:** A smooth, blurred overlay effect appears behind the active modal to focus the user's attention.
- **Triple-Action Close Functionality:** The modal can be dismissed in three intuitive ways:
  1. **Click the 'X':** Standard close button interaction.
  2. **Click the Overlay:** Clicking anywhere outside the modal window dismisses it.
  3. **Escape Key:** Pressing the `Escape` (`Esc`) key on the keyboard triggers a global event listener to close the modal, demonstrating advanced event handling.

##  Technologies Used

- **HTML5:** Semantic structuring.
- **CSS3:** Custom styling, Flexbox, absolute positioning, and backdrop-filters.
- **Vanilla JavaScript:** DOM manipulation, handling node lists, and global keyboard events.

## 📸 Screenshots

### Initial State
![Initial View](image_246b9a.png)

### Active Modal
![Modal Open](image_246bb8.png)

##  Development Focus

Through building this project, the primary learning objectives included:
- Selecting multiple elements using `querySelectorAll` and iterating through them.
- Manipulating CSS classes using `classList.add`, `classList.remove`, and `classList.contains` to control visibility state instead of directly injecting inline CSS.
- Implementing the DRY (Don't Repeat Yourself) principle by creating reusable functions (`openModal` and `closeModal`).
- Attaching global `keydown` event listeners to the `document` object to capture the 'Escape' key press.

## 👨‍💻 Author

**Ahmed Alhayek**  
*Software Engineering Student & web Developer*
