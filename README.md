# The Matrix Fan Website 🕶️🟩

This fan-made website is a tribute to **The Matrix** film series, blending cinematic homage with interactive design. Built using **HTML**, **CSS**, and **JavaScript**, it features the iconic **falling code animation**, character galleries, story synopses, and more—all crafted with no external libraries or frameworks.

> ⚠️ *This site is a non-commercial fan project. It is not affiliated with or endorsed by the original creators or studios of The Matrix franchise.*

---

### 🖥️ **Live Demo**

Explore the site by opening `index.html` in any modern browser, or visit the hosted version here:  
🔗 [https://thematrix.andreszenteno.com](https://thematrix.andreszenteno.com)

---

### 📁 **Project Structure**

```plaintext
matrix-website/
│
├── index.html           # Homepage with falling code and intro
├── matrix.js            # JavaScript for falling code animation
├── components/
│   ├── footer.html
│   └── header.html
├── pages/
│   ├── gallery.html
│   ├── home.html
│   ├── soundtrack.html
│   ├── synopsis.html
│   └── videos.html
├── assets/
│   ├── css/             # Global styles
│   ├── gif/
│   ├── images/          # Movie stills and thumbnails
│   ├── svg/
│   └── webfonts/
└── README.md            # Project documentation
```

---

### 🚀 **Getting Started**

To run the site locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/andresz74/matrix-website.git
   cd matrix-website
   ```

2. **Don't just open `index.html` directly**:
   Modern browsers block local file access (like `file:///`) for security reasons. Use a local web server instead.

---

### 📦 **Local Development Tips**

If you try to open `index.html` directly from your file browser, you'll likely encounter errors like:

```
Not allowed to load local resource: file:///assets/css/style.css
Fetch API cannot load file:///components/header.html due to access control checks.
```

These errors happen because modern browsers restrict local `file://` access. To fix this, run a **local web server**:

#### ✅ Option 1: Use Python (built-in on most systems)

```bash
cd matrix-website
python3 -m http.server 8000
```

Then visit: [http://localhost:8000](http://localhost:8000)

#### ✅ Option 2: Use Node.js and `http-server`

```bash
npm install -g http-server
cd matrix-website
http-server -p 8000
```

#### ✅ Option 3: Use **Live Server** in VS Code

1. Install the **Live Server** extension.
2. Right-click `index.html` → **Open with Live Server**


### 🧠 **Features**

* 🟢 **Matrix Falling Code** animation with canvas and JavaScript.
* 🖼️ **Visual Gallery** featuring stills from the films.
* 📝 **Character Highlights** including Neo, Trinity, Morpheus, and Agent Smith.
* 📜 **Story Synopses** for each movie in the series.
* 🌐 **Responsive Layout** for desktop and mobile.

---

### 🎨 **Customization Options**

* Modify `matrix.js` to change:

  * Characters used in the rain effect
  * Speed and font size of falling code
* Add or replace images in the `assets/images` directory
* Update text content to localize or personalize the site

---

### 🌟 **Preview**

![The Matrix Fan Website](https://zenteno.org/public_assets/matrix-website-screenshot.png)

---

### 📄 **License**

This project is open-source and distributed under the [MIT License](LICENSE).
All Matrix-related content (images, character names, etc.) remains the property of their respective copyright holders.

---

### 🙋‍♂️ **About the Creator**

**Andres Zenteno**
Frontend Developer & Sci-Fi Enthusiast
GitHub: [@andresz74](https://github.com/andresz74)
Email: [azenteno74@gmail.com](mailto:azenteno74@gmail.com)
Website: [zenteno.org](https://zenteno.org)
