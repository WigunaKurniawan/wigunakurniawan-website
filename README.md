# Wiguna Kurniawan Personal Website

Welcome to the repository for **Wiguna Kurniawan's Personal Website**! This project is hosted on GitHub Pages and can be accessed via the custom domain [wigunakurniawan.com](https://wigunakurniawan.com).

## Project Overview

This website serves as a personal portfolio for Wiguna Kurniawan, showcasing professional skills, services offered, and a portfolio of completed projects. Built with HTML, CSS, and JavaScript, it is designed to be simple, professional, and responsive.

## Features

- **Responsive Design**: The website is optimized for viewing on various devices, from desktops to mobile phones.
- **Portfolio Section**: Highlights key projects and accomplishments.
- **Service Offerings**: Lists the primary services provided, such as Data Analytics, Microsoft 365 Migration, and Custom Dashboard Development.
- **Contact Form**: Allows visitors to get in touch with Wiguna Kurniawan directly.

## Getting Started

To view or edit the website locally, you can clone this repository and open the files in your preferred code editor.

### Clone the Repository

```bash
git clone https://github.com/WigunaKurniawan/wigunakurniawan-website.git
```

## Structure
The project structure is as follows:
```
wigunakurniawan-website/
├── index.html         # Main HTML file
├── assets/            # Folder for assets like CSS, JS, and images
│   ├── css/
│   │   └── style.css  # Stylesheet
│   ├── js/
│   │   └── script.js  # JavaScript (if any)
│   └── images/        # Folder for images used on the site
├── CNAME              # Custom domain configuration for GitHub Pages
├── README.md          # Project README file
└── LICENSE            # License file
```
## Deploying the Site
The website is hosted on GitHub Pages. Any changes pushed to the main branch will automatically deploy to GitHub Pages and be live within minutes.

1. Make Changes: Update the code or content in your local repository.
2. Commit and Push:
   ```
   git add .
   git commit -m "Your commit message"
   git push origin main
  ```

3. Check Deployment: The site should update at wigunakurniawan.com after a few minutes.

## Custom Domain Setup

This repository uses a custom domain, wigunakurniawan.com, which is configured with GitHub Pages.
Ensure the file CNAME exists in the root directory with the content:
```
wigunakurniawan.com
```

The following DNS settings are required for GitHub Pages to recognize the custom domain:

A Records:
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
CNAME Record:
www pointing to wigunakurniawan.com
Note: It may take up to 24 hours for DNS changes to propagate fully.

## Issues and Troubleshooting
If the website does not display as expected, consider the following troubleshooting steps:

1. Ensure DNS settings are correct and fully propagated.
2. Check the GitHub Pages settings in the repository to make sure the custom domain is properly configured.
3. If HTTPS is unavailable, verify that DNS records are correctly pointing to GitHub Pages.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

