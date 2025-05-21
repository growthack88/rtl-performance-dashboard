# Read to Lead | Performance Report

This repository hosts a password-protected dashboard displaying Read to Lead performance metrics from Madgicx.

## Features

- **Password Protection**: Access to the dashboard requires the password "rtl2025"
- **Data Privacy**: Dashboard content is blurred and dimmed until valid password is entered
- **Responsive Design**: Works on desktop and mobile devices
- **Full-Screen Display**: Maximizes the viewing area for the performance report
- **Loading Indicator**: Shows a loading message while the report is being loaded
- **Smooth Transitions**: Elegant visual effects when loading and accessing the dashboard

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

You will need to enter the password "rtl2025" to access the performance report. The dashboard content will be blurred and dimmed until the correct password is entered, ensuring that metrics and sensitive data are not visible to unauthorized users.

## Password Information

- Default password: `rtl2025`
- The password authentication is implemented using client-side JavaScript
- Authentication is stored in the browser's session storage, so users will need to re-enter the password if they close the browser
- Dashboard metrics are visually obscured until authentication is complete

## Troubleshooting

If the GitHub Pages deployment fails, ensure that:
1. The repository has GitHub Pages enabled as described above
2. The workflow file (.github/workflows/static.yml) is properly configured
3. The iframe URL is accessible and properly formatted
