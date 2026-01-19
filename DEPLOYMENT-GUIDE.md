# 🚀 QUICK DEPLOYMENT CHECKLIST

## Before You Upload

✅ All files are ready to upload
✅ Logo has transparent background
✅ SEO tags are in place
✅ All pages are linked correctly

---

## Upload to GitHub (5 minutes)

1. **Go to your repository:** https://github.com/bbenias/daves-website

2. **Upload all files:**
   - Click "Add file" > "Upload files"
   - Drag the entire `daves-website` folder contents
   - Make sure to maintain the folder structure:
     - All HTML files in root
     - CSS folder with styles.css
     - Images folder with logo.png

3. **Commit changes:**
   - Add commit message: "Initial website upload"
   - Click "Commit changes"

---

## Enable GitHub Pages (2 minutes)

1. **Go to Settings** (in your repository)

2. **Click "Pages"** (left sidebar)

3. **Configure source:**
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

4. **Wait 1-2 minutes** for deployment

5. **Your site is live at:**
   ```
   https://bbenias.github.io/daves-website/
   ```

---

## After Deployment

### Immediately:
- [ ] Visit the live site and test all pages
- [ ] Check that logo displays correctly
- [ ] Test navigation links
- [ ] Verify mobile responsiveness

### Within 24 Hours:
- [ ] Set up Formspree for contact form
- [ ] Update contact form with your Formspree ID
- [ ] Test contact form submission

### Optional Improvements:
- [ ] Add Open Graph images for social sharing
- [ ] Set up Google Analytics
- [ ] Submit sitemap to Google Search Console
- [ ] Add actual project photos to Projects page

---

## Contact Form Setup

1. Go to: https://formspree.io/register
2. Create free account
3. Create new form
4. Copy your form ID (looks like: `xxxYYYzzz123`)
5. Edit `contact.html` line 55:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
6. Replace `YOUR_FORM_ID` with your actual ID
7. Commit and push the change

---

## Testing Checklist

After site is live, test:
- [ ] Home page loads correctly
- [ ] All navigation links work
- [ ] Logo is visible and clear
- [ ] Mobile menu works on phone
- [ ] Contact form loads (even if not functional yet)
- [ ] Page titles show correctly in browser tab
- [ ] Footer information is correct

---

## Common Issues & Fixes

**Logo not showing:**
- File must be at: `images/logo.png`
- Check capitalization (must be lowercase)

**CSS not loading:**
- File must be at: `css/styles.css`
- Check that HTML files reference it correctly

**404 Error:**
- Make sure files are in root of repository
- Not in a subfolder like `docs/` unless configured

---

**You're ready to go! 🎉**

Once uploaded, your professional website will be live and searchable on Google within days.
