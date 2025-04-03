# RTL Performance Dashboard

This repository hosts an iframe-based dashboard displaying RTL performance metrics from Madgicx.

## How to Enable GitHub Pages

To properly deploy this dashboard, you need to manually enable GitHub Pages in the repository settings:

1. Go to the repository settings page: [Repository Settings](https://github.com/growthack88/rtl-performance-dashboard/settings)
2. Scroll down to the "Pages" section in the left sidebar
3. Under "Build and deployment":
   - For "Source", select "GitHub Actions"
4. Save the settings

After enabling GitHub Pages, the Actions workflow will automatically deploy the site. The deployment may take a few minutes to complete.

## Accessing the Dashboard

Once deployed, the dashboard will be available at: https://growthack88.github.io/rtl-performance-dashboard/

The dashboard embeds a Madgicx report in an iframe, displaying it in full-screen mode with a simple loading indicator.

## Troubleshooting

If the GitHub Pages deployment fails, ensure that:
1. The repository has GitHub Pages enabled as described above
2. The workflow file (.github/workflows/static.yml) is properly configured
3. The iframe URL is accessible and properly formatted
