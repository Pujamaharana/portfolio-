# Photography Portfolio (GitHub Pages Ready)

This is a clean **Photography + Resume** portfolio site for **Pranesh**. Edit the text in `index.html` and publish free using **GitHub Pages**.

## ✏️ What to Edit First
- In `index.html`:
  - Replace name, email, phone, Instagram handle, and About text.
  - Update the **Experience**, **Education**, and **Skills** to match your resume.
  - Replace gallery image links with your own (local files or hosted URLs).

## 🖼 Replace Gallery Images
- Find the `<section id="gallery">` in `index.html`.
- Each gallery item is:
  ```html
  <a class="masonry-item" href="BIG_IMAGE_URL" data-lightbox>
    <img src="THUMB_IMAGE_URL" alt="Your caption">
  </a>
  ```
- You can use your own local images by adding them under `assets/img/` and changing the links:

  ```html
  <a class="masonry-item" href="assets/img/wedding-01.jpg" data-lightbox>
    <img src="assets/img/wedding-01.jpg" alt="Wedding">
  </a>
  ```

## 🚀 Publish on GitHub Pages (No Coding Needed)
1. Create a GitHub account (if not already).  
2. Click **New repository** → Name it **portfolio** (or any name).  
3. Click **Upload files**, and upload everything from this folder.  
4. Go to **Settings → Pages**:  
   - **Source**: Deploy from a branch  
   - **Branch**: `main` / root (`/`) → **Save**  
5. Your site will be live at:  
   `https://YOUR-USERNAME.github.io/REPO-NAME/`

## 🏷 Customise Colors / Theme
- Colors are set in `assets/css/style.css` at the top (`:root`).  
- For a light theme, change background to light and text to dark.

## 💬 Contact Form
- The "Send" button opens the user's email app with pre-filled text (`mailto:`).  
- To use a real service later, connect Formspree, SheetDB, or Netlify Forms.

## 🧩 Optional: Add a Favicon
Place `favicon.ico` in the project root and add in `<head>`:
```html
<link rel="icon" href="favicon.ico">
```

---

Made with ❤️ and ready for GitHub Pages.
