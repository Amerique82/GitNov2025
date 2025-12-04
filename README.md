# Digital Artisan - Corporate Services Website

A modern, professional corporate website showcasing digital services with beautiful design and smooth animations.

## Features

- 🎨 Modern corporate design with dark theme
- 📱 Fully responsive (mobile, tablet, desktop)
- ✨ Smooth animations and transitions
- 🎯 Single-page navigation with smooth scrolling
- 💼 Services showcase with Unsplash images
- 🛠️ Expertise section with animated progress bars
- 👥 Team-focused About Us section
- 📧 Contact form with validation
- 🌟 Floating shapes animation

## Sections

1. **Home** - Hero section with compelling value proposition
2. **About Us** - Team introduction with statistics
3. **Services** - 6 professional services with images
4. **Expertise** - Technical skills and capabilities
5. **Contact** - Get in touch form with company information

## Files Included

- `index.html` - Main HTML structure
- `styles.css` - All styling and animations
- `script.js` - Interactive functionality and animations

## How to Use Locally

1. Download all three files to the same folder
2. Open `index.html` in any modern web browser
3. That's it! No server or dependencies needed

## How to Upload to GitHub and Deploy

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., "portfolio-website")
5. Make sure it's set to **Public**
6. Don't initialize with README, .gitignore, or license
7. Click "Create repository"

### Step 2: Upload Your Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click "uploading an existing file"
2. Drag and drop all three files (`index.html`, `styles.css`, `script.js`)
3. Add a commit message like "Initial portfolio upload"
4. Click "Commit changes"

#### Option B: Using Git Command Line

```bash
# Navigate to your project folder
cd /path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click on **Settings** (top menu)
2. Scroll down to the **Pages** section (left sidebar)
3. Under "Source", select **main** branch
4. Leave the folder as **/ (root)**
5. Click **Save**
6. Wait a few minutes, then refresh the page
7. You'll see a message: "Your site is published at https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/"

### Step 4: Share Your Portfolio

Your portfolio will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

Share this link with your professor or anyone else!

## Customization Tips

### Change Colors
Edit the `:root` variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;  /* Main brand color */
    --secondary-color: #8b5cf6; /* Secondary brand color */
    --accent-color: #ec4899;    /* Accent color */
}
```

### Update Content
Edit `index.html` to change:
- Company name and tagline in the hero section
- About Us text and team statistics
- Service cards (the images use Unsplash URLs)
- Expertise skills and percentages
- Contact information

### Change Service Images
The images come from Unsplash. To change them:
```html
<!-- Find this in the Services section -->
<img src="https://images.unsplash.com/photo-xxxxx?w=800&h=500&fit=crop" alt="Service Name">

<!-- Replace the photo ID with a different Unsplash photo -->
```

### Update Team Photo
Replace the team image URL in the About Us section:
```html
<!-- Find this in index.html -->
<img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?w=600&h=600&fit=crop" alt="Our Team" class="team-image">
```

### Change Fonts
Add a Google Font in the `<head>` of `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

Then update the font-family in `styles.css`:
```css
body {
    font-family: 'Poppins', sans-serif;
}
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Optional Features

The JavaScript includes some optional features that are commented out:
- Cursor trail effect
- Typing effect for hero title
- Right-click prevention

To enable them, simply uncomment the relevant lines in `script.js`

## Performance

- Lightweight: Only ~40KB total
- No external dependencies
- Fast loading time
- Optimized animations
- Lazy loading ready

## License

Feel free to use this template for your corporate website or presentation!

## Credits

Created with ❤️ using modern web technologies and Unsplash images

---

**Pro Tips for Your Presentation:**

1. **Test the website** on different devices before showing it
2. **Practice navigating** through all sections smoothly
3. **Highlight the features**: responsive design, smooth animations, professional services showcase
4. **Mention the technology**: HTML5, CSS3, JavaScript, Unsplash API for images
5. **Show the corporate focus**: team-based approach, professional services, business-ready design
6. **Have the GitHub link ready** to share
7. **Emphasize the single-page design** - all links stay on the same page for better UX

Good luck with your presentation! 🚀