# My Personal Portfolio & Blog

A modern, responsive personal website built with Jekyll and deployed on GitHub Pages. Features a dark/light theme toggle, responsive design, and organized sections for projects, blog posts, and social links.

## Features

- 🎨 **Dark/Light Theme** — Toggle between dark and light modes with localStorage persistence
- 📱 **Fully Responsive** — Mobile-first design that works on all devices
- 🚀 **Jekyll Powered** — Static site generation for fast performance
- 🎯 **Customizable** — Easy to personalize with your own content
- ⚡ **No Dependencies** — Pure HTML, CSS, and JavaScript (no frameworks)

## Quick Start

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/pkhatiwoda47/introduction.git
   cd introduction
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the local server**
   ```bash
   bundle exec jekyll serve
   ```
   
4. **Visit** `http://localhost:4000` in your browser

### Customize Your Site

1. **Edit `_config.yml`** to update:
   - Your name and description
   - Email and social links
   - Site metadata

2. **Update `index.html`** to:
   - Personalize the hero section copy
   - Add your own links and projects
   - Update social media URLs

3. **Create blog posts** in `_posts/` with format:
   ```
   _posts/YYYY-MM-DD-your-post-title.md
   ```

## Project Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # Page templates
│   ├── default.html     # Base layout
│   └── post.html        # Blog post layout
├── _sass/               # SCSS partials
│   ├── _variables.scss  # Color and font variables
│   ├── _reset.scss      # Reset styles
│   └── _highlights.scss # Code highlighting
├── style.scss           # Main stylesheet
├── index.html           # Homepage
└── README.md            # This file
```

## Customization Guide

### Colors

Edit `_sass/_variables.scss` to customize the color scheme:

```scss
$panel: #090f18;
$text: #e5edf8;
$accent: #63c5ff;
$blue: #0ea5e9;
```

### Fonts

Update font-family variables in `_sass/_variables.scss`:

```scss
$helvetica: 'Your Font Name', 'Fallback Font', sans-serif;
```

### Max Width

Change the container width:

```scss
$max-width: 1120px;
```

## Deployment

The site is configured to deploy automatically on GitHub Pages when you push to the main branch.

1. Go to your repository settings
2. Scroll to "GitHub Pages"
3. Select "main" as the source branch
4. Your site will be available at `https://pkhatiwoda47.github.io/introduction`

## Adding a Blog

1. Create `_posts/` directory
2. Add markdown files with format: `YYYY-MM-DD-title.md`
3. Add front matter:
   ```yaml
   ---
   layout: post
   title: My First Post
   date: 2024-01-01
   ---
   ```

## Browser Support

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers

## License

MIT - Feel free to use this as a template for your own site!

## Resources

- [Jekyll Docs](https://jekyllrb.com/docs/)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [SCSS Guide](https://sass-lang.com/guide)

---

Made with ❤️. Happy creating!
