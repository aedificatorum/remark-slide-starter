
class: center, middle

# RemarkJS Starter Slides

---

# What's Inside?

- Edit your slides in Markdown (complete with highlighting/preview)
- Presentation mode with speaker notes
- Hot reload on save
- Export to PDF

--

> _Requires an internet connection to present! If you need offline support pull remarkjs & any fonts down._

---

# Getting Started

```bash
git clone https://github.com/aedificatorum/remarkjs-slide-starter.git new-slides
cd new-slides
git remote remove origin
npm install
npm run present
```

---

# Modifying Content

- Slides live in `public/slides.md`
- Customise fonts in `public/styles.css`

---

# Presenting

- Use the forward & back arrows to navigate
- Press `c` to open a second window (great for putting on a second monitor)
- Press `p` to open presenter mode, which shows current slide, next slides, and notes

---

# Exporting Slides

- While running the `present` task, run `npm run export`

---

# More Information

- Slideshow built with `remarkjs` - https://remark.js.com
- Served up with `live-server` - https://github.com/tapio/live-server
- PDF exported by `decktape` - https://github.com/astefanutti/decktape

---

# Suggestions?

- https://github.com/aedificatorum/remarkjs-slide-starter

--

.center[.contain-image[![Continue](https://http.cat/100)]]