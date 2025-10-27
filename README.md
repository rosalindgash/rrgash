# Rosalind Gash - Personal Website

A personal branding website showcasing my work as an academic researcher and tech founder, exploring the intersection of adaptive digital technologies, accessibility, and AI-assisted development.

🔗 **Live Site:** [https://rosalindgash.github.io/rrgash](https://rosalindgash.github.io/rrgash)

## About

This site presents my dual identity as both an academic researcher and technology entrepreneur, highlighting:

- **Research Focus:** Adaptive digital technologies, energy-conscious research methodologies, and AI-assisted academic practices
- **Tech Projects:** PingBuoy (website monitoring SaaS) and other development work
- **Intersection:** How academic research informs product development and vice versa

## Features

- **Single-page application** with section navigation (Overview, Research, Tech, Contact)
- **Responsive design** that works on mobile, tablet, and desktop
- **Amber/gold color scheme** for a warm, professional aesthetic
- **No build process required** - runs directly in the browser
- **Fast loading** with CDN-hosted dependencies

## Tech Stack

- **React 18** - UI framework (loaded via CDN)
- **TailwindCSS** - Utility-first CSS (loaded via CDN)
- **Babel Standalone** - JSX transformation in the browser
- **Vanilla JavaScript** - No build tools needed

## Structure

```
├── index.html          # Main application file (contains all React code)
├── cartoon-me.jpg      # Profile image
└── README.md          # This file
```

## Local Development

Simply open `index.html` in any modern web browser. No build process or local server required.

For a better development experience with live reload:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Deployment to GitHub Pages

1. Create a new GitHub repository (or use existing)
2. Upload `index.html` and `cartoon-me.jpg` to the repository root
3. Go to **Settings → Pages**
4. Under "Source", select your main branch and `/` (root)
5. Click **Save**
6. Your site will be live at `https://rosalindgash.github.io/rrgash/`

## Customization

All content is contained in `index.html`. To modify:

1. Open `index.html` in a text editor
2. Find the section you want to edit (search for section headers like "Research Section" or "Tech Section")
3. Edit the text content within the JSX
4. Save and refresh your browser

### Key Sections to Customize:

- **Hero section** (lines ~160-190): Main introduction and tagline
- **Research section** (lines ~320-410): Research focus and publications
- **Tech section** (lines ~415-510): Project descriptions
- **Contact section** (lines ~515-615): Contact information and links

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

Note: Internet Explorer is not supported.

## Performance

- **No build time** - instant changes
- **CDN-hosted libraries** - fast global delivery
- **Single HTML file** - simple deployment
- **Client-side rendering** - no server required

## Trade-offs

This approach prioritizes simplicity and ease of deployment over performance optimization:

**Pros:**
- Zero build configuration
- Easy to edit and deploy
- Works on any static hosting
- Perfect for GitHub Pages

**Cons:**
- Larger initial bundle size
- No code splitting
- Not ideal for SEO (single-page app)
- Babel transform happens in browser

## Future Enhancements

Potential improvements for later:

- [ ] Add proper build process with Vite or Create React App
- [ ] Implement static site generation for better SEO
- [ ] Add blog section with markdown support
- [ ] Create separate pages for each section
- [ ] Add animations and transitions
- [ ] Implement dark mode

## Research Interests

- AI-assisted academic research methodologies
- Applying ADAP (Adaptive Digital Academic Practice) frameworks  
- Accessibility in digital technologies
- Energy-conscious research frameworks

## Connect

- **Email:** rrgash@protonmail.com
- **LinkedIn:** [linkedin.com/in/rosalindgash](https://www.linkedin.com/in/rosalindgash)
- **GitHub:** [github.com/rosalindgash](https://github.com/rosalindgash)

## Affiliations

- Society for Disability Studies

## License

© 2025 Rosalind Gash. All rights reserved.

---

*Built with React and TailwindCSS. Bridging academia and entrepreneurship through accessible technology.*
