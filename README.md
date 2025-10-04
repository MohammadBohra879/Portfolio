# Personal Portfolio Website
Author: Mohammad Bohra
Assignment: Responsive Personal Portfolio Website (Assignment - 1)

---

## 📌 Tools Used
- **HTML5** → For semantic page structure (`<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
- **CSS3 (External style.css)** → For custom styling (typography, colors, spacing, borders, hover & focus effects).
- **Tailwind CSS (via npm build → output.css)** → For responsive design, utility-based styling, flex/grid layouts.
- **No JavaScript Used** → Website built completely using HTML and CSS for simplicity and performance.

---

## 🌟 Features Implemented
1. **Multi-page Structure**
   - 3 pages: Home (`index.html`), Projects (`project.html`), Contact (`contact.html`).
   - Consistent navigation bar across all pages.

2. **Semantic HTML**
   - Correct use of semantic tags for clear and meaningful structure.

3. **Navigation**
   - Internal links between all pages.
   - Responsive navigation menu styled with Tailwind and custom CSS.

4. **Contact Form**
   - Includes fields for Name, Email, and Message.
   - Uses required validation attributes.
   - Submit buttons with hover and focus effects.

5. **Projects Section**
   - Table showing project details (Name, Description, Year).
   - Ordered list (Skills) and unordered list (Tools) included.

6. **Media Embedding**
   - Profile image on Home page.
   - Project demo videos (`project1.mp4`, `project2.mp4`).
   - Background music (`bg-music.mp3`).

7. **Styling (External CSS + Tailwind CSS)**
   - Typography, spacing, and borders styled in `style.css`, `projects.css`, and `contact_style.css`.
   - Hover and focus effects for links, buttons, and inputs.
   - Smooth transitions and color blending using Tailwind utilities.

8. **Responsive Design**
   - Tailwind’s responsive classes (`sm:`, `md:`, `lg:`) ensure the website adapts to all screen sizes.
   - Works seamlessly on mobile, tablet, and desktop screens.

---

## 📂 Folder Structure

myportfolio/
│── index.html              (Home Page)
│── project.html            (Projects Page)
│── contact.html            (Contact Page)
│── style.css               (Main CSS File)
│── projects.css            (Project Page CSS)
│── contact_style.css       (Contact Page CSS)
│── input.css               (Tailwind Input File)
│── output.css              (Compiled Tailwind CSS)
│
│── /assest
│     ├── profilepic.jpg
│     ├── contact-us.png
│     ├── bg-music.mp3
│     ├── project1.mp4
│     ├── project2.mp4
│
│── package.json
│── package-lock.json
│── /node_modules
│── /.vscode
│     ├── settings.json

---

## 🧩 Summary
This portfolio website highlights my(Mohammad Bohra) skills, academic projects, and contact details in a clean and responsive layout. The design combines custom CSS with Tailwind utilities to maintain simplicity, consistency, and responsiveness without relying on JavaScript.
