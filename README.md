# ML – Missing Semester CUET

This repository contains the source code for the Machine Learning section of the **Missing Semester CUET** bootcamp. The website is built using [Quarto](https://quarto.org/) and automatically deployed to GitHub Pages.

## 🚀 Live Website

The live website can be found at: [https://MissingSemesterCUET.github.io/ML/](https://MissingSemesterCUET.github.io/ML/)

## 🛠 Tech Stack

- **Quarto**: For generating the static website from Markdown and Jupyter notebooks.
- **GitHub Actions**: For automated CI/CD.
- **GitHub Pages**: For hosting the built site.
- **Bootswatch (Darkly)**: For a modern dark theme.

## 📂 Repository Structure

- `main` branch: **Source files only**. Markdown, notebooks, configs, and workflows live here.
- `gh-pages` branch: **Built website**. This branch is automatically updated by GitHub Actions and should not be modified manually.

## 💻 Local Development

To preview the website locally:

1.  Install [Quarto](https://quarto.org/docs/get-started/).
2.  Clone this repository.
3.  Run the following command in the root directory:
    ```bash
    quarto preview
    ```

## ➕ How to Add a New Lecture

Follow these steps to add a new lecture (e.g., `04-neural-networks`):

1.  **Create a Directory:** Create `lectures/04-neural-networks/`.
2.  **Add Files:** Create `outline.md`, `slides.ipynb` (pre-executed), and `video.md`.
3.  **Update Config:** Open `_quarto.yml` and add the new lecture to the `sidebar` section.
4.  **Update Landing Page:** Add a new card for the lecture in `index.md`.
5.  **Commit and Push:** Push your changes to the `main` branch. GitHub Actions will handle the rest!

## 🤝 Contribution Guidelines

- Ensure all Jupyter notebooks are pre-executed with visible outputs.
- Maintain the dark theme aesthetic.
- Use technically accurate but accessible language.
- Link to relevant external resources where appropriate.

---
© 2026 Missing Semester CUET – Machine Learning Section
