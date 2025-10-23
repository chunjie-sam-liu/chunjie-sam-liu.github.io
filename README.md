# Chunjie Liu - Personal Website

A modern, responsive personal website built with [Astro](https://astro.build), featuring a clean design, blog functionality, and portfolio sections.

## 🚀 Features

- **Fast & Modern**: Built with Astro for optimal performance and SEO
- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Blog Ready**: Structured blog section with sample posts
- **Portfolio Showcase**: Projects section to highlight your work
- **Contact Form**: Interactive contact page (ready for backend integration)
- **TypeScript Support**: Full TypeScript support for better developer experience

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: CSS with custom properties and modern layouts
- **Type Safety**: TypeScript
- **Deployment**: GitHub Pages ready

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── about.astro
│   │   ├── projects.astro
│   │   ├── contact.astro
│   │   └── blog/
│   │       ├── index.astro
│   │       └── building-modern-website-astro.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🚀 Getting Started

1. **Clone or download this repository**
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Start the development server**:
   ```bash
   npm run dev
   ```
4. **Open your browser** and visit `http://localhost:4321`

## 📝 Customization

### Personal Information
- Update the navigation brand name in `src/layouts/BaseLayout.astro`
- Modify the hero section in `src/pages/index.astro`
- Edit your bio and skills in `src/pages/about.astro`
- Update project information in `src/pages/projects.astro`
- Add your contact details in `src/pages/contact.astro`

### Styling
- Global styles are in `src/styles/global.css`
- Component-specific styles are included in each `.astro` file
- The color scheme uses CSS custom properties for easy theming

### Adding Blog Posts
1. Create a new `.astro` file in `src/pages/blog/`
2. Follow the structure of existing posts
3. Update the posts array in `src/pages/blog/index.astro`

## 🌐 Deployment

This site is configured for deployment to GitHub Pages:

1. **Build the site**:
   ```bash
   npm run build
   ```
2. **Deploy**: The `dist/` folder contains your built site ready for deployment

### GitHub Pages Setup
1. Go to your repository settings
2. Navigate to Pages section
3. Set source to "GitHub Actions" or upload the `dist/` folder contents

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Contact

- Website: [https://chunjie-sam-liu.github.io](https://chunjie-sam-liu.github.io)
- GitHub: [@chunjie-sam-liu](https://github.com/chunjie-sam-liu)

---

Built with ❤️ using Astro