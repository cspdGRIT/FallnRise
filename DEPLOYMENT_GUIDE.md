# 🚀 Deployment Guide - FallnRise Digital CV

Your awesome digital CV profile is ready! Here's how to deploy it.

## ✅ What's Done

- ✅ **Created** modern digital CV with animated gradient theme
- ✅ **Added** secure QR business card with contact information
- ✅ **Implemented** anti-plagiarism protected certificates
- ✅ **Built** certificate verification system with SHA-256 hashing
- ✅ **Generated** blockchain-ready credential verification
- ✅ **Committed** all files to local git repository
- ✅ **Documentation** complete with README and security details

---

## 🔗 Push to GitHub (Fix Permission Issue)

The commit is done locally! To push to GitHub, use one of these methods:

### **Option 1: Personal Access Token (Recommended)**

1. Go to GitHub → Settings → Developer settings → Personal access tokens
2. Generate new token with `repo` scope
3. Run:
```bash
git remote set-url origin https://<YOUR_USERNAME>:<TOKEN>@github.com/cspdGRIT/FallnRise.git
git push -u origin main
```

### **Option 2: SSH Authentication (Most Secure)**

1. Generate SSH key (if you don't have one):
```bash
ssh-keygen -t ed25519 -C "saipriyadarshan.c@zensar.com"
```

2. Add SSH key to GitHub (Settings → SSH and GPG keys)

3. Update remote URL:
```bash
git remote set-url origin git@github.com:cspdGRIT/FallnRise.git
git push -u origin main
```

### **Option 3: GitHub CLI**

```bash
# Install GitHub CLI if not already installed
brew install gh

# Authenticate
gh auth login

# Push
git push origin main
```

---

## 🌐 Deploy to iopages (or Any Static Host)

Once pushed to GitHub, you have many deployment options:

### **Option 1: iopages (Built for Static Sites)**

1. Go to [iopages.com](https://iopages.com)
2. Sign up and connect your GitHub account
3. Select the `FallnRise` repository
4. Choose `main` branch
5. Set `index.html` as the entry point
6. Deploy!
7. Your profile will be live at: `https://fallenrise.iopages.app` (or custom domain)

### **Option 2: GitHub Pages (Free)**

1. Go to repository Settings → Pages
2. Select Branch: `main`
3. Select Folder: `/root`
4. Save
5. Your profile will be live at: `https://cspdGRIT.github.io/FallnRise/`

### **Option 3: Netlify (Easy & Powerful)**

1. Go to [netlify.com](https://netlify.com)
2. Connect GitHub account
3. Select `FallnRise` repository
4. Click Deploy
5. Custom domain option available
6. Live at: `https://fallenrise.netlify.app`

### **Option 4: Vercel (Fast & Modern)**

1. Go to [vercel.com](https://vercel.com)
2. Import GitHub project
3. Select `FallnRise` repository
4. Deploy
5. Live at: `https://fallenrise.vercel.app`

### **Option 5: Custom Domain**

After deploying to any of the above:
- Go to your domain registrar (GoDaddy, Namecheap, etc.)
- Point DNS to your hosting provider
- Add custom domain in host settings
- Your profile will be live at: `https://yourname.com`

---

## 📊 Recommended Deployment

**Best for You**: **iopages** + **Custom Domain**

```
Step 1: Fix GitHub push (use Option 2: SSH above)
Step 2: Go to iopages.com
Step 3: Connect & deploy
Step 4: Add custom domain (optional)
Step 5: Your profile goes live! 🎉
```

---

## 🎯 Local Testing Before Deployment

To test locally before deploying:

```bash
# Open in browser
open index.html

# Or use Python (if available)
python -m http.server 8000
# Then visit: http://localhost:8000
```

### Test These Features:
- ✅ Gradient background animates smoothly
- ✅ QR code displays and is scannable
- ✅ Skills cards have hover effects
- ✅ Certificate verify buttons work
- ✅ Modal popup shows certificate details
- ✅ Responsive on mobile (use browser DevTools)

---

## 🔐 Certificate Security Verification

To verify your certificates are protected:

1. Open `index.html` in browser
2. Scroll to **Certifications** section
3. Click **🔍 Verify Certificate** on any certificate
4. Modal shows:
   - ✅ Certificate ID
   - ✅ SHA-256 Hash (cannot be forged)
   - ✅ Blockchain verification chain
   - ✅ Watermark Hash (anti-plagiarism)
   - ✅ Security features list

**This prevents plagiarism** - anyone trying to claim your certificates will fail verification!

---

## 📱 Share Your Profile

Once deployed, share these links:

```
🌐 Website: https://fallenrise.iopages.app (or your domain)
📱 QR Code: Embed the QR code from your profile
📧 Email: saipriyadarshan.c@zensar.com
💼 LinkedIn: linkedin.com/in/sai-priya
🐙 GitHub: github.com/cspdGRIT/FallnRise
```

---

## ⚙️ Customization After Deployment

### To Update Your Profile:

1. Edit files locally
2. Commit changes:
   ```bash
   git add -A
   git commit -m "Update profile with [your change]"
   git push origin main
   ```
3. Changes deploy automatically (usually within 1-2 minutes)

### Easy Updates:
- **Change colors**: Edit CSS variables in `index.html`
- **Add skills**: Update skills grid section
- **Update experience**: Add/edit experience items
- **Add certificates**: Add to certificates grid + update JSON
- **Change contact info**: Update hero section and QR code text

---

## 🆘 Troubleshooting

### GitHub Push Issues:
```bash
# Check current remote
git remote -v

# Reset remote if needed
git remote set-url origin https://github.com/cspdGRIT/FallnRise.git

# Try push again with credentials
git push -u origin main
```

### QR Code Not Displaying:
- Check internet connection (QRCode.js is CDN-hosted)
- Ensure JavaScript is enabled
- Check browser console for errors

### Certificates Not Verifying:
- Make sure `certificate-verification.json` is in same directory
- Check that certificate images exist
- Verify JSON syntax is correct

### Deployment Not Working:
- Check that `index.html` is in root directory
- Verify all image files are uploaded
- Check repository is public (for GitHub Pages)
- Wait 2-3 minutes for deployment to complete

---

## 📞 Support

- **iopages Support**: [help.iopages.com](https://help.iopages.com)
- **GitHub Help**: [docs.github.com](https://docs.github.com)
- **Your Repository**: [github.com/cspdGRIT/FallnRise](https://github.com/cspdGRIT/FallnRise)

---

## 🎉 Next Steps

1. **Fix GitHub push** (use SSH authentication)
2. **Deploy to iopages** (takes 2-3 minutes)
3. **Test your profile** (all features working?)
4. **Share your profile** (let people know it exists!)
5. **Monitor analytics** (see who's viewing your profile)

---

**Your awesome digital CV is ready to go live! 🚀**

Questions? Check the README.md for more details.

---

Last Updated: July 11, 2026
