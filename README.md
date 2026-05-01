# DSN Free AI Classes 2026 — Participant Onboarding Site

A static onboarding website for the **Data Science Nigeria (DSN) Free AI Classes 2026** programme. Hosted on GitHub Pages.

## 🌐 Live Site
> After deploying, your site will be at:
> `https://<your-github-username>.github.io/dsn-free-ai-classes-2026/`

---

## 📁 File Structure
```
dsn-free-ai-classes-2026/
├── index.html    # Main onboarding page
├── style.css     # All styles (DSN brand colours)
├── main.js       # Scroll animations & nav behaviour
└── README.md     # This file
```

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** button → **"New repository"**
3. Name it: `dsn-free-ai-classes-2026`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload the Files
**Option A — Upload via GitHub website (easiest):**
1. Open your new repository
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop all 4 files (`index.html`, `style.css`, `main.js`, `README.md`)
4. Scroll down and click **"Commit changes"**

**Option B — Using Git on your computer:**
```bash
git clone https://github.com/<your-username>/dsn-free-ai-classes-2026.git
cd dsn-free-ai-classes-2026
# copy your files here, then:
git add .
git commit -m "Initial commit: DSN Free AI Classes 2026 onboarding site"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Branch"**, select **`main`** and folder **`/ (root)`**
4. Click **"Save"**
5. Wait 1–2 minutes, then visit:
   `https://<your-github-username>.github.io/dsn-free-ai-classes-2026/`

---

## ✏️ Customisation

### Update the Submission Form Link
In `index.html`, find this line and replace `#` with your actual Google Form or Typeform URL:
```html
<a href="#" class="btn btn-primary btn-large" id="submitFormBtn">
```

### Update Contact Email
Search for `freeaiclasses@datasciencenigeria.org` in `index.html` and replace with the correct email.

### Update Platform URLs
All platform links are in `index.html` in the `<a href="...">` tags inside each track and platform guide section.

---

## 🎨 Brand Colours
| Colour | Hex |
|--------|-----|
| DSN Green | `#00A86B` |
| DSN Dark Navy | `#0A2240` |
| DSN Gold | `#F5A623` |

---

## 📬 Contact
- Website: [datasciencenigeria.org](https://datasciencenigeria.org)
- Twitter: [@dsnailive](https://twitter.com/dsnailive)
- Email: freeaiclasses@datasciencenigeria.org
