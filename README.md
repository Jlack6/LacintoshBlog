# Lacintosh Blog

A personal blog about software testing, quality assurance, and career insights by James Lack.

## About

Welcome to Lacintosh, your go-to source for software testing and quality assurance insights. This blog covers topics including:

- Test automation
- Agile testing
- Continuous integration
- Test management
- Quality assurance best practices
- Career experiences in QA

## Features

- **Articles**: Personal insights and experiences in QA
- **About Me**: Background and career journey
- **Scrib Notes**: Information about the Scrib Notes iOS app

## Deployment

This site is deployed using GitHub Pages with GitHub Actions for automatic deployment. The deployment process:

1. **Automatic Deployment**: Every push to the `main` branch triggers an automatic deployment
2. **GitHub Actions**: Uses the workflow in `.github/workflows/deploy.yml`
3. **Source Directory**: Files are served from the `public` directory
4. **URL**: The site will be available at `https://[your-username].github.io/LacintoshBlog`

### Setting up GitHub Pages

1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** section
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically deploy your site when you push to the main branch

### Manual Deployment

You can also trigger a manual deployment by:
1. Going to the **Actions** tab in your repository
2. Selecting the "Deploy to GitHub Pages" workflow
3. Clicking **Run workflow**

## Local Development

To run this site locally:

1. Clone the repository
2. Open `public/index.html` in your web browser
3. Or use a local server like `python -m http.server` in the `public` directory

## License

This project is open source and available under the [MIT License](LICENSE).
