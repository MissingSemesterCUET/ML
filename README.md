# ML – Missing Semester CUET

Machine Learning bootcamp materials for [Missing Semester CUET](https://missingsemestercuet.github.io/).

## Branch Strategy

| Branch | Purpose |
|--------|---------|
| `main` | **Source only** – Quarto `.md`, `.ipynb`, config, and styles. No rendered HTML. |
| `gh-pages` | **Auto-generated** – built by GitHub Actions on every push to `main`. Never edit directly. |

## Local Preview

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview
```

This starts a local dev server with hot-reload at `http://localhost:4848`.

## Adding a New Lecture

1. Create a folder under `lectures/` following the naming convention:

   ```
   lectures/04-topic-name/
   ├── outline.md
   ├── slides.ipynb
   └── video.md
   ```

2. Add a sidebar entry in `_quarto.yml`:

   ```yaml
   - title: "Lecture 4 – Topic Name"
     style: docked
     collapse-level: 1
     contents:
       - section: "Lecture 4"
         contents:
           - text: "Outline"
             href: lectures/04-topic-name/outline.md
           - text: "Slides"
             href: lectures/04-topic-name/slides.ipynb
           - text: "Video"
             href: lectures/04-topic-name/video.md
   ```

3. Add a lecture card to `index.md`.

4. Push to `main` – the site rebuilds and deploys automatically.

## Project Structure

```
.
├── _quarto.yml          # Site config (sidebar, navbar, format)
├── styles.css           # Full custom dark theme
├── index.md             # Landing page
├── lectures/
│   ├── 01-linear-regression/
│   ├── 02-logistic-regression/
│   └── 03-neural-networks/
├── .github/workflows/
│   └── deploy.yml       # CI/CD pipeline
└── README.md
```

## License

Course materials © 2026 Missing Semester CUET. All rights reserved.
