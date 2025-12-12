# GitHub Pages Deployment Instructions

This repository is set up as a GitHub Pages website for the CS 566 Optimized Disaster Analysis project.

## 🌐 Accessing the Website

Once GitHub Pages is enabled, your website will be available at:
```
https://anish-c.github.io/Optimized_disaster_analysis/
```

## ⚙️ How to Enable GitHub Pages

To deploy this website, follow these steps:

1. **Go to Repository Settings**
   - Navigate to your repository on GitHub
   - Click on "Settings" tab

2. **Enable GitHub Pages**
   - In the left sidebar, click on "Pages"
   - Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/create-github-pages-website`)
   - Select the root folder (`/ (root)`) as the source directory
   - Click "Save"

3. **Wait for Deployment**
   - GitHub will automatically build and deploy your site
   - This usually takes 1-2 minutes
   - You'll see a green checkmark and a URL when it's ready

## 📁 Website Structure

The website consists of the following files:

- **index.html** - Main HTML page with all content sections
- **styles.css** - CSS stylesheet for professional styling
- **.nojekyll** - Tells GitHub Pages to skip Jekyll processing

## 🎨 Website Features

The website includes:

- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Navigation Menu** - Easy access to different sections
- **Hero Section** - Eye-catching introduction
- **Project Overview** - Detailed description with feature cards
- **Methodology** - Explanation of approach and training
- **Results** - Key findings and achievements
- **Contact Section** - Links to GitHub repository

## 🔧 Customization

To customize the website:

1. **Edit Content**: Modify `index.html` to update text, add images, or change structure
2. **Update Styling**: Edit `styles.css` to change colors, fonts, or layout
3. **Add Pages**: Create additional HTML files and link them in the navigation

## 📝 Updating the Website

After making changes:

1. Commit your changes to the repository
2. Push to GitHub
3. GitHub Pages will automatically rebuild and deploy your site
4. Changes typically appear within 1-2 minutes

## 🚀 Testing Locally

To test the website on your local machine before deploying:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have npx)
npx http-server
```

Then open your browser to `http://localhost:8000`

## 📱 Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file with your domain name
2. Configure your domain's DNS settings
3. Update settings in GitHub Pages settings

## ✨ Next Steps

Consider adding:
- Project images or screenshots
- Interactive demos or visualizations
- Research paper or documentation links
- Team member information
- Embedded videos or presentations
- Dataset information and examples

## 🔗 Useful Links

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Tutorial](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Tutorial](https://developer.mozilla.org/en-US/docs/Web/CSS)
