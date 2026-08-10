MyBlog — Personal Portfolio & Blog

A clean, modern personal portfolio and blog page built with pure HTML and CSS.

MyBlog is a lightweight, single-page personal portfolio designed for a web developer based in Tehran. It presents a professional online presence with a sleek dark theme, smooth interactions, and a contact form — all in a simple, no‑framework setup.

---

✨ Features

· Personal Branding — Clean layout with a profile image, name, and tagline.
· About Section — Introduce yourself and your expertise.
· Contact Form — A styled form for visitors to send messages.
· Sticky Navigation — Easy access to different sections.
· Fully Responsive — Adapts to various screen sizes (including landscape mobile).
· Dark Theme — Modern gradient background with vibrant accent colors.
· Smooth Interactions — Hover effects, transitions, and focus states.

---

🛠️ Tech Stack

· HTML5 — Semantic structure
· CSS3 — Custom properties (variables), flexbox, backdrop‑filter, media queries
· No JavaScript — Pure static site

---

📂 Project Structure

```
MyBlog/
├── index.html              # Main page
├── Style.css               # All styles (variables, layout, components)
├── README.md               # Project documentation
└── Components/
    └── Picture/
        ├── Logo.jpg        # Profile / logo image
        └── Icons/          # (additional icon assets)
```

---

🚀 Getting Started

Prerequisites

· Any modern web browser
· A code editor (optional, for customization)

Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Dani-Devlop/MyBlog.git
   ```
2. Navigate to the project folder
   ```bash
   cd MyBlog
   ```
3. Open index.html in your browser — double‑click the file or use a live server.

---

🎨 Customization

Colors

Edit the CSS variables in :root inside Style.css:

```css
:root {
  --title: hsl(216, 100%, 50%);
  --primary-backgroud-color: #0D0D0D;
  --link-Botton-Title-color: #0066FF;
  --Hover-Color: #AA00FF;
  --text-color: rgb(255, 255, 255);
}
```

Content

Update the text in index.html — change the name, about description, and navigation links.

Profile Image

Replace Components/Picture/Logo.jpg with your own image (keep the same filename or update the src attribute in the <img> tag).

---

📱 Responsive Design

· Desktop — Full‑width sections with centered content.
· Mobile (landscape) — Special handling for phones in landscape orientation (see @media query in Style.css).
· Scrollbar — Hidden for a cleaner look (scrollbar-width: none).

---

🤝 Contributing

Contributions are welcome! If you have suggestions or improvements:

1. Fork the repository
2. Create a feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

📄 License

This project is open source and available under the MIT License.

---

🙋‍♂️ Author

Dani — Web Developer
GitHub: @Dani-Devlop

---

⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!