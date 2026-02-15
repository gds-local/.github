# GDS Local Website

This is the GitHub Pages website for GDS Local, styled to match the official GDS blog design.

## Setup Instructions

### Option 1: Using the GitHub Web Interface

1. **Upload the files:**
   - Go to your repository: https://github.com/gds-local/.github
   - Click "Add file" > "Upload files"
   - Drag and drop both `index.html` and `styles.css` files
   - Commit the files to the main branch

2. **Enable GitHub Pages:**
   - Go to Settings > Pages
   - Under "Build and deployment":
     - Source: Select "Deploy from a branch"
     - Branch: Select "main" and "/" (root)
   - Click Save

3. **View your site:**
   - Your site will be available at: https://gds-local.github.io/.github/
   - It may take a few minutes for the site to go live

### Option 2: Using Git Command Line

```bash
# Clone your repository
git clone https://github.com/gds-local/.github.git
cd .github

# Add the website files
# (Copy index.html and styles.css to this directory)

# Commit and push
git add index.html styles.css
git commit -m "Add GDS Local website"
git push origin main
```

Then follow step 2 from Option 1 to enable GitHub Pages.

### Option 3: Create a Custom Domain Site

If you want a cleaner URL like `gds-local.github.io`:

1. Create a new repository named `gds-local.github.io`
2. Upload `index.html` and `styles.css` to this repository
3. Go to Settings > Pages
4. The site will automatically be available at: https://gds-local.github.io/

## Customizing the Site

### Adding Blog Posts

To add blog posts, you can:
1. Create additional HTML files (e.g., `post-1.html`, `post-2.html`)
2. Link to them from the main `index.html` page
3. Copy the post structure from `index.html`

### Updating Content

- Edit `index.html` to change the main page content
- Edit `styles.css` to adjust the visual styling
- All content follows GDS design patterns and accessibility standards

## Design Features

This site includes:
- GOV.UK Design System styling
- Accessible skip links
- Responsive layout (mobile and desktop)
- GDS crown logo and branding
- Sidebar with useful links
- Footer with Open Government Licence information

## Accessibility

The site follows WCAG 2.1 AA standards:
- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Focus indicators
- Semantic HTML

## License

Content is available under the Open Government Licence v3.0
