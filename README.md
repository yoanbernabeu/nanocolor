# 🎨 NanoColor - AI Coloring Page Generator

A fun, Neo-Brutalist web app that generates unique coloring pages using AI. Perfect for kids, parents, and anyone who loves to color!

> **⚡ Full Vibe Project** - Coded in 30 minutes with Gemini 3 Pro and Antigravity. The code is intentionally kept "non-clean" and in a single file for fun and simplicity!

![NanoColor Banner](https://img.shields.io/badge/AI-Powered-blueviolet?style=for-the-badge) ![Replicate](https://img.shields.io/badge/Replicate-Nano%20Banana%20Pro-orange?style=for-the-badge) ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Features

- 🤖 **AI-Powered Generation** - Uses Google's Nano Banana Pro model via Replicate API
- 🎭 **Multiple Styles** - Classic, Manga, Mandala, and Pixel Art
- 👶 **Age-Appropriate** - Toddler (thick lines), Child (classic), and Expert (fine details) difficulty levels
- 📸 **Reference Images** - Upload up to 14 images to guide the AI generation
- 🌍 **Bilingual** - Full support for English and French
- 💎 **Quality Options** - Generate in 1K, 2K, or 4K resolution
- 📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- 🎨 **Neo-Brutalist Design** - Bold, colorful, and kid-friendly interface
- ⚡ **Fast & Simple** - No backend required, runs entirely in the browser

## 🚀 Quick Start

### Prerequisites

You'll need a [Replicate API key](https://replicate.com/account/api-tokens) to use this app. The key should start with `r8_`.

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yoanbernabeu/nanocolor.git
cd NanoColor
```

2. Serve the app locally:
```bash
npx serve .
```

3. Open your browser to `http://localhost:3000`

4. Enter your Replicate API key when prompted

5. Start creating coloring pages! 🎉

## 🎯 How to Use

1. **Enter your API key** - Required on first use (stored in localStorage)
2. **Describe what you want** - E.g., "A dinosaur skateboarding"
3. **Optional: Upload reference images** - Add up to 14 images for inspiration
4. **Choose difficulty** - Toddler, Child, or Expert
5. **Select a style** - Classic, Manga, Mandala, or Pixel Art
6. **Adjust quality** - Use the ⚙️ menu to select 1K, 2K, or 4K
7. **Generate!** - Click the rocket button and wait for your unique coloring page
8. **Download & Print** - Save your creation and start coloring!

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling (via CDN)
- **Alpine.js** - Lightweight reactive framework
- **Replicate API** - AI model hosting (Nano Banana Pro)
- **CORS Proxy** - corsproxy.io for API access

## 🎨 Styles Available

- **Classic** - Traditional coloring book style with clean outlines
- **Manga** - Anime-inspired line art with dynamic expressions
- **Mandala** - Symmetrical geometric patterns for relaxation
- **Pixel Art** - Retro 8-bit style for nostalgic fun

## 📦 Deployment

This project is configured for automatic deployment to GitHub Pages.

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to **Settings** → **Pages**
3. Select **GitHub Actions** as the source
4. The workflow will automatically deploy on every push to `main`

Your app will be live at: `https://yoanbernabeu.github.io/nanocolor/`

## 🔐 Privacy & Security

- API keys are stored locally in your browser (localStorage)
- No data is sent to any server except Replicate's API
- All processing happens client-side
- Images are converted to base64 before being sent to the API

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

MIT License

Copyright (c) 2025 Yoan Bernabeu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 🙏 Acknowledgments

- **Google** - For the Nano Banana Pro AI model
- **Replicate** - For hosting the model and providing the API
- **Tailwind CSS** - For the amazing utility-first CSS framework
- **Alpine.js** - For the lightweight reactive framework

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yoanbernabeu/nanocolor/issues) page
2. Create a new issue with details about your problem
3. Make sure to include your browser version and any error messages

---

Made with ❤️ for kids and coloring enthusiasts everywhere!

**Happy Coloring!** 🖍️✨
