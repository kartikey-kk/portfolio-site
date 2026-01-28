# Portfolio — Kartikey Kumar

A clean, minimal portfolio site focused on **Data Science**, **Machine Learning**, and **Cloud (AWS)**. Recruiter-friendly, no frameworks — HTML and CSS only.

## Tech stack

- **HTML5** — semantic structure, accessible markup
- **CSS3** — custom properties, grid, flexbox, responsive layout, print styles
- **No frameworks** — no React, Bootstrap, or JS libraries
- **Font** — [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Google Fonts)

## Sections

| Section | Description |
|--------|-------------|
| **Hero** | Name, tagline, primary CTA |
| **About** | Bio, education, current role, certifications, achievements |
| **Focus areas** | Learning priorities: GenAI systems, Agentic AI, practical engineering |
| **Skills** | Data Science & languages, ML & AI, tools & cloud |
| **Projects** | Hostel Management, Netflix Analysis, Loan Default Prediction, Customer Behavior, DriveAware, Disease Outcome Prediction |
| **Experience** | Internship, education, leadership (Void Society, CoE) |
| **Contact** | Email, phone, LinkedIn, GitHub |

## How to run locally

1. **Open in browser**  
   Double-click `index.html` or drag it into a browser. Works offline after first load (Google Fonts may need network once).

2. **Local server (optional)**  
   To avoid `file://` restrictions (e.g. for future JS or CORS), serve the folder:
   ```bash
   # Python 3
   python -m http.server 8080

   # Node (npx)
   npx serve .

   # Then open http://localhost:8080
   ```

## Deploy on Vercel

1. **Push to GitHub**  
   Create a repo and push this folder (e.g. `portfolio` or `Portfolio-Website`).

2. **Connect to Vercel**  
   - Go to [vercel.com](https://vercel.com) and sign in (GitHub recommended).  
   - **Add New → Project** → import your GitHub repo.  
   - Vercel will detect the static site; leave **Build Command** empty, **Output Directory** as `.` (or use defaults).  
   - Click **Deploy**.  
   - Your site will be live at `https://your-project.vercel.app`.

3. **Deploy from CLI (optional)**  
   From the project folder:
   ```bash
   npx vercel
   ```
   Follow the prompts (login, project name). Use `npx vercel --prod` for production.

The repo includes `vercel.json` so Vercel treats it as a static site with no build step.

## Project structure

```
Portfolio Website/
├── index.html    # Single-page content & structure
├── styles.css    # Layout, typography, components, responsive & print
├── resume.pdf   # Your resume — visitors can download (name it resume.pdf)
├── vercel.json  # Vercel config (static, no build)
└── README.md    # This file
```

## Customization

- **Content** — Edit `index.html`: replace text, project links, contact details.
- **Resume** — Put your resume PDF in this folder and name it `resume.pdf`. The nav “Resume”, hero “Download Resume”, and contact “Download PDF” links all point to it. Downloaded filename will be `Kartikey_Kumar_Resume.pdf`.
- **Theme** — In `styles.css`, change `:root` variables (`--color-accent`, `--color-bg`, etc.).
- **Print** — Print or “Save as PDF” uses built-in print styles (simplified layout, URLs shown).

## License

Use and modify as you like. Credit optional.
