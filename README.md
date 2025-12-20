# Optimized Disaster Analysis

This repository contains a computer vision pipeline for disaster imagery analysis using transfer learning and uncertainty quantification.

## GitHub Pages

The project documentation is deployed via GitHub Pages at: **https://Anish-C.github.io/Optimized_disaster_analysis/**

### Website Structure

- **`index.html`** - Main project documentation page with full writeup
- **`styles.css`** - Dark-themed styling for the documentation
- **`.github/workflows/pages.yml`** - GitHub Actions workflow for automatic deployment

### Viewing the Site

The website includes:
- Project overview and methodology
- Dataset description
- Model architecture details
- Uncertainty quantification techniques
- Results and analysis examples
- Interactive navigation with Grad-CAM visualizations
- Mathematical rendering with KaTeX

### Local Testing

To test the website locally before deployment:

1. Start a simple HTTP server in the repository root:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Or Python 2
   python -m SimpleHTTPServer 8000
   ```

2. Open `http://localhost:8000` in your browser

### Deployment

The site automatically deploys on every push to the `main` branch via the GitHub Actions workflow in `.github/workflows/pages.yml`.

To enable GitHub Pages:
1. Go to repository **Settings** > **Pages**
2. Ensure **Source** is set to `GitHub Actions`
3. The workflow will handle the rest automatically

## Project Files

- **`files/CLEAN_PROJECT/`** - Main Python implementation
- **`files/CLEAN_PROJECT/analyze_real_images.py`** - Image analysis script
- **`files/CLEAN_PROJECT/analysis_results/`** - Generated analysis outputs
- **`data/`** - Dataset directory

## License

© 2025 Disaster Response CV Analyzer
