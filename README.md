# 🌸 afaf-maliha · Portfolio

> A VSCode-themed developer portfolio — because why should a portfolio look like everything else?

**[Live Site →](https://afafmaliha0716.github.io)** &nbsp; | &nbsp; **[UT Austin CS · Year 3](https://www.cs.utexas.edu)**

---

## ✦ Features

- **Night Pink dark theme** — based on the VSCode Night Pink extension, with a full light mode toggle
- **Command Palette** — `Ctrl+Shift+P` opens a real fuzzy-search file navigator (just like VSCode)
- **Keyboard shortcuts** — `Ctrl+1` through `Ctrl+5` to jump between sections
- **Interactive terminal** — type `ls`, `whoami`, `open projects`, `hook 'em`, and more
- **Problems panel** — accurate representation of my schedule
- **Rotating status bar** — updates every few seconds, like a real editor
- **Hover IntelliSense** — hover over code identifiers for tooltips
- **Zero dependencies** — pure HTML, CSS, and vanilla JS. No build step, no frameworks

## 📁 Portfolio Sections

| File | Contents |
|------|----------|
| `about.ts` | Bio, background, and what I'm working on |
| `projects.tsx` | Projects with GitHub + live links |
| `experience.tsx` | Internships and campus involvement |
| `skills.json` | Languages, frameworks, tools, product skills |
| `contact.ts` | Email, LinkedIn, GitHub, resume |

## 🚀 Deploying to GitHub Pages

This site deploys automatically via GitHub Pages — no CI/CD needed.

1. Create a repo named **`afafmaliha0716.github.io`** (must match your GitHub username exactly)
2. Push this code to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your site will be live at `https://afafmaliha0716.github.io` in ~60 seconds

**Updating the site:** just push a new commit. GitHub Pages redeploys automatically.

## 🛠 Local development

No build step needed. Just open `index.html` in your browser:

```bash
# Option 1: just open the file
open index.html

# Option 2: serve locally with Python
python3 -m http.server 3000
# then visit http://localhost:3000

# Option 3: VS Code Live Server extension → right-click index.html → Open with Live Server
```

## 🎨 Customizing

All content lives in `index.html`. Look for `[bracket]` placeholders:

- **About** → lines 8–13: update name, university details, currently working on
- **Projects** → search `proj-card` sections: fill in names, descriptions, GitHub/live links
- **Experience** → search `exp-card` sections: fill in company, role, dates, bullets
- **Contact** → update email, LinkedIn handle, resume PDF link
- **Status bar messages** → search `STATUSES` array near the bottom of the `<script>` tag
- **Terminal easter eggs** → search `RESPONSES` object to add your own commands

## 📸 Preview

![Portfolio Preview](preview.png)
<!-- Take a screenshot and save it as preview.png in this folder -->

---

<p align="center">
  Built with 💗 and way too much pink &nbsp;·&nbsp; 
  <a href="https://afafmaliha0716.github.io">afafmaliha0716.github.io</a>
</p>
