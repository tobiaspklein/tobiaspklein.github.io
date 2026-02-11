# Tobias Klein - Portfolio Website

Modern, responsive portfolio website showcasing content creation and digital marketing work.

## 🚀 How to Deploy to GitHub Pages (FREE!)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create your free account
3. Choose username carefully - it will be in your URL (e.g., `tobiaskl.github.io`)

### Step 2: Create a New Repository
1. Click the "+" icon in top right → "New repository"
2. Name it EXACTLY: `yourusername.github.io` (replace with your GitHub username)
   - Example: if your username is `tobiaskl`, name it `tobiaskl.github.io`
3. Make it **Public**
4. Click "Create repository"

### Step 3: Upload Your Files
There are 2 ways to upload:

#### Option A: Drag & Drop (Easiest)
1. Click "uploading an existing file"
2. Drag ALL the files from your portfolio folder into the browser
   - `index.html`
   - `assets` folder (with all images inside)
3. Scroll down and click "Commit changes"

#### Option B: Using GitHub Desktop (Recommended for Updates)
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your repository
3. Copy all portfolio files into the folder
4. Commit and push changes

### Step 4: Enable GitHub Pages
1. Go to your repository → Settings
2. Scroll to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes

### Step 5: Visit Your Website! 🎉
Your portfolio will be live at:
```
https://yourusername.github.io
```

Example: `https://tobiaskl.github.io`

---

## 📁 File Structure
```
portfolio/
├── index.html          # Main website file
└── assets/
    └── images/         # All your project images
        ├── foto_perfil.jpg
        ├── Bullish_bears_ordinal.png
        ├── Canon_Printer_Rebates__Randmar_flyers_.png
        ├── Youtube_Thumbnail__Randmar_.png
        └── Confeitaria_básica.png
```

---

## 🎨 Customization

### Change Colors
Open `index.html` and find the `:root` section (around line 20):
```css
:root {
    --black: #0a0a0a;
    --white: #fafafa;
    --accent: #4a9d7f;  /* Change this for different accent color */
}
```

### Update Content
1. Open `index.html` in any text editor
2. Find the section you want to edit (search for section names like `<!-- Hero Section -->`)
3. Change the text directly
4. Save and re-upload to GitHub

### Add/Remove Projects
1. Find the `<!-- Projects Section -->` in `index.html`
2. Copy a `<div class="project-card">` block
3. Paste and edit the content
4. Add new images to `assets/images/` folder

---

## 📱 Features
- ✅ Fully responsive (looks great on phones, tablets, desktops)
- ✅ Modern, clean design with neutral colors
- ✅ Smooth animations and hover effects
- ✅ SEO-friendly structure
- ✅ Fast loading
- ✅ No JavaScript frameworks needed

---

## 🔧 Troubleshooting

**Website not showing up?**
- Wait 2-5 minutes after enabling GitHub Pages
- Make sure repository name is `username.github.io`
- Check that `index.html` is in the root folder (not in a subfolder)

**Images not loading?**
- Make sure `assets/images/` folder structure is correct
- Check that image filenames in `index.html` match actual files (case-sensitive!)

**Want to use a custom domain?**
- You can connect your own domain (like `tobiasklein.com`) later
- GitHub has [instructions here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 📧 Support
If you need help:
1. Check [GitHub Pages documentation](https://pages.github.com/)
2. Google your specific error message
3. Ask in [GitHub Community](https://github.community/)

---

## 🎯 Next Steps
1. Update your LinkedIn to include your new portfolio link
2. Add the link to your email signature
3. Share it when applying for jobs!

**Good luck! 🚀**
