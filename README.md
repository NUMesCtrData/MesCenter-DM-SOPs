

### Mesulam Institute Data Management Practices

# 📘 SOP GitHub Pages Site

Welcome to the **Standard Operating Procedures (SOP)** repository! This site is hosted via [GitHub Pages](https://pages.github.com/) to provide a clear, accessible, and version-controlled reference for all standard workflows and procedures.

## 📄 What is this?

This repository contains SOP documentation for our team/organization. It serves as the single source of truth for day-to-day operational processes, ensuring consistency, compliance, and easy onboarding.

The site is automatically generated and updated using GitHub Pages. All updates pushed to the `main` (or `gh-pages`) branch are reflected live.

🔗 **Live Site:** [numesctrdata.github.io/MesCenter-DM-SOPs](https://numesctrdata.github.io/MesCenter-DM-SOPs/)

## 📁 Repository Structure

```
.
├── index.md           # Homepage
├── _config.yml        # Jekyll configuration for GitHub Pages
├── assets/            # Static files (images, PDFs, etc.)
├── sop/               # SOP markdown files
│   ├── sop-1.md
│   └── sop-2.md
├── README.md          # You're here!
```

## 🚀 How to Contribute

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-org/your-repo-name.git
   ```

2. **Make your changes:**  
   - Add or update SOP `.md` files inside the `sop/` folder.
   - Follow the existing formatting and naming conventions.

3. **Preview locally (optional):**
   If you're using Jekyll:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```

4. **Push your changes:**
   ```bash
   git add .
   git commit -m "Add/update SOP"
   git push origin main
   ```

## 📚 Writing SOPs

Use Markdown syntax to write SOPs. Each document should include:

- **Title**
- **Purpose**
- **Scope**
- **Responsibilities**
- **Procedure Steps**
- **Related Documents (if any)**
- **Revision History**

You can use this [template](./sop/sop-template.md) as a starting point.

## 🛠️ Tech Stack

- [GitHub Pages](https://pages.github.com/)
- [Jekyll](https://jekyllrb.com/)
- [Markdown](https://www.markdownguide.org/)

## 📬 Feedback & Support

If you spot an error or want to suggest improvements, feel free to [open an issue](https://github.com/your-org/your-repo-name/issues) or submit a pull request.

---

Let me know if you'd like a version that includes a sidebar, search, or a custom Jekyll theme too!

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/bookdown-template.*

