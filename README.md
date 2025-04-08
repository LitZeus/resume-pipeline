# 📄 Resume – Tejas Athalye

This repository contains the LaTeX source code for my professional resume. It is automatically compiled and deployed to GitHub Pages using GitHub Actions.

## 🔧 Tech Stack

- 📄 **LaTeX** – Clean and structured typesetting  
- ⚙️ **GitHub Actions** – Auto-compilation and deployment  
- 🌐 **GitHub Pages** – Hosted PDF resume  

## 🔗 Live Resume

You can always view and download the latest version of my resume here:

👉 [Resume_Tejas_Athalye.pdf](https://litzeus.github.io/resume-pipeline/Resume_Tejas_Athalye.pdf)

## 🛠️ Local Development

If you'd like to compile this resume locally:

```bash
# Clone the repo
git clone https://github.com/LitZeus/resume-pipeline.git
cd resume-pipeline

# Compile using latexmk or any LaTeX editor
latexmk -pdf resume.tex
```

## 🔁 Workflow Usage

The [GitHub Actions workflow](.github/workflows/build.yml) is automatically triggered on every push to the `main` branch. It performs the following steps:

1. Checks out the repository.
2. Compiles the LaTeX source (`resume.tex`) to PDF using `latexmk`.
3. Renames the output to `Resume_Tejas_Athalye.pdf`.
4. Moves it to the `public/` directory.
5. Pushes it to the `gh-pages` branch.
6. GitHub Pages then serves it at:

```
https://litzeus.github.io/resume-pipeline/Resume_Tejas_Athalye.pdf
```

## 📂 Output File Structure

```bash
├── resume.tex
├── public/
│   └── Resume_Tejas_Athalye.pdf
```

---

> 📌 Tip: Bookmark the live link above to always access your latest resume!
