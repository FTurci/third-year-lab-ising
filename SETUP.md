# Setup Instructions for Students

## Publishing Your Own Quarto Website

### 1. Fork the Repository
Click the "Fork" button at the top right of the GitHub repository page.

### 2. Clone Your Fork
```bash
git clone https://github.com/[your-username]/third-year-lab-ising.git
cd third-year-lab-ising
```

### 3. Preview Locally
```bash
quarto preview
```

### 4. Publish to GitHub Pages
When you're ready to publish:

```bash
quarto publish gh-pages
```

The first time you run this, Quarto will:
- Ask you to confirm
- Create a `gh-pages` branch
- Push your website to GitHub Pages

Your website will be available at: `https://[your-username].github.io/third-year-lab-ising/`

### 5. Update Your Website
After making changes:

```bash
quarto publish gh-pages
```

Quarto will rebuild and republish your site.

## Adding Content
- Edit `index.qmd` to modify the homepage
- Add new `.qmd` files for additional pages
- Update `_quarto.yml` to add pages to the navigation bar
