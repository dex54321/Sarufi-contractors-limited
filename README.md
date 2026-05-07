# 🏗️ SARUFI CONTRACTORS WEBSITE
## Professional Construction Contractor Website

---

## 📁 FOLDER STRUCTURE

```
sarufi-contractors-website/
│
├── index.html                 # Main HTML file (START HERE)
│
├── css/
│   └── styles.css            # All styling and design
│
├── js/
│   └── script.js             # JavaScript functionality
│
├── images/                    # Folder for local images (optional)
│   └── (place your images here)
│
└── README.md                 # This file
```

---

## 🚀 HOW TO USE

### **Step 1: Download All Files**
Download the entire `sarufi-contractors-website` folder to your computer.

### **Step 2: Open the Website**
1. Navigate to the folder
2. Double-click on `index.html`
3. It will open in your default web browser
4. The website will display perfectly with all images, styles, and functionality

### **Step 3: Make Edits**

#### **To Edit HTML Content:**
- Open `index.html` with a text editor (VS Code, Notepad, etc.)
- Find the section you want to change
- Make your edits
- Save the file
- Refresh your browser to see changes

#### **To Edit Styling:**
- Open `css/styles.css`
- Modify colors, fonts, sizes, spacing, etc.
- Save the file
- Refresh your browser

#### **To Add/Modify JavaScript:**
- Open `js/script.js`
- Add new functionality
- Save the file

#### **To Replace Images:**
Look for image URLs in `index.html` that look like:
```html
<img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=400&h=280&fit=crop" alt="...">
```

Replace with your own image URLs or local paths:
```html
<img src="images/your-photo.jpg" alt="...">
```

---

## 🔧 KEY FILES EXPLAINED

### **index.html**
- Contains all the website structure (HTML)
- Imports CSS from `css/styles.css`
- Imports JavaScript from `js/script.js`
- Main content: Hero, Services, Gallery, Projects, Testimonials, Footer

### **css/styles.css**
- **Color Variables** (lines 14-22):
  ```css
  --primary-color: #c84b31;      /* Orange/brown */
  --primary-dark: #a83d27;       /* Darker brown */
  --accent-color: #f59e0b;       /* Golden orange */
  ```
- **Sections**: Each section has its own CSS block
- **Responsive Design**: Mobile adjustments at bottom

### **js/script.js**
- Smooth scrolling between sections
- Scroll animations for cards
- Gallery lazy loading
- Button hover effects
- Form validation helpers (for future contact form)

---

## 🎨 CUSTOMIZATION GUIDE

### **Change Logo/Brand Name**
In `index.html`, find:
```html
<div class="logo">Sarufi Contractors</div>
```
Replace with your company name.

### **Change Colors**
In `css/styles.css`, update these variables (lines 14-22):
```css
--primary-color: #c84b31;        /* Main color */
--primary-dark: #a83d27;         /* Darker shade */
--accent-color: #f59e0b;         /* Button/accent color */
```

### **Update Contact Information**
Search for these in `index.html`:
- `contact@sarufibuilderscontractors.com` → Your email
- `+254712345678` → Your phone
- `www.sarufibuilderscontractors.com` → Your website

### **Change Service Cards**
Find the services section and edit titles/descriptions:
```html
<h3>Foundation & Structural Work</h3>
<p>Expert foundation laying...</p>
```

### **Update Project Images**
Replace Unsplash URLs with your own images:
```html
<!-- FROM: -->
<img src="https://images.unsplash.com/..." alt="...">

<!-- TO: -->
<img src="images/your-project.jpg" alt="...">
```

### **Update Testimonials**
Find testimonial cards and modify:
- Client names
- Review text
- Company/title information

---

## 🌐 HOW TO HOST ONLINE

### **Option 1: Netlify (EASIEST & FREE)**
1. Go to **netlify.com**
2. Sign up for free
3. Drag & drop the entire folder
4. Get a live URL instantly!

### **Option 2: GitHub Pages (FREE)**
1. Create GitHub account
2. Create repository
3. Upload all files
4. Enable GitHub Pages in settings
5. Get a free URL

### **Option 3: Web Hosting (PAID)**
1. Buy hosting from GoDaddy, Bluehost, etc.
2. Use FTP/File Manager to upload files
3. Point domain to hosting
4. Website goes live!

---

## 📝 IMPORTANT NOTES

✅ **All files MUST be in the correct folder structure** for linking to work
✅ **Keep file names exactly as they are** (case-sensitive on some servers)
✅ **Images load from Unsplash** - Replace with your own for better branding
✅ **JavaScript enhances experience** - Website works even without it
✅ **Mobile responsive** - Looks great on all devices

---

## 🔐 FILE PERMISSIONS

Make sure all files have read permissions:
- `index.html` - Read permission
- `css/styles.css` - Read permission
- `js/script.js` - Read permission

---

## ❓ TROUBLESHOOTING

**Images not showing?**
- Check image URLs are correct
- Verify images are in the `images/` folder
- Use full URLs or correct relative paths

**Styles not applying?**
- Verify `css/styles.css` is in the `css/` folder
- Check file name spelling (case-sensitive)
- Clear browser cache (Ctrl+Shift+Delete)

**JavaScript not working?**
- Verify `js/script.js` is in the `js/` folder
- Check browser console for errors (F12)
- Website still functions without JavaScript

**Navigation links not working?**
- Verify section IDs match href attributes
- Check for typos in section names
- Ensure IDs are unique

---

## 📞 QUICK CUSTOMIZATION CHECKLIST

- [ ] Change company name (Sarufi Contractors → Your name)
- [ ] Update email address
- [ ] Update phone number
- [ ] Update website URL
- [ ] Edit service descriptions
- [ ] Add your project images
- [ ] Update testimonials with real clients
- [ ] Change colors to match branding
- [ ] Update footer information
- [ ] Test all links and buttons

---

## 🎓 NEXT STEPS

1. **Customize for your client** - Edit all company details
2. **Add real images** - Replace Unsplash placeholder images
3. **Update testimonials** - Use real client feedback
4. **Test thoroughly** - Check all sections and links
5. **Deploy online** - Use Netlify, GitHub Pages, or web hosting
6. **Get feedback** - Share with client and iterate

---

## 📧 SUPPORT

For questions about:
- **HTML/CSS/JS** - Check W3Schools.com
- **Image hosting** - Use Unsplash, Pexels, or Pixabay
- **Deployment** - Check Netlify docs or GitHub Pages guide
- **Customization** - Edit files with VS Code

---

**Last Updated:** 2024
**Website Version:** 1.0
**Status:** ✅ Production Ready

---

Built with ❤️ for Sarufi Contractors
