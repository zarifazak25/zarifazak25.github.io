# Multi-Page Personal Website Template

**Simple multi-page website with clear comments showing exactly what to change!**

---

## 📁 What's Included

**5 HTML Pages:**
- `index.html` - Home page (your introduction)
- `about_me.html` - About you (3 sections)
- `portfolio.html` - All your portfolio work (4 categories, 12 projects)
- `contact.html` - Your contact information
- `style.css` - One CSS file for all pages

**Navigation works automatically** - all pages link to each other!

---

## 🚀 Quick Setup

### Step 1: Upload to GitHub
1. Create GitHub account at [github.com](https://github.com)
2. Create repository named: `your-username.github.io`
3. Upload all 5 files (4 HTML + 1 CSS)
4. Enable GitHub Pages in Settings → Pages

### Step 2: Create Image Folders
1. Create `images` folder in your repository
2. Create `files` folder for your CV

### Step 3: Upload Images
**You need 16 images total** - see list below

### Step 4: Edit Content
**All changes are clearly marked with comments like:**
```html
<!-- CHANGE: Replace this with your information -->
```

Just search for "CHANGE" in each HTML file!

---

## 📸 Images You Need (16 Total)

### Main Images (4 files):
1. **profile_photo.jpg** - 800x800px (square) - Your headshot
2. **about_professional.jpg** - 1200x800px (landscape) - Work photo
3. **about_goals.jpg** - 1200x800px (landscape) - Career goals
4. **about_interests.jpg** - 1200x800px (landscape) - Hobbies

### Portfolio Project Images (12 files):
**Course Development (3):**
5. **course_dev_project_1.jpg** - 1200x800px
6. **course_dev_project_2.jpg** - 1200x800px
7. **course_dev_project_3.jpg** - 1200x800px

**Product Development (3):**
8. **product_dev_project_1.jpg** - 1200x800px
9. **product_dev_project_2.jpg** - 1200x800px
10. **product_dev_project_3.jpg** - 1200x800px

**UX Research (3):**
11. **ux_research_project_1.jpg** - 1200x800px
12. **ux_research_project_2.jpg** - 1200x800px
13. **ux_research_project_3.jpg** - 1200x800px

**Data Visualization (3):**
14. **data_viz_project_1.jpg** - 1200x800px
15. **data_viz_project_2.jpg** - 1200x800px
16. **data_viz_project_3.jpg** - 1200x800px

**All images must be .jpg or .png format!**

---

## ✏️ What to Edit in Each File

### index.html (Home Page)
**Search for "CHANGE" and replace:**
- Your Name (3 places)
- Professional title
- Introduction paragraph (2-3 sentences)

### about_me.html
**Search for "CHANGE" and replace:**
- Your Name (2 places)
- Professional Background paragraph
- Career Goals paragraph
- Personal Interests paragraph

### portfolio.html
**Search for "CHANGE" and replace:**
- Your Name (2 places)
- 4 category descriptions (Course Dev, Product Dev, UX Research, Data Viz)
- 12 project titles
- 12 project dates/contexts
- 12 project descriptions
- 12 sets of tags

**That's 12 projects total - 3 per category!**

### contact.html
**Search for "CHANGE" and replace:**
- Your Name (2 places)
- Email address (2 places)
- LinkedIn URL (2 places)
- GitHub URL (2 places)
- Other link (optional)

### style.css (Optional)
**To change colors:**
Find this section at the top:
```css
:root {
    --primary-color: #2563eb;      /* Main color */
    --primary-dark: #1e40af;       /* Darker shade */
}
```
Use [coolors.co](https://coolors.co) to find color codes!

---

## 📂 Final Folder Structure

```
your-username.github.io/
│
├── index.html              ← Home page
├── about_me.html           ← About page
├── portfolio.html          ← Portfolio page
├── contact.html            ← Contact page
├── style.css               ← Styling
│
├── images/                 ← Create this folder
│   ├── profile_photo.jpg
│   ├── about_professional.jpg
│   ├── about_goals.jpg
│   ├── about_interests.jpg
│   ├── course_dev_project_1.jpg
│   ├── course_dev_project_2.jpg
│   ├── course_dev_project_3.jpg
│   ├── product_dev_project_1.jpg
│   ├── product_dev_project_2.jpg
│   ├── product_dev_project_3.jpg
│   ├── ux_research_project_1.jpg
│   ├── ux_research_project_2.jpg
│   ├── ux_research_project_3.jpg
│   ├── data_viz_project_1.jpg
│   ├── data_viz_project_2.jpg
│   └── data_viz_project_3.jpg
│
└── files/                  ← Create this folder
    └── your_cv.pdf         ← Your CV/Resume
```

---

## 🎯 How to Find What to Change

**Easy method:**
1. Open any HTML file
2. Use Ctrl+F (Windows) or Cmd+F (Mac)
3. Search for: `CHANGE`
4. Edit each section you find
5. Commit changes

**Every editable section has a comment starting with `<!-- CHANGE:`**

---

## ✅ Testing Checklist

After editing:
- [ ] Visit `https://your-username.github.io`
- [ ] Click through all 4 pages (Home, About, Portfolio, Contact)
- [ ] Check all images load
- [ ] Check all navigation links work
- [ ] Test email link opens email app
- [ ] Test social links open correctly
- [ ] View on mobile phone
- [ ] Download CV works

---

## 🎨 Features

✅ **Multi-page navigation** - separate pages that link together
✅ **Responsive design** - works on all devices
✅ **Clear comments** - know exactly what to change
✅ **Image specifications** - exact sizes and file names provided
✅ **Professional layout** - clean and modern design
✅ **Easy to customize** - just follow the comments

---

## 💡 Tips

**DO:**
✅ Use exact file names (case-sensitive!)
✅ Follow image size recommendations
✅ Keep images under 2MB
✅ Search for "CHANGE" to find all editable sections
✅ Test on phone and computer

**DON'T:**
❌ Change HTML structure (keep the `<div>` and tags)
❌ Delete comments (they help you know what to change)
❌ Use spaces in file names
❌ Skip uploading images

---

## 🐛 Troubleshooting

**Images not showing?**
- File names must match EXACTLY
- Must be in `images/` folder
- Check file extension (.jpg not .JPG)

**Pages not linking?**
- File names: `index.html`, `about_me.html`, `portfolio.html`, `contact.html`
- All in main folder (not in subfolders)

**Website not updating?**
- Wait 2-3 minutes after committing
- Hard refresh browser (Ctrl+Shift+R)

---

## 📖 How Comments Work

Every place you need to make changes has a comment like this:

```html
<!-- ============================================ -->
<!-- CHANGE: Replace this with your information -->
<!-- ============================================ -->
<h1>Your Name</h1>
```

**You only change the text BETWEEN the HTML tags:**
```html
<h1>John Smith</h1>  ← Change "Your Name" to "John Smith"
```

**Don't change the HTML tags themselves:**
```html
<h1>  ← Keep this
```

---

## 🌐 Your Website

After setup, your website will be live at:
`https://your-username.github.io`

Share it everywhere!

---

## 📚 Need Help?

- GitHub Pages: [pages.github.com](https://pages.github.com)
- HTML Basics: [w3schools.com/html](https://www.w3schools.com/html/)

---

**Remember:** Use Ctrl+F or Cmd+F to search for "CHANGE" in each file - that's where you need to edit! 🎯
