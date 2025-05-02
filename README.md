````markdown
# 🏨 Trillo — Your All-in-One Booking App

Trillo is a responsive, modern hotel booking landing page template built with **HTML**, **SCSS**, and **JavaScript**. It's a frontend-only project designed to showcase layout techniques using **Flexbox**, **Grid**, and modular SCSS architecture.

## 🚀 Features

- Hotel search interface
- Navigation bar with interactive icons
- Gallery of hotel images
- Hotel description and amenities
- User reviews section
- Booking call-to-action (CTA)

## 📸 Preview

![Trillo Screenshot](https://raw.githubusercontent.com/auroraEros/trillo/refs/heads/main/img/screenshot.png)

## 🛠 Technologies Used

- HTML5
- SCSS (compiled via `node-sass`)
- PostCSS + Autoprefixer
- Live Server (for development)
- npm-run-all (task management)

## 📦 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/trillo.git
   cd trillo
   ```
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm start
   ```

   This will:

   - Compile SCSS to CSS in watch mode
   - Launch Live Server for hot-reloading

## 🛠 Available Scripts

| Script         | Description                                       |
| -------------- | ------------------------------------------------- |
| `npm start`    | Runs `devserver` and `watch:sass` in parallel     |
| `watch:sass`   | Watches SCSS files and compiles them to CSS       |
| `compile:sass` | Compiles `sass/main.scss` to `css/style.comp.css` |
| `prefix:css`   | Adds vendor prefixes using PostCSS                |
| `compress:css` | Compresses final CSS                              |
| `build:css`    | Runs all steps to generate final CSS              |

## 📁 Folder Structure

```
trillo/
│
├── css/
│   └── style.css          # Compiled CSS
│
├── sass/
│   └── main.scss          # Main SCSS file (modularized)
│
├── img/
│   └── ...                # Images and sprite.svg
│
├── index.html
├── package.json
└── README.md
```

### 📌 Live Demo

## Demo

You can view the live demo of the project here:  
[Trillo - Netlify](https://aurora-trillo.netlify.app/)

## 📸 Credits

- Icons from [iconmonstr.com](https://iconmonstr.com)
- Fonts from [Google Fonts](https://fonts.google.com/)
- Design inspired by Jonas Schmedtmann’s Advanced CSS course

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Designed and built by **Sahar** ✨
