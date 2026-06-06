# QuietTrace Web

> Landing page and marketing site for QuietTrace - A private, offline-first journaling app

[![Deployed on Cloudflare Pages](https://img.shields.io/badge/deployed-Cloudflare%20Pages-F38020?logo=cloudflare)](https://quiettrace.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🌐 Live Site

[quiettrace.app](https://quiettrace.app)

## 📖 About

This repository contains the landing page and marketing site for QuietTrace, a private journaling application currently in development. The page serves as a placeholder and future email signup point for interested users.

**QuietTrace** is a privacy-first, offline-capable journaling app for iOS and Android. Built with Flutter and Supabase, it offers:
- 🔒 Private, secure journaling
- 📱 Offline-first architecture
- ☁️ Optional cloud sync
- 🏷️ Tag-based organization
- 🌙 Dark mode support
- 📤 Full data export

## 🚀 Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/yourusername/quiet-trace-web.git
cd quiet-trace-web

# Open in browser
open index.html
# or with a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

### Using Live Server (VS Code)

1. Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Right-click `index.html`
3. Select "Open with Live Server"

## 📁 Project Structure

```
quiet-trace-web/
├── index.html          # Main landing page
├── assets/             # (Future) Images, fonts, icons
├── styles/             # (Future) Additional CSS if needed
├── scripts/            # (Future) Any JavaScript
└── README.md           # This file
```

## 🌍 Deployment

### Cloudflare Pages (Current)

This site is automatically deployed to Cloudflare Pages.

**Automatic Deployment:**
Every push to `main` triggers a new deployment.

**Manual Deployment:**
1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com)
2. Go to Pages
3. Select the project
4. Click "Create deployment"
5. Upload files or connect to GitHub

### Alternative Deployment Options

<details>
<summary><b>Netlify</b></summary>

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```
</details>

<details>
<summary><b>Vercel</b></summary>

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```
</details>

<details>
<summary><b>GitHub Pages</b></summary>

1. Go to repository Settings > Pages
2. Select source: Deploy from a branch
3. Select branch: `main` and folder: `/ (root)`
4. Save

Your site will be available at: `https://yourusername.github.io/quiet-trace-web/`
</details>

## 🎨 Customization

### Update Content

Edit `index.html` to change:
- **Headline:** Update the `<h1>` tag
- **Tagline:** Modify the `.tagline` paragraph
- **Description:** Change the `.description` content
- **Status:** Update the `.status` div

### Change Colors

The gradient background can be customized in the `<style>` section:

```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* Replace with your preferred colors */
}
```

### Add Email Signup

To add Mailchimp/ConvertKit integration later:

```html
<div class="email-signup">
    <form action="YOUR_FORM_ACTION" method="post">
        <input type="email" placeholder="Enter your email" required>
        <button type="submit">Notify Me</button>
    </form>
</div>
```

## 🔧 Future Enhancements

- [ ] Email signup form integration
- [ ] Animated hero section
- [ ] Feature showcase section
- [ ] Screenshot carousel
- [x] Privacy policy page
- [x] Terms of service page
- [ ] Blog/updates section
- [ ] Social media links
- [ ] Analytics integration (privacy-friendly)

## 📊 Analytics

Currently no analytics are implemented to respect user privacy. When adding analytics, consider privacy-friendly options:
- [Plausible](https://plausible.io/)
- [Fathom](https://usefathom.com/)
- [Simple Analytics](https://simpleanalytics.com/)

## 🤝 Contributing

This is a personal project, but suggestions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Related Links

- **Main App Repository:** [github.com/yourusername/quiet-trace-app](https://github.com/yourusername/quiet-trace-app) (private)
- **Website:** [quiettrace.app](https://quiettrace.app)
- **Twitter:** [@quiettrace](https://twitter.com/quiettrace)
- **Instagram:** [@quiettrace](https://instagram.com/quiettrace)

## 👨‍💻 Author

**Steve Gray**
- Website: [biblepraise.org](https://biblepraise.org)
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments

- Design inspiration from minimalist app landing pages
- Deployed with [Cloudflare Pages](https://pages.cloudflare.com/)

---

**Status:** 🚧 In Development | **Version:** 0.1.0 | **Last Updated:** January 2026
