# CISNOLA Dashboard

This repository contains the CISNOLA Dashboard website, designed to visualize data from Communities In Schools Gulf South.

###
HOW TO UPDATE:

SEE PDF NAMED: Update_annual.pdf

## Project Structure

- `index.html` - Main homepage that integrates all dashboard content
- `css/` - Contains stylesheets
  - `styles.css` - Main stylesheet for the entire website
- `js/` - Contains JavaScript files
  - `navigation.js` - Handles navigation functionality
  - `charts.js` - Handles chart rendering and data processing
- `images/` - Contains image assets
- `dashboards/` - Contains individual dashboard pages
  - `caseload.html` - Caseload Buildup dashboard
  - (other dashboard pages to be added)

## Data Sources

The dashboard uses CSV data from the following GitHub repository.

## Deployment Instructions

To deploy this website to GitHub Pages:

1. Push all files to your GitHub repository.

2. Go to your repository on GitHub.

3. Navigate to Settings → Pages.

4. Under "Source", select the branch (main) and set the folder to either:
   - `/` (root) - If you want to serve files directly from the repository root
   - `/docs` - If you want to move all files to a docs folder first

5. Click "Save".

6. GitHub will provide you with a URL like:
   https://<username>.github.io/<repo-name>/

7. Your website will be published at this URL. It may take a few minutes for changes to appear.

## Local Development

To run this website locally:

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

## Browser Compatibility

This website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)