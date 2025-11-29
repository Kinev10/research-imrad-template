# 📘 Research IMRaD Template (Markdown + MkDocs)

Welcome to the **Research IMRaD Template** — a clean, modular, and GitHub-friendly way to write your academic research paper using:

- **Markdown** for writing  
- **MkDocs + Material theme** for documentation  
- **GitHub + GitHub Pages** for version control and publishing  

This template follows the **IMRaD structure**:

- **I**ntroduction  
- **M**ethods  
- **R**esults  
- **A**nd  
- **D**iscussion  

---

## 📁 Repository Structure

```
docs/
│
├── index.md
├── title-page.md
├── abstract.md
│
├── introduction/
│   ├── background.md
│   ├── research-questions.md
│   └── significance.md
│
├── methods/
│   ├── research-design.md
│   ├── participants-and-data.md
│   ├── data-collection.md
│   └── data-analysis.md
│
├── results/
│   ├── findings.md
│   └── tables-and-figures.md
│
├── discussion/
│   ├── interpretation.md
│   ├── limitations.md
│   └── recommendations.md
│
├── conclusion.md
├── references.md
│
├── appendices/
│   ├── questionnaire.md
│   └── supplementary-data.md
│
├── img/
└── src/
```

All research pages are written in **Markdown (.md)** files and organized by section.

---

## 🧩 Requirements

Install MkDocs and the Material theme:

```bash
pip install mkdocs mkdocs-material
```

---

## ▶️ Local Preview

To preview your research website locally:

```bash
mkdocs serve
```

Then open:

```
http://127.0.0.1:8000/
```

---

## 🌐 How to Enable GitHub Pages (Publishing Your Site)

This project is designed to be published online using **GitHub Pages** and **MkDocs**.

Follow these steps to enable the website version of your research.

---

### ✅ 1. Push your repository to GitHub

If you haven’t yet:

```bash
git add .
git commit -m "Initial commit"
git push
```

---

### ✅ 2. Automatic Deployment (Recommended)

This template includes a **GitHub Actions workflow** that automatically deploys your MkDocs site **whenever a Pull Request is merged into the `main` branch**.

The workflow will:

1. Build your MkDocs site  
2. Push the output to the `gh-pages` branch  
3. Update your GitHub Pages website  

---

### ✅ 3. One-Time Setup on GitHub Pages

After the first deployment:

1. Go to your repository’s **Settings**
2. Click **Pages**
3. Under *Build and Deployment*:
   - **Source:** Deploy from a branch  
   - **Branch:** `gh-pages`  
   - **Folder:** `/ (root)`
4. Click **Save**

Your live research website will be available at:

```
https://<username>.github.io/<repository-name>/
```

Example:

```
https://kinev10.github.io/research-imrad-template/
```

---

## ✍️ Editing Your Content

You can edit any page in the `docs/` folder.

Examples:

- `docs/introduction/background.md`
- `docs/methods/data-collection.md`
- `docs/results/findings.md`

Images go inside:

```
docs/img/
```

Source code or scripts go inside:

```
docs/src/
```

---

## 🔀 Git Workflow (Recommended for Students)

1. Create a branch before editing  
2. Commit changes  
3. Push the branch  
4. Open a Pull Request  
5. After PR is **merged**, GitHub Pages automatically updates  

---

## 🎉 You’re Ready!

You now have a complete IMRaD research repository with:

✔ GitHub version control  
✔ Organized Markdown pages  
✔ Auto-built MkDocs site  
✔ Auto-deployment to GitHub Pages  
