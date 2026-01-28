# Rosette Dizon Portfolio - GitHub Pages Deployment

## ✅ What's Ready
- ✅ index.html with all content
- ✅ styles.css with star ratings
- ✅ images/ folder with 28 images
- ✅ All testimonials updated with 5-star ratings
- ✅ Name corrected (Rosette not Rosette)
- ✅ Client titles added

## 📁 Folder Structure
```
portfolio-github/
├── index.html        (main portfolio page)
├── styles.css        (all styles including star ratings)
├── images/           (28 PNG images)
│   ├── tracking_sample.png
│   ├── ghl_campaign_2.png
│   ├── meetings_spreadsheet.png
│   └── ... (25 more images)
└── README.md         (this file)
```

## 🚀 How to Deploy to GitHub Pages

### Step 1: Download the portfolio-github folder
Download the entire `portfolio-github` folder to your computer.

### Step 2: Create a GitHub Repository
1. Go to https://github.com and log in
2. Click "New" repository
3. Name it: `rosette-dizon-portfolio` (or any name you want)
4. Make it **Public**
5. Click "Create repository"

### Step 3: Upload Files
**Option A: Via GitHub Website (Easiest)**
1. Click "uploading an existing file"
2. Drag and drop ALL files:
   - index.html
   - styles.css
   - the entire `images` folder
3. Click "Commit changes"

**Option B: Via Git Command Line**
```bash
cd portfolio-github
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes

### Step 5: Visit Your Portfolio!
Your portfolio will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## 🔧 Making Changes

### To Edit Text:
1. Open `index.html` in a text editor
2. Find the section you want to edit
3. Change the text (keep HTML tags intact)
4. Save and re-upload to GitHub

### To Add/Change Images:
1. Replace image files in the `images/` folder
2. Keep the same filenames OR
3. Update the `<img src="images/YOUR-IMAGE.png">` tags in index.html

### To Change Colors:
1. Open `styles.css`
2. Find `:root {` at the top
3. Change the color values:
   - `--primary` (dark blue background)
   - `--accent` (pink/red highlights)
   - `--light` (text color)

## ✨ Features Included
- ✅ 4 testimonials with 5-star ratings
- ✅ 28 work sample images
- ✅ Responsive design (works on phone, tablet, desktop)
- ✅ Smooth animations
- ✅ Professional color scheme
- ✅ All client names properly handled

## 🐛 Troubleshooting

**Images not showing?**
- Make sure the `images/` folder is in the same directory as `index.html`
- Check that image filenames match exactly (case-sensitive)

**Page looks broken?**
- Make sure `styles.css` is uploaded
- Check browser console for errors (F12)

**Changes not showing?**
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait a few minutes for GitHub Pages to update

## 📧 Need Help?
Contact: RFD1222@GMAIL.COM
