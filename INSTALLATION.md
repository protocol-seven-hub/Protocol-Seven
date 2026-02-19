# Protocol Seven PWA - Installation Guide

This guide will help you deploy Protocol Seven as a Progressive Web App that users can install on their phones and computers.

---

## 📋 Prerequisites

- GitHub account (free)
- Your Protocol Seven PWA files (this folder)
- 10 minutes of your time

---

## 🚀 Step 1: Create GitHub Repository

### 1.1 Go to GitHub
- Visit https://github.com
- Log in to your account
- Click the **"+"** button in the top-right corner
- Select **"New repository"**

### 1.2 Configure Repository
- **Repository name:** `protocol-seven` (or whatever you want)
- **Description:** "Protocol Seven: Ascension Engine - Complete transformation system"
- **Visibility:** 
  - Choose **Public** (free, anyone can install)
  - Or **Private** (paid, only you control access)
- **Initialize:** Leave unchecked (we have files already)
- Click **"Create repository"**

---

## 📁 Step 2: Upload Your Files

### Option A: Upload via Web (Easiest)

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop **ALL** files from your `protocol-seven-pwa` folder:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - The entire `icons/` folder
3. Scroll down and click **"Commit changes"**

### Option B: Upload via Git (Advanced)

```bash
# Navigate to your protocol-seven-pwa folder
cd /path/to/protocol-seven-pwa

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Protocol Seven PWA"

# Connect to your GitHub repo (replace USERNAME and REPO)
git remote add origin https://github.com/USERNAME/protocol-seven.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## 🌐 Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Your URL will be:
```
https://YOUR-USERNAME.github.io/protocol-seven/
```

Example: `https://cedric.github.io/protocol-seven/`

---

## ✅ Step 4: Test the Installation

### On Desktop (Chrome/Edge):

1. Visit your GitHub Pages URL
2. Look for the **"Install"** button in the address bar (⊕ or ⬇ icon)
3. Click it
4. Confirm installation
5. **Protocol Seven opens in its own window!**
6. Check your Start Menu (Windows) or Applications (Mac) - it's there!

### On iPhone (Safari):

1. Visit your GitHub Pages URL
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Edit the name if you want
5. Tap **"Add"**
6. **Protocol Seven icon appears on home screen!**
7. Tap it - launches like a native app!

### On Android (Chrome):

1. Visit your GitHub Pages URL
2. Chrome shows **"Add to Home screen"** banner
3. Tap **"Install"** or **"Add"**
4. Confirm
5. **Protocol Seven icon on home screen!**
6. Tap - launches fullscreen!

---

## 🎨 Step 5: Customize Icons (Important!)

The current icons are placeholders. Create professional icons:

1. Follow instructions in `icons/ICON-GUIDE.md`
2. Create your icons (black background, green P7 logo)
3. Replace files in `icons/` folder:
   - `icon-192.png`
   - `icon-512.png`
   - `icon-maskable-512.png`
4. Upload to GitHub (commit and push)
5. Wait 1-2 minutes for update
6. Users will see your new icon!

---

## 🔧 Step 6: Update Your App

When you make changes:

1. Edit your local files
2. Upload to GitHub (replace old files)
3. Or use Git:
   ```bash
   git add .
   git commit -m "Updated features"
   git push
   ```
4. GitHub Pages updates automatically (1-2 minutes)
5. Users get update next time they open the app

---

## 🌍 Step 7: Share Your App

### Share the URL:
```
https://YOUR-USERNAME.github.io/protocol-seven/
```

### On Social Media:
```
🎯 Protocol Seven: Ascension Engine

Complete transformation system with:
✅ 6 mission types
✅ Dual progress tracking
✅ Offline support
✅ Install to home screen

Track your journey: [YOUR URL]
```

### QR Code (Optional):
1. Go to https://qr-code-generator.com
2. Enter your GitHub Pages URL
3. Download QR code
4. Share image - people scan and install!

---

## 🔒 Optional: Custom Domain

Want `protocolseven.com` instead of GitHub URL?

### Buy Domain ($10-15/year):
- Namecheap.com
- Google Domains
- GoDaddy

### Configure:
1. In your domain settings, add DNS records:
   ```
   Type: CNAME
   Name: www
   Value: YOUR-USERNAME.github.io
   ```
2. In GitHub repo settings → Pages:
   - Custom domain: `www.protocolseven.com`
   - Save
3. Wait 24 hours for DNS propagation
4. Your app is now at your custom domain!

---

## 🐛 Troubleshooting

### "Install button doesn't appear"
- Make sure you're using HTTPS (GitHub Pages is always HTTPS ✓)
- Clear browser cache and reload
- Try different browser
- Check manifest.json is accessible at `/manifest.json`

### "Icons don't show"
- Check file paths in manifest.json
- Icons must be in `/icons/` folder
- File names must match exactly (case-sensitive)
- Try hard refresh (Ctrl+Shift+R or Cmd+Shift+R)

### "App doesn't work offline"
- Service worker needs time to cache (first visit)
- Visit app once while online
- Close and reopen
- Should work offline now

### "Changes don't appear"
- GitHub Pages can take 1-2 minutes to update
- Clear browser cache
- Uninstall and reinstall app
- Check service-worker.js version number

---

## 📱 User Installation Instructions

Give these to your users:

### iPhone Users:
1. Open Safari
2. Go to [YOUR URL]
3. Tap Share button
4. "Add to Home Screen"
5. Tap the icon on your home screen to use!

### Android Users:
1. Open Chrome
2. Go to [YOUR URL]
3. Tap "Add to Home screen" banner
4. Or Menu → "Install app"
5. Tap the icon to launch!

### Desktop Users:
1. Open Chrome or Edge
2. Go to [YOUR URL]
3. Click Install button in address bar
4. Find in Start Menu/Applications
5. Launch like any program!

---

## ✨ What Users Can Do

✅ **Install to home screen** (looks like native app)
✅ **Works offline** (no internet needed after first load)
✅ **Fast loading** (cached locally)
✅ **Auto-updates** (when you push changes)
✅ **Full-screen mode** (no browser UI)
✅ **Push notifications** (optional, requires setup)

---

## 🎯 Next Steps

1. ✅ Deploy to GitHub Pages (follow steps above)
2. ✅ Test installation on your devices
3. ✅ Create professional icons
4. ✅ Share with friends/family for testing
5. ✅ Collect feedback
6. ✅ Launch publicly!

---

## 📞 Need Help?

- **GitHub Pages Docs:** https://pages.github.com
- **PWA Docs:** https://web.dev/progressive-web-apps
- **Test PWA:** https://www.pwabuilder.com (validates your PWA)

---

**You're ready to deploy! Follow the steps above and Protocol Seven will be installable on any device!** 🚀
