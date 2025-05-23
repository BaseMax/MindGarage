# MindGarage (تعمیرکار معز)

[![Deploy to GitHub Pages](https://github.com/BaseMax/MindGarage/actions/workflows/deploy.yml/badge.svg)](https://github.com/BaseMax/MindGarage/actions)

**MindGarage** (Persian: تعمیرکار معز) is a minimalist, clean, and fast blog powered by the [Zola](https://www.getzola.org/) static site generator. It's built for writers and developers who value focus, simplicity, and performance. All posts are written in Markdown and statically rendered for optimal speed and SEO.

🌐 **Live blog**: [https://basemax.github.io/MindGarage/](https://basemax.github.io/MindGarage/)

## ✨ Features

- 📝 Markdown-based blogging
- 🌍 Multi-language friendly (including full Persian support)
- 🎨 Clean, responsive theme ([even-persian](./themes/even-persian))
- ⚡ Built and deployed automatically using GitHub Actions
- 🔒 No database, no server, just HTML — secure and maintenance-free

## 🛠️ Getting Started

To run the blog locally:

1. [Install Zola](https://www.getzola.org/documentation/getting-started/installation/)
2. Clone this repo:
   ```bash
   git clone https://github.com/BaseMax/MindGarage.git
   cd MindGarage
   ```
3. Run the development server:
    ```bash
    zola serve
    ```
4. Visit http://localhost:1111 in your browser

## 🚀 Deployment

This project uses GitHub Actions to automatically build and deploy the site to GitHub Pages on every push to the main branch.

- Workflow: `.github/workflows/deploy.yml`
- Key points:
    - Zola is cached and installed if needed
    - The site is built using zola build
    - The output in `/public` is pushed to the `gh-pages` branch

📦 You can customize deployment settings by editing the workflow file.

## 🧩 Folder Structure

```bash
MindGarage/
├── content/            # Blog posts and pages (Markdown)
│   ├── pages/about.md
│   ├── hello-world.md
│   └── ...
├── themes/even-persian # Theme with Persian support
├── config.toml         # Site configuration
├── LICENSE
├── README.md
├── telegram2blogmd.py  # Optional: your Telegram-to-blog converter
└── .github/workflows/
    └── deploy.yml      # GitHub Actions deployment script

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

Made with ❤️ by Max Base (BaseMax)

Copyright 2025, Keegan, Max Base
