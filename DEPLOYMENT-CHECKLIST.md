# 🚀 Protocol Seven PWA - Deployment Checklist

Use this checklist to deploy your PWA to GitHub Pages.

---

## ✅ Pre-Deployment

- [ ] All files present in folder:
  - [ ] index.html
  - [ ] manifest.json
  - [ ] service-worker.js
  - [ ] icons/ folder with 3 PNG files
  - [ ] README.md
  - [ ] INSTALLATION.md

- [ ] (Optional) Replace placeholder icons with custom designs
  - [ ] See icons/ICON-GUIDE.md for instructions
  - [ ] Create icon-192.png
  - [ ] Create icon-512.png
  - [ ] Create icon-maskable-512.png

---

## 🌐 GitHub Setup

- [ ] Create GitHub account (if you don't have one)
- [ ] Create new repository:
  - [ ] Name it (e.g., "protocol-seven")
  - [ ] Make it Public (free) or Private (paid)
  - [ ] Don't initialize with README (we have our own)

- [ ] Upload files:
  - [ ] Drag and drop all files to GitHub
  - [ ] Or use Git command line (see INSTALLATION.md)
  - [ ] Commit with message: "Initial PWA deployment"

---

## 📄 Enable GitHub Pages

- [ ] Go to repository Settings
- [ ] Click "Pages" in left sidebar
- [ ] Under Source:
  - [ ] Select branch: main
  - [ ] Select folder: / (root)
  - [ ] Click Save

- [ ] Wait 1-2 minutes for deployment
- [ ] Note your URL: https://[username].github.io/[repo-name]/

---

## 🧪 Testing

### Desktop Testing (Chrome/Edge)
- [ ] Visit your GitHub Pages URL
- [ ] Check for Install button in address bar
- [ ] Click Install
- [ ] Confirm app opens in own window
- [ ] Check Start Menu/Applications for app icon
- [ ] Close and reopen - should load instantly
- [ ] Disconnect internet - app should still work

### Mobile Testing (iPhone)
- [ ] Open Safari on iPhone
- [ ] Visit your GitHub Pages URL
- [ ] Tap Share button
- [ ] Tap "Add to Home Screen"
- [ ] Name it and tap Add
- [ ] Find icon on home screen
- [ ] Tap to launch - should open fullscreen
- [ ] Test offline (airplane mode)

### Mobile Testing (Android)
- [ ] Open Chrome on Android
- [ ] Visit your GitHub Pages URL
- [ ] Look for "Add to Home screen" banner
- [ ] Tap Install/Add
- [ ] Find icon in app drawer
- [ ] Tap to launch - should open fullscreen
- [ ] Test offline (airplane mode)

---

## ✨ Post-Deployment

- [ ] Test all 6 mission types:
  - [ ] Financial Goal
  - [ ] Pay Off Debt
  - [ ] Lose Weight (with starting weight)
  - [ ] Overcome Lust
  - [ ] Sobriety
  - [ ] Faithfulness

- [ ] Test mission switching:
  - [ ] Switch from one mission to another
  - [ ] Confirm dialog appears
  - [ ] Verify progress saves
  - [ ] Switch back
  - [ ] Verify original progress restored

- [ ] Test dual tracking:
  - [ ] Log positive progress
  - [ ] Log negative progress
  - [ ] Verify calculations correct

- [ ] Complete The Mirror Protocol:
  - [ ] Answer all 5 questions
  - [ ] Review covenant

- [ ] Test habits and quests:
  - [ ] Add custom habit
  - [ ] Complete habit
  - [ ] Check XP gain
  - [ ] Create quest
  - [ ] Complete quest

- [ ] Test offline:
  - [ ] Disconnect internet
  - [ ] Use app normally
  - [ ] Reconnect
  - [ ] Verify data syncs

---

## 📢 Launch

- [ ] Share URL with testers/friends
- [ ] Create social media post
- [ ] (Optional) Create QR code for easy sharing
- [ ] (Optional) Set up custom domain
- [ ] Collect feedback
- [ ] Make improvements

---

## 🔄 Updates (When Needed)

- [ ] Edit local files
- [ ] Test changes locally
- [ ] Upload to GitHub (replace files)
- [ ] Wait 1-2 minutes
- [ ] Test deployed version
- [ ] Update service-worker.js cache version
- [ ] Notify users of updates

---

## 🎯 Success Criteria

Your PWA is successfully deployed if:

✅ Users can visit the URL in any browser  
✅ Install button appears (desktop/mobile)  
✅ App installs to home screen/applications  
✅ App launches in standalone mode (no browser UI)  
✅ App works offline after first visit  
✅ All missions save/load correctly  
✅ Data persists between sessions  
✅ Icons display properly on all devices  

---

## 📞 Help Resources

- **Detailed Guide:** See INSTALLATION.md
- **Icon Creation:** See icons/ICON-GUIDE.md  
- **GitHub Pages:** https://pages.github.com
- **PWA Testing:** https://www.pwabuilder.com
- **Manifest Validator:** https://manifest-validator.appspot.com

---

**You're ready! Check off each item as you go. Good luck! 🚀**
