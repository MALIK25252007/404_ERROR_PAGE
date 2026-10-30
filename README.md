<div align="center">

<!-- Animated waving header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=240&section=header&text=404%20ERROR&fontSize=80&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=Page%20not%20found%20%E2%80%94%20I%20tried%20to%20catch%20some%20fog%2C%20but%20I%20missed%20it&descSize=18&descAlignY=62" width="100%" alt="404 Error header" />

<!-- Typing animation -->
<a href="https://404errorpage-five.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=7DD3FC&center=true&vCenter=true&width=700&lines=%F0%9F%8C%AB%EF%B8%8F+Oops!+This+page+got+lost+in+the+fog;404+%E2%80%94+Page+not+found;A+clean+and+minimal+error+page;Designed+by+Tarun+Malik" alt="Typing animation" />
</a>

<br/>

<a href="https://404errorpage-five.vercel.app/">
  <img src="https://img.shields.io/badge/%F0%9F%9A%80%20LIVE%20DEMO-View%20404%20Page-7dd3fc?style=for-the-badge&labelColor=0f2027" alt="Live Demo" />
</a>
<a href="https://github.com/MALIK25252007/404_ERROR_PAGE">
  <img src="https://img.shields.io/badge/%E2%AD%90%20SOURCE-GitHub%20Repo-2c5364?style=for-the-badge&logo=github&logoColor=white" alt="Repository" />
</a>

<br/><br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Responsive](https://img.shields.io/badge/Design-Responsive-success?style=for-the-badge)
![Single File](https://img.shields.io/badge/Single%20File-index.html-blueviolet?style=for-the-badge)

</div>

---

## 🌫️ About The Project

Nobody likes landing on a broken link, but a good error page can make it a little less annoying. **404 Error Page** is a clean, minimal and atmospheric "Page not found" page with a foggy theme and a playful message:

<div align="center">

> **404**
> ### Page not found
> *I tried to catch some fog, but I missed it.*

</div>

The whole page lives in a single `index.html` file, so it's easy to read, customize and drop into any website. Just point your server's 404 route at it.

Designed and built by **[Tarun Malik](https://github.com/MALIK25252007)**.

---

## 🌐 Live Preview

<div align="center">

### 👉 [**404errorpage-five.vercel.app**](https://404errorpage-five.vercel.app/) 👈

</div>

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🌫️ | **Fog Theme** | Moody, atmospheric look with a playful error message |
| 🔢 | **Big 404 Display** | Large, eye-catching error code that's clear at a glance |
| 🏠 | **Back to Home Button** | Lets visitors get back on track right away |
| 📱 | **Responsive** | Works on mobile, tablet and desktop |
| ⚡ | **Lightweight** | A single HTML file with no heavy dependencies |
| 🧩 | **Easy to Customize** | Change the text, colors and link in minutes |
| 🚀 | **Deploy Anywhere** | Works on Vercel, Netlify, GitHub Pages or any web server |

---

## 🧭 User Flow

```mermaid
flowchart LR
    A[🔗 Broken or wrong link] --> B[🌫️ 404 Page]
    B --> C{Visitor clicks}
    C -->|Back to Home| D[🏠 Home Page]
    style A fill:#203a43,color:#fff,stroke:#7dd3fc
    style B fill:#2c5364,color:#fff,stroke:#7dd3fc
    style C fill:#0f2027,color:#fff,stroke:#7dd3fc
    style D fill:#7dd3fc,color:#000,stroke:#203a43
```

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,vercel,git,github,vscode&theme=dark" alt="Tech stack icons" />

</div>

- **HTML5** – page structure and content
- **CSS3** – styling, layout and visual effects
- **Vercel** – fast, free hosting for the live demo

---

## 📂 Project Structure

```
404_ERROR_PAGE/
├── 📄 index.html    # The complete 404 page
└── 📄 README.md     # You are here
```

---

## 🚀 Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/MALIK25252007/404_ERROR_PAGE.git
```

**2. Go into the project folder**

```bash
cd 404_ERROR_PAGE
```

**3. Open it in your browser**

Double-click `index.html`, or run it with the VS Code **Live Server** extension.

---

## 🔌 Use It As Your Website's 404 Page

<details>
<summary><strong>▶ Vercel / Netlify / GitHub Pages</strong></summary>

<br/>

- **GitHub Pages:** rename the file to `404.html` and put it in the root of your site. GitHub Pages shows it automatically for missing pages.
- **Netlify:** name the file `404.html` in your publish folder. Netlify serves it for unknown routes.
- **Vercel:** name it `404.html` in your output folder (for static sites), or add a `404.html` / not-found route according to your framework.

</details>

<details>
<summary><strong>▶ Apache</strong></summary>

<br/>

Add this line to your `.htaccess` file:

```apache
ErrorDocument 404 /404.html
```

</details>

<details>
<summary><strong>▶ Nginx</strong></summary>

<br/>

Add this inside your `server` block:

```nginx
error_page 404 /404.html;
```

</details>

---

## 🎨 Customization

- **Message:** change the "Page not found" heading and the fog line in `index.html`
- **Colors & fonts:** edit the CSS inside the file to match your brand
- **Button link:** point the **Back to Home** button to your real homepage URL (right now it uses `#`)
- **Footer:** update the copyright text and credit line

---

## 🗺️ Roadmap

- [x] Clean foggy 404 layout
- [x] Back to Home button
- [x] Live deployment on Vercel
- [ ] Add more fog animation effects
- [ ] Light and dark mode toggle
- [ ] Search box to help visitors find pages
- [ ] Multiple theme options

---

## 🏷️ Topics / Tags

<div align="center">

`404-page` `error-page` `404-error` `page-not-found` `not-found` `html` `css` `html-css` `frontend` `web-design` `ui-design` `minimal-design` `responsive-design` `vercel` `single-page` `beginner-friendly` `open-source` `portfolio-project`

</div>

> 💡 **Tip:** Add these as repository topics on GitHub (⚙️ next to *About* → *Topics*) so people can discover your project.

---

## 🤝 Contributing

Ideas and improvements are welcome!

1. 🍴 Fork the project
2. 🌿 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔁 Open a Pull Request

---

## 📜 License

This project is free to clone and use for personal projects. Credit to the author is appreciated.

---

## 📬 Contact

<div align="center">

**Tarun Malik**

[![GitHub](https://img.shields.io/badge/GitHub-MALIK25252007-181717?style=for-the-badge&logo=github)](https://github.com/MALIK25252007)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tarun%20Malik-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/tarun-malik-9bab21388)
[![Instagram](https://img.shields.io/badge/Instagram-_malik__200716-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_malik_200716)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat%20Now-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/918279630850)
[![Email](https://img.shields.io/badge/Email-Malik1642007@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Malik1642007@gmail.com)

<br/>

### ⭐ If you like this project, give it a star! ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=140&section=footer&animation=fadeIn" width="100%" alt="footer" />

</div>
