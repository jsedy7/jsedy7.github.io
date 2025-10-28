# jsedy.com

Personal portfolio and FPV drone showcase of **Jiří Šedý**

🌐 **Live site:** [https://jsedy.com](https://jsedy.com)

## 🧩 Overview

This repository contains the complete source code of my personal website, built with **[Hugo](https://gohugo.io/)** and the **[PaperMod](https://github.com/adityatelange/hugo-PaperMod)** theme

The site serves as:
- A portfolio of my **FPV drone projects** and cinematic shots
- A short overview of my **IT background**
- A simple **contact and pricing** page for collaborations  

It’s multilingual (🇨🇿 Czech & 🇬🇧 English) and automatically deployed via **GitHub Actions** to **GitHub Pages**

## ⚙️ Technical setup

### Local development

```bash
# clone the repository (including submodules)
git clone --recurse-submodules https://github.com/jsedy7/jsedy7.github.io.git
cd jsedy7.github.io/jsedy.com

# start local Hugo server
hugo server -D
```

Then open http://localhost:1313 in your browser

## 🚀 Deployment

Deployment is fully automated via **GitHub Actions**

Every push to the `main` branch triggers:
1. **Hugo build** inside the `jsedy.com` directory  
2. **Static output generation** to `jsedy.com/public`  
3. **Upload as artifact**  
4. **Deployment to GitHub Pages**

## 📄 License
This project is released under the [MIT License](LICENSE)
Feel free to use it as a reference for your own Hugo + PaperMod setup
