# Sandesh Patel | Developer Portfolio & Freelance Landing Page

Live website: **[sandesh-portfolio.pages.dev](https://sandesh-portfolio.pages.dev/)**

Source code for Sandesh Patel's personal developer portfolio and freelance landing page. Built with clean HTML5, custom CSS, and vanilla JavaScript, hosted on Cloudflare Pages.

---

## Live Site & Links

- **Live URL:** [https://sandesh-portfolio.pages.dev/](https://sandesh-portfolio.pages.dev/)
- **Privacy Policy:** [https://sandesh-portfolio.pages.dev/privacy.html](https://sandesh-portfolio.pages.dev/privacy.html)
- **Terms of Service:** [https://sandesh-portfolio.pages.dev/terms.html](https://sandesh-portfolio.pages.dev/terms.html)
- **Resume:** In-browser modal preview and direct PDF download

---

## Features

- **Direct, Human Copy:** Written in an authentic, developer-first voice highlighting real production work at REAK INFOTECH LLP and practical freelance services.
- **Zero Horizontal Overflow:** Strict layout bounds and responsive containers tested across mobile viewports (320px, 375px, 390px, 430px) through desktop (1280px+).
- **Real Vector Logos:** 100% SVG logos for all tools, languages, and platforms (Go, Python, Vue.js, TypeScript, PostgreSQL, Docker, GitHub, LinkedIn, WhatsApp, X).
- **Working Contact Form:** Asynchronous Formspree form submission with instant visual feedback, disabled button states, and direct email/WhatsApp fallbacks.
- **Dark & Light Mode:** Toggleable theme with local storage persistence and system preference detection (`prefers-color-scheme`).
- **Interactive Resume Modal:** Embedded PDF preview powered by Google Drive viewer with keyboard accessibility (Escape to close) and direct download options.
- **Scrollspy Navigation:** Sticky glassmorphic header that adjusts background blur and highlights active sections on scroll.
- **Animated Typing Text:** Smooth headline role cycling via Typed.js with fallback for users with `prefers-reduced-motion`.
- **Privacy & Analytics:** Privacy-preserving Cloudflare Web Analytics (cookie-free, no cross-site tracking) with full disclosure in `privacy.html`.

---

## Tech Stack

- **Markup:** Semantic HTML5, Schema.org JSON-LD structured data (`Person` and `WebPage`).
- **Styling:** Vanilla CSS3 with CSS custom properties (variables), Flexbox, CSS Grid, and mobile-first media queries.
- **Scripts:** Vanilla JavaScript (ES6+) for DOM interactions, theme switching, modal handling, and contact API calls.
- **Typography:** Poppins via Google Fonts.
- **Hosting & CI/CD:** Cloudflare Pages with Git pre-push hook auto-deployments via Wrangler.

---

## Project Structure

```text
portfolio/
├── 404.html                     # Custom 404 Not Found page
├── all-in-one.css               # Consolidated stylesheet with light/dark variables
├── google8d8686369b9d6380.html  # Google Search Console site verification
├── img/                         # Avatars, icons, and image assets
│   ├── favicon.png
│   ├── favicon.webp
│   └── sandesh_github.webp
├── index.html                   # Main portfolio & freelance landing page
├── license.txt                  # Open-source MIT license
├── privacy.html                 # Privacy Policy (includes Cloudflare Web Analytics disclosure)
├── README.md                    # Project documentation
├── robots.txt                   # Search crawler directives
├── SandeshPatel_Resume.pdf.pdf  # Developer resume PDF
├── script.js                    # Form handler, theme toggle, Typed.js, and modal logic
├── sitemap.xml                  # Search engine sitemap
└── terms.html                   # Terms of Service
```

---

## Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sandeshPatel06/portfolio.git
   cd portfolio
   ```

2. **Run locally:**
   Open `index.html` directly in a web browser, or run a local HTTP server:
   ```bash
   python3 -m http.server 8080
   ```
   Then navigate to `http://localhost:8080` in your browser.

3. **Deploying updates:**
   Pushes to `main` automatically run the local pre-push deployment hook via Wrangler:
   ```bash
   git push origin main
   ```

---

## Contact & Hire

- **Email:** [sandeshpatel.sp.93@gmail.com](mailto:sandeshpatel.sp.93@gmail.com)
- **WhatsApp:** [+91 9399613606](https://wa.me/9399613606)
- **LinkedIn:** [linkedin.com/in/sandesh-patel07](https://www.linkedin.com/in/sandesh-patel07)
- **GitHub:** [github.com/sandeshPatel06](https://github.com/sandeshPatel06)

---

## License

This project is licensed under the MIT License. See [license.txt](license.txt) for details.
