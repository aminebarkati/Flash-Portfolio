# ⚡ Flash Portfolio

A **single-file portfolio builder** — customize every section live, export your portfolio as HTML or a PDF resume, and deploy in under a minute. No build step, no dependencies, no backend.

**[→ Live Demo](https://yourname.github.io/flash-portfolio)**

---

## 🎨 Themes

8 built-in presets, all fully customizable via color pickers:

| Name | Feel |
|------|------|
| **Gold Dark** | Dark background, warm gold accents — the default |
| **Ocean** | Deep navy with electric blue |
| **Forest** | Dark green with emerald highlights |
| **Rose** | Deep red tones with pink accents |
| **Slate** | Dark blue-grey with soft violet |
| **Amber** | Near-black with amber/yellow |
| **Minimal** | Clean white, black accents |
| **Cyber** | Pitch black with neon teal |

---

## 🛠 How to Use

Flash Portfolio is hosted at **[yourname.github.io/flash-portfolio](https://yourname.github.io/flash-portfolio)**.

Open it in your browser and click the **✏️** button (bottom-right) to open the Customizer panel.

### Theme tab
- Pick a color preset or fine-tune individual colors with the color pickers
- Switch body font and corner radius
- Enable **Click-to-Edit** to click any text directly on the page and type over it — including the large background initials in the hero

### Sections tab
- **Reorder** sections by dragging
- **Rename** section labels by clicking the name inline
- **Toggle** visibility with the switch
- **Clone** a section with ⧉ to duplicate it
- **Delete** a section with ✕

### Content tab
Full add / edit / delete for every data-driven section:
- **Skills** — category name + comma-separated tags
- **Experience** — date, title, organisation, bullet points (EN + FR)
- **Education** — same structure as Experience
- **Projects** — name, year, description, tech stack, optional link
- **Life Events** — date, title, description, emoji icon, optional photo upload
- **Languages** — name, level label, proficiency %
- **Contact** — icon, label, display value, href

### Export tab
| Action | What it does |
|--------|-------------|
| **⬆ Import HTML** | Re-open any previously exported Flash Portfolio file to keep editing |
| **⬇ Download HTML** | Save your portfolio as a clean, self-contained HTML file |
| **📄 Export Resume PDF** | Generates a print-ready A4 resume from your data and opens the print dialog |

---

## 🚀 Deploy Your Own Portfolio

Once you're happy with your content:

1. Go to the **Export tab** → click **⬇ Download HTML**
2. Rename the downloaded file to `index.html`
3. Deploy using any of the options below — all are free

### Netlify Drop *(fastest — no account needed)*
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `index.html`
3. Your portfolio is live instantly at a `*.netlify.app` URL

### GitHub Pages
```bash
git init
git add index.html
git commit -m "my portfolio"
git remote add origin https://github.com/yourname/yourrepo.git
git push -u origin main
```
Then: **Repo Settings → Pages → Deploy from branch → main → Save**

Your portfolio goes live at `https://yourname.github.io/yourrepo`

### Vercel / Cloudflare Pages
Connect your GitHub repo — both platforms auto-detect a single HTML file and deploy with zero configuration.

> **Tip:** The exported file is fully self-contained. Keep a copy so you can re-import and edit it later.

---

## 📁 Project Structure

```
flash-portfolio.html   ← the entire app — HTML, CSS, and JS in one file
README.md
```

The whole tool ships as a single HTML file. There is no framework, no bundler, no package.json. Everything — the portfolio viewer, the customizer panel, all themes, all CRUD logic — lives in that one file.
