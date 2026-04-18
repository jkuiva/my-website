# My Website

This repository contains the source code for my personal website, built as a simple static site and deployed automatically using **Cloudflare Pages**.  
The goal of this project is to practise real-world Git workflows, web fundamentals, and modern deployment pipelines.

---

## 🚀 Deployment

The site is deployed through **Cloudflare Pages**, which automatically builds and publishes the site whenever changes are merged into the `main` branch.

**Production URL:**  
<https://www.kuivalainen.eu>

**Preview Deployments:**  
Every pull request triggers an automatic preview build, allowing changes to be tested before merging.

---

## 🧩 Tech Stack

- **HTML5**  
- **CSS3**  
- **Static assets** (images, icons, etc.)  
- **Cloudflare Pages** for hosting and CI/CD  
- **GitHub** for version control and workflow management

No frameworks or build tools are used at this stage — the focus is on fundamentals.

---

## 🔄 Workflow

This project uses a **moderate, professional-style Git workflow**:

### `main` branch

- Always stable  
- Automatically deployed to production  
- Protected by GitHub branch rules  

### Feature branches

Used for all non-trivial changes.  
Examples:

- `feature/new-layout`
- `content/update-homepage`
- `fix/navbar-spacing`

### Pull Requests

- Every change is submitted through a PR  
- Cloudflare Pages generates a preview deployment  
- Changes are reviewed before merging  
- Ensures clean history and stable production

---

## 📁 Project Structure

```text
/
├── index.html        # Main page
├── styles.css        # Global styles
├── images/           # Static images
└── README.md         # Project documentation
```

---

## 🧪 Local Development

You can open the site locally by simply opening `index.html` in a browser.  
No build steps or dependencies required.

---

## 🎯 Purpose of This Project

This repository is part of my learning path toward:

- Practising Git branching and PR workflows  
- Understanding static site deployment  
- Building clean, maintainable web projects  
- Preparing for future work in system administration and infrastructure roles  
- Developing intuition for version control and CI/CD pipelines  

---

## 📬 Contact

**Juha Kuivalainen**  
<https://www.kuivalainen.eu>
