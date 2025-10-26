# Legal Documents - GitHub Pages Setup

## 🚨 REQUIRED FOR APP STORE SUBMISSION

These legal documents are **mandatory** for Apple App Store approval.

---

## 📋 Setup Instructions (5 minutes)

### Step 1: Create GitHub Repository

1. Go to https://github.com
2. Click **"New repository"** (green button)
3. **Repository name:** `clickandclean-legal`
4. **Public** (must be public for GitHub Pages)
5. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Web Upload (Easiest)**

1. In your new repo, click **"uploading an existing file"**
2. Drag and drop these 3 files:
   - `privacy.html`
   - `terms.html`
   - `support.html`
3. Click **"Commit changes"**

**Option B: Command Line**

```bash
cd /path/to/this/legal-docs/folder
git init
git add .
git commit -m "Add legal documents"
git remote add origin https://github.com/YOUR_USERNAME/clickandclean-legal.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repo, click **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select **"main"** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Get Your URLs

Your documents will be live at:
- **Privacy:** `https://YOUR_USERNAME.github.io/clickandclean-legal/privacy.html`
- **Terms:** `https://YOUR_USERNAME.github.io/clickandclean-legal/terms.html`
- **Support:** `https://YOUR_USERNAME.github.io/clickandclean-legal/support.html`

### Step 5: Test URLs

**CRITICAL:** Open each URL in your browser to verify they load correctly!

---

## ✅ After Setup

Once URLs are live, you need to add them to:

1. **App Store Connect** (when creating app listing)
2. **Xcode project** (if referenced in code)

---

## 📝 What's Included

### privacy.html
- GDPR/AVG compliant privacy policy
- Covers data collection, usage, sharing
- User rights and security measures
- Required by EU law

### terms.html
- Terms of Service for marketplace
- User responsibilities
- Payment terms and fees
- Cancellation policy
- Liability disclaimers

### support.html
- Contact information
- FAQ section
- In-app support instructions
- Safety reporting

---

## 🔧 Customization (Optional)

Before or after uploading, you can customize:

1. **Email addresses** - Replace placeholders with real ones:
   - `support@clickandclean.app`
   - `privacy@clickandclean.app`
   - `safety@clickandclean.app`
   - `feedback@clickandclean.app`

2. **Company details** - If you have a registered company name

3. **Styling** - The CSS is inline and can be modified

---

## ⚠️ Important Notes

- **Do NOT delete these files** - Apple checks these URLs during review
- **Keep URLs stable** - Changing them requires app update
- **Review content** - Make sure you're comfortable with all terms
- **Real email** - Eventually replace with a real support email

---

## 🆘 Troubleshooting

**URLs not working?**
- Wait 2-3 minutes after enabling Pages
- Check repo is **public**
- Verify file names are exactly: `privacy.html`, `terms.html`, `support.html`

**Need to update content?**
- Just edit files and commit changes
- GitHub Pages auto-updates in 1-2 minutes

---

## Next Steps

After URLs are live:
1. ✅ Test all three URLs in browser
2. ✅ Copy URLs somewhere safe
3. ✅ Continue with App Store submission
4. ✅ You'll paste these URLs into App Store Connect

**Your legal documents are production-ready and compliant!**

