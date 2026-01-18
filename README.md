# Maurice Labs Website

Landing page for [mauricelabs.ai](https://mauricelabs.ai)

## Quick Deploy to GitHub Pages

1. Create a new repository named `mauricelabs.github.io` (or any name)

2. Push this code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/mauricelabs.github.io.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repository **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. Your site will be live at `https://YOUR_USERNAME.github.io/mauricelabs.github.io/`

## Custom Domain Setup

To use `mauricelabs.ai`:

1. Add a `CNAME` file to the repo containing:
   ```
   mauricelabs.ai
   ```

2. Configure DNS with your registrar:
   - Add an `A` record pointing to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Or add a `CNAME` record: `YOUR_USERNAME.github.io`

3. In GitHub repo settings → Pages → Custom domain, enter `mauricelabs.ai`

4. Enable "Enforce HTTPS"

## Structure

```
/
├── index.html      # Single-page site (all HTML/CSS/JS inline)
├── CNAME           # Custom domain config (add after setup)
└── README.md       # This file
```

## Local Preview

Just open `index.html` in a browser — no build step required.

---

*Maurice Labs — Local-First Agentic AI*
