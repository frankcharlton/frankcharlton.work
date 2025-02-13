# frankcharlton.work

Welcome to my static site repository! This site is built using **Hugo**, and will serve as my **data science portfolio** home. Hoping to have blog posts, articles, example projects, etc

## 🚀 Features
- **About Me** – My background, skills, and career journey.
- **Projects** – A collection of my work in data science, analytics, and software.
- **Blog** – Insights, tutorials, and reflections on data science topics.
- **Contact** – Links to connect with me on LinkedIn, GitHub, and email.

## 🛠️ Setup & Installation
To run this site locally:

1. **Clone the repository**
   ```sh
   git clone https://github.com/frankcharlton/frankcharlton.work.git
   cd frankcharlton.work
   ```

2. **Install Hugo** (if not already installed)
   - [Install Hugo](https://gohugo.io/getting-started/installing/)
   
3. **Run the Hugo server**
   ```sh
   hugo server --disableFastRender
   ```
   Visit `http://localhost:1313/` in your browser.

## 📂 Project Structure
```
/frankcharlton.work
├── content/       # Site content (Markdown files)
├── layouts/       # Custom templates
├── static/        # Static assets (CSS, JS, images)
├── themes/        # Hugo theme
├── config.toml    # Site configuration
└── README.md      # This file
```

## 📦 Deployment
This site can be deployed using **GitHub Pages**, **Netlify**, or **Vercel**. Example steps for GitHub Pages:

1. **Generate static files**
   ```sh
   hugo --cleanDestinationDir
   ```
2. **Deploy to GitHub Pages**
   ```sh
   git add .
   git commit -m "Deploy update"
   git push origin main
   ```

## 📬 Contact
- **Website:** [frankcharlton.work](https://frankcharlton.work)
- **GitHub:** [@frankcharlton](https://github.com/frankcharlton/)
- **LinkedIn:** [https://www.linkedin.com/in/frankcharlton/](https://www.linkedin.com/in/frankcharlton/)

## 📝 License
This project is licensed under the MIT License.
