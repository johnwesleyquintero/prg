# ⚡ Epic Prompt Generator

A high-performance, browser-based tool designed to transform raw ideas into structured, professional prompts. Built for the modern builder who values speed, precision, and strategic autonomy.

---

## 🚀 Key Features

*   **Structured Prompt Engineering:** Automatically formats inputs (Category, Context, Core Request, Epics, Subtasks) into a clean, markdown-ready structure.
*   **Robust Copy System:** Enhanced clipboard integration that works across all environments, including local `file://` protocols and non-secure contexts.
*   **Persistent Workflow:**
    *   **Autosave:** Never lose progress with real-time session storage.
    *   **Request Presets:** Save and manage commonly used request templates in local storage.
*   **Intelligent UI/UX:**
    *   Responsive design for seamless mobile and desktop usage.
    *   Modern aesthetic powered by Google Fonts (Inter & JetBrains Mono) and Lucide Icons.
    *   Instant visual feedback (loading states, toast notifications).
*   **Dynamic Categories:** Supports 20+ professional domains including Software Engineering, AI/ML, DevOps, and Business Strategy.

---

## 📋 How to Use

1.  **Launch:** Open `index.html` in any modern web browser.
2.  **Input Details:**
    *   **Category:** Select your professional domain.
    *   **Context:** Provide the "Why" and "How" (e.g., tech stack, target audience).
    *   **Core Request:** The "What" — your primary objective (Required).
    *   **Organization:** Define Parent Tasks (Epics) and Subtasks for complex workflows.
    *   **Data/Code:** Paste snippets, logs, or JSON for deep analysis.
3.  **Execute:** Click `✨ Generate Prompt` to compile your request.
4.  **Export:**
    *   `📋 Copy`: Instant clipboard sync with visual confirmation.
    *   `⬇️ Save .txt`: Downloads a timestamped `.md` file for your records.
5.  **Manage:** Use `💾 Save Input` to create reusable presets or `🗑️ Delete` to clean up your library.

---

## 🖥️ Installation & Tech Stack

No installation required. This is a zero-dependency, pure client-side solution.

*   **Frontend:** HTML5, CSS3 (Modern Flex/Grid, Custom Properties)
*   **Logic:** Vanilla JavaScript (ES6+)
*   **Assets:** [Lucide Icons](https://lucide.dev/), [Google Fonts](https://fonts.google.com/)
*   **Storage:** LocalStorage (Presets) & SessionStorage (Drafts)

---

## 🎨 Strategic Customization

The system is built to be a reusable playbook. You can easily adapt the styles or categories in the source code:

```css
/* Update theme variables in :root */
--primary: #8b5cf6; /* Main brand color */
--radius: 12px;   /* UI rounding */
```

```javascript
/* Add custom categories in the script block */
const CATEGORIES = ["Your Custom Domain", ...];
```

---

## 👤 Author & Philosophy

**John Wesley Quintero**
*Founder | Architect | Educator*

This tool is built on the principle of **Building the System** — creating reusable, scalable assets that increase strategic autonomy and operational efficiency.

© 2025. Built for results.
