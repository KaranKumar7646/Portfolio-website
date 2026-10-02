# 🌐 Karan Kumar — 3D Portfolio Website

An interactive, 3D personal portfolio website built to showcase my projects, skills, and experience.

<!-- Add a screenshot or GIF of your site here -->
<!-- ![Portfolio Preview](./3d-portfolio-main/public/preview.png) -->

🔗 **Live Demo:** [https://karan-portfolio-4x1y.onrender.com](https://karan-portfolio-4x1y.onrender.com)

---

## ✨ Features

- 🎨 Interactive 3D elements and smooth animations
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🧑‍💻 About, Skills, Projects, and Contact sections
- 📬 Working contact form
- ⚡ Fast build and load times

---

## 🛠️ Tech Stack

| Category   | Technologies                                    |
| ---------- | ----------------------------------------------- |
| Frontend   | React, JavaScript, HTML5, CSS3                  |
| 3D / Motion| Three.js, React Three Fiber, Framer Motion      |
| Styling    | Tailwind CSS                                    |
| Tooling    | Vite, npm, Git & GitHub                         |

> Update this table to match the exact libraries listed in `3d-portfolio-main/package.json`.

---

## 📁 Project Structure

```
Portfolio-website/
├── 3d-portfolio-main/    # Main application source code
│   ├── public/           # Static assets and 3D models
│   ├── src/              # Components, sections, styles
│   └── package.json
├── .gitignore
└── package-lock.json
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- npm (comes with Node.js)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/KaranKumar7646/Portfolio-website.git

# 2. Go into the project folder
cd Portfolio-website/3d-portfolio-main

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

Then open the local URL shown in your terminal (usually `http://localhost:5173`).

### Build for production

```bash
npm run build
npm run preview
```

---

## 🔐 Environment Variables

If the contact form uses a service like EmailJS, create a `.env` file inside `3d-portfolio-main/`:

```env
VITE_APP_EMAILJS_SERVICE_ID=your_service_id
VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
```

Never commit your `.env` file to GitHub.

---

## 🌍 Deployment

This site is currently deployed on [Render](https://render.com/). It can also be deployed for free on:

- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/)

Set the root directory to `3d-portfolio-main` and the build command to `npm run build`.

---

## 🤝 Contributing

Suggestions and improvements are welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📬 Contact

**Karan Kumar**

- GitHub: [@KaranKumar7646](https://github.com/KaranKumar7646)
- LinkedIn: [Add your link](https://linkedin.com/in/your-profile)
- Email: your-email@example.com

---

⭐ If you like this project, consider giving it a star!
