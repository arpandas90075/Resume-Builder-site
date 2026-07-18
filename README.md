# ResumeForge 📄

A free, lightweight resume builder that runs entirely in your browser — no signup, no backend, no data ever leaves your device. Build a professional resume in minutes and download it as a PDF.

**[Live Demo](#)** · *(add your GitHub Pages link here)*

##  Features

- **Two ways to start**
  -  **Create your own** — start from a blank canvas and fill in your details step by step
  -  **Choose from our resumes** — pick from 6 pre-filled sample resumes and edit anything
- **6 designer templates** — Modern, Classic, Minimal, Creative, Professional, Elegant
- **Live A4 preview** — see your resume update in real time as you type
- **Full customization** — switch templates, accent colors (8 presets + custom color picker), and fonts anytime without losing your content
- **One-click PDF download** — generates a real `.pdf` file directly in the browser via html2pdf.js
- **Auto-save** — your draft is saved to localStorage, so you can close the tab and continue later
- **Sections included** — personal info, professional summary, work experience, education, skills, and languages
- **Responsive** — works on desktop and mobile

##  Getting Started

No build tools, no dependencies to install.

```bash
git clone https://github.com/<arpandas90075>/resumeforge.git
cd resumeforge
```

Then just open `resume-builder.html` in any modern browser. That's it.

> **Note:** An internet connection is needed the first time, to load the html2pdf.js library from CDN.

### Deploy to GitHub Pages

1. Push this repo to GitHub
2. Rename `resume-builder.html` to `index.html` (optional, for a cleaner URL)
3. Go to **Settings → Pages → Source** and select your main branch
4. Your site is live at `https://<arpandas90075>.github.io/resumeforge/`

##  Templates

| Template | Style |
|---|---|
| **Modern** | Bold colored sidebar layout |
| **Classic** | Timeless centered serif design |
| **Minimal** | Clean and airy with lots of whitespace |
| **Creative** | Colorful gradient banner header |
| **Professional** | Sharp corporate look |
| **Elegant** | Refined two-column serif design |

##  Tech Stack

- **HTML / CSS / Vanilla JavaScript** — single file, zero frameworks
- **[html2pdf.js](https://github.com/eKoopmans/html2pdf.js)** (via CDN) — client-side PDF generation
- **localStorage** — draft persistence

##  Project Structure

```
resumeforge/
└── resume-builder.html   # The entire app — HTML, CSS, and JS in one file
```

Inside the file:
- `<style>` — site UI styles + the 6 resume template designs (`.t-modern`, `.t-classic`, …)
- Three `.view` sections — landing page, template gallery, editor
- `<script>` — app state, sample resume data, form renderer, `renderResume()` (one branch per template), and `downloadPDF()`

##  Privacy

Everything runs client-side. Your resume data is stored only in your own browser's localStorage and is never uploaded anywhere.

##  Contributing

Contributions are welcome! Some ideas:

- New resume templates
- Extra sections (projects, certifications, references)
- Photo upload support
- Multi-page resume support
- More export formats (DOCX, plain text)

Fork the repo, make your changes, and open a pull request.

##  License

MIT — free to use, modify, and distribute.

---

Made by [Arpan](https://github.com/<arpandas90075>)
