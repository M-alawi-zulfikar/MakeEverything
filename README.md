<div align='center'>

# 🎬 MakeEverything

**Turn HTML & CSS animations into a video. Free, open source, runs in your browser.**

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![No upload](https://img.shields.io/badge/Your_code-Never_uploaded-8A2BE2?style=for-the-badge)
![No install](https://img.shields.io/badge/Install-Not_needed-22d3ee?style=for-the-badge)

### [▶ Open the website](https://m-alawi-zulfikar.github.io/MakeEverything/)

</div>

---

## ✨ What is it?

Write an animation with plain HTML and CSS, press **Make video**, and download the result. Everything happens inside your browser, so your code is never sent anywhere.

## 🚀 How to use

1. Open the [website](https://m-alawi-zulfikar.github.io/MakeEverything/)
2. Paste or write your HTML + CSS
3. Pick a size (square, vertical for Reels/TikTok/Shorts, or wide), FPS, and length
4. Press **Make video**, then **Download**

## 🧠 How it works

1. Your code runs in a sandboxed iframe (JavaScript is blocked).
2. Over and over, the animated page is drawn onto a canvas using an SVG `foreignObject`.
3. The browser's `MediaRecorder` records the canvas into a video file.

## ⚠️ Limitations

- Works best in **Chrome or Edge** (including Android). Safari is not supported yet.
- Video smoothness depends on your device speed.
- Output is **WebM**. Convert it if you need MP4.
- Animations on `::before` / `::after` are not captured yet.
- External images, fonts, and stylesheets are not loaded. Use `data:` URLs and system fonts.
- No JavaScript inside your animation, only HTML and CSS.

## 💻 Run it locally

No build step. Download `index.html` and open it in your browser.

## 🗺️ Roadmap

- [x] HTML + CSS to WebM video
- [ ] MP4 export
- [ ] Frame-perfect mode (same result on every device)
- [ ] Capture `::before` / `::after` animations
- [ ] Ready-made templates
- [ ] Audio track

## 🤝 Contributing

Ideas and fixes are welcome! Fork the repo, change `index.html`, and open a pull request. Bug reports go in the Issues tab.

## 📄 License

MIT. Free to use, change, and share.

---

<div align='center'>

Made with 💜 by [Alawi](https://github.com/M-alawi-zulfikar) · ⭐ Star the repo if it helps you!

</div>
