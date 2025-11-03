# UnderText - GitHub Pages Setup

This folder contains the HTML files for UnderText's privacy policy, terms of use, and support pages that will be hosted on GitHub Pages for App Store submission.

## Files Created

- `index.html` - Landing page with links to all documents
- `privacy.html` - Complete privacy policy
- `terms.html` - Terms of use and subscription details
- `support.html` - Support page with FAQs and contact info

## Setup Instructions

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the "+" icon in the top right > "New repository"
3. Repository settings:
   - **Name:** `UnderText` (or any name you prefer)
   - **Description:** "Privacy policy and legal documents for UnderText app"
   - **Public** (must be public for GitHub Pages)
   - Check "Add a README file"
4. Click "Create repository"

### Step 2: Upload Files to GitHub

**Option A: Upload via GitHub Web Interface (Easiest)**

1. In your new repository, click "Add file" > "Upload files"
2. Drag and drop all 4 HTML files:
   - `index.html`
   - `privacy.html`
   - `terms.html`
   - `support.html`
3. Add commit message: "Add privacy policy and legal documents"
4. Click "Commit changes"

**Option B: Upload via Git Command Line**

```bash
# Navigate to the docs folder
cd "/Users/toni/Keyboard app/SnapKey/docs"

# Initialize git (if not already in a git repo)
git init

# Add GitHub repository as remote
git remote add origin https://github.com/xntuan/UnderText.git

# Add all HTML files
git add index.html privacy.html terms.html support.html

# Commit
git commit -m "Add privacy policy and legal documents"

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your GitHub repository, click "Settings" (top menu)
2. In the left sidebar, scroll down and click "Pages"
3. Under "Source", select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click "Save"
5. Wait 1-2 minutes for deployment
6. GitHub will show your site URL: `https://xntuan.github.io/UnderText/`

### Step 4: Get Your Public URLs

After GitHub Pages is deployed, your URLs will be:

- **Privacy Policy:** `https://xntuan.github.io/UnderText/privacy.html`
- **Terms of Use:** `https://xntuan.github.io/UnderText/terms.html`
- **Support URL:** `https://xntuan.github.io/UnderText/support.html`
- **Landing Page:** `https://xntuan.github.io/UnderText/`

### Step 5: Test Your URLs

1. Click on each URL to make sure they load correctly
2. Check that all internal links work
3. Test on mobile Safari to ensure formatting looks good

### Step 6: Add URLs to App Store Connect

Once your subscription is approved (1-2 days), you'll add these URLs when submitting your app:

1. **Privacy Policy URL:** Use the privacy.html URL
2. **Support URL:** Use the support.html URL (or index.html)
3. **Marketing URL (optional):** Use the index.html URL

## Updating Documents

If you need to update the privacy policy or terms later:

1. Edit the HTML files locally
2. Upload the updated files to GitHub (same process as Step 2)
3. Changes will be live within 1-2 minutes
4. No need to update App Store Connect - the URL stays the same!

## Important Notes

- ✅ Repository MUST be public for GitHub Pages to work
- ✅ Keep the exact file names (`privacy.html`, `terms.html`, etc.)
- ✅ Test all URLs before submitting to App Store
- ✅ Make sure your GitHub username is professional (it will be in the URL)

## Need Help?

If you have issues setting up GitHub Pages:
- GitHub Pages docs: https://pages.github.com/
- Check that repository is public
- Wait 5-10 minutes for initial deployment
- Clear browser cache if changes don't appear

---

**Next Step:** Once you have your public URLs, you're ready to submit to App Store Connect!
