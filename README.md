# Epic Prompt Request Generator

A lightweight, web-based tool to generate structured prompts for any workflow—flexible, saveable, and copyable. Perfect for developers, designers, content creators, operations specialists, and strategists who need a quick way to formalize and organize requests.

---

## 🚀 Features

* **Dynamic Prompt Generation:** Automatically combines your inputs (category, context, request, parent task, subtask, relevant data) into a clean, structured prompt.
* **Save & Load Requests:** Store commonly used requests in the browser for quick reuse.
* **Copy & Download:** Copy the generated prompt to the clipboard or download it as a `.txt` file.
* **Autosave Form State:** Your progress is saved automatically in session storage to prevent data loss.
* **Responsive Design:** Works smoothly on desktop and mobile devices.
* **Customizable Categories:** Predefined categories include Development, Design, Content, Operations, Strategy, and Other.

---

## 📋 Usage

1. **Open the tool** in your browser (simply open the HTML file).
2. **Fill out the form:**

   * **Category:** Select a relevant category.
   * **Context:** Provide background information.
   * **Request:** Describe the task or problem you need help with (required).
   * **Parent Task / Subtask:** Optional fields to organize your request.
   * **Relevant Data:** Paste any code, CSV, JSON, logs, or other reference material.
3. **Generate Prompt:** Click `✨ Generate Prompt` to create a structured prompt based on your inputs.
4. **Copy or Download:**

   * `📋 Copy` copies the generated prompt to your clipboard.
   * `⬇️ Download` saves it as `prompt.txt`.
5. **Save Requests:** Use `💾 Save Request` to store prompts for future reuse.
6. **Clear Form:** Reset all fields using the `Clear Form` button.

---

## 🖥️ Installation

1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. No backend required—fully client-side.

---

## 🎨 Customization

* **Styling:** Edit the CSS variables in the `<style>` block to match your preferred colors or branding.

  ```css
  --primary-color: #9c4dff;
  --secondary-color: #6c34ff;
  --light-bg: #fafafa;
  ```
* **Categories:** Update the `<select>` options in the `Category` dropdown to match your workflow.

---

## ⚡ Technologies Used

* HTML5 & CSS3 (with CSS variables for easy theming)
* Vanilla JavaScript (no frameworks required)
* LocalStorage for saved requests
* SessionStorage for autosave functionality

---

## 🧩 How It Works

1. User fills in the form.
2. JavaScript collects input values and generates a structured prompt in Markdown-like format.
3. Optional fields (Parent Task, Subtask, Relevant Data) are appended if filled.
4. Autosave keeps the form state in session storage.
5. Saved requests are stored in LocalStorage for future retrieval.
6. Generated prompt can be copied or downloaded as a text file.

---

## 👤 Author

**John Wesley Quintero**
© 2025. All rights reserved.

---

## 📂 License

This project is free to use and modify for personal or professional use.
