Ось README.md для вашого репозиторію goit-js-hw-08.

Судячи з назви та структури (а також класичної програми курсу GoIT), це домашнє завдання з Vanilla JavaScript, де створюється інтерактивна галерея зображень. Основний акцент тут зазвичай робиться на роботу з DOM, делегування подій (Event Delegation) та використання сторонніх бібліотек (наприклад, для модального вікна — basicLightbox).

Ви можете скопіювати цей код:

Markdown
# Interactive Image Gallery 🖼️

A Vanilla JavaScript project built as part of the GoIT course homework. This application demonstrates how to create a dynamic, interactive image gallery using clean JavaScript, event delegation, and third-party libraries.

🔗 **[Live Demo](https://ibuizle.github.io/goit-js-hw-08/)**

## 📖 About the Project

The main objective of this project was to practice DOM manipulation and event handling in JavaScript. Instead of attaching event listeners to every single image, the project utilizes the **Event Delegation** pattern on the parent container, making the application much more efficient. When a user clicks on an image, a high-resolution version opens in a modal window.

### Key Features:
- **Dynamic Rendering:** The gallery interface is generated dynamically using JavaScript based on an array of data.
- **Event Delegation:** Optimized event listening by attaching a single listener to the gallery wrapper.
- **Modal Window:** Clicking an image opens a modal window with the full-sized picture (often using a library like `basicLightbox`).
- **Keyboard Navigation:** Users can close the modal window by pressing the `Escape` key.

## 🛠 Built With

- **HTML5:** Semantic structure.
- **CSS3:** Styling and responsive grid layout.
- **Vanilla JavaScript:** Core logic, DOM manipulation, and event handling.
- **Third-Party Library:** (e.g., SimpleLightbox or basicLightbox) used for the modal functionality.

## 🚀 How to Run Locally

To check out the project on your local machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ibuizle/goit-js-hw-08.git](https://github.com/ibuizle/goit-js-hw-08.git)
Navigate into the project folder:

Bash
cd goit-js-hw-08
Open the project:
Simply open the index.html file in your browser, or use an extension like Live Server in VS Code for a better development experience.

👤 Author
GitHub — @ibuizle
