# Git Playground (Fork Workflow) — AY 2025

A hands-on lab to practice **basic Git** with a real **GitHub PR workflow**.  
You will **fork** this repo, work on a **feature branch**, and open a **Pull Request** (PR) back to this class repo’s `main`.

> ✅ This repo has automated checks (GitHub Actions). Your PR will **fail** if:
> - Your **branch** does not start with **your GitHub username** (e.g., `ericrev/feature-readme`)
> - **README** does not list your **name + @username** under **Contributors**
> - Your **bio** file is missing or does not include **@username**
> - No **conventional commit** message or **issue number** in commits

---

## Objectives
- Practice **fork → branch → commit → push → pull request**
- Use **conventional commit messages** and reference issues
- Resolve a simple **merge conflict**
- Identify yourself clearly using your **GitHub username**

## Rules
- **Branch naming (required):** `your-github-username/feature-…`
- **Commit style:** Conventional Commits (e.g., `feat: …`, `docs: …`) and reference an issue `(#1)` or `(#2)`
- **Do not** push directly to `main`. Use a PR and request review.
- **Files to modify/add:** `README.md` (Contributors) and `students/<lastname>-bio.md`

## Prerequisites
- Git installed; GitHub account
- Configure your identity (once):
  ```bash
  git config --global user.name  "Your Name"
  git config --global user.email "your_email@example.com"
