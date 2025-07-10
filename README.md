# Web Blocking Page

A simple, clean blocking page for websites that displays when content is blocked by focus settings or parental controls.

## Features

- Clean, modern design with Apple-inspired styling
- Responsive layout that works on all devices
- Minimal and distraction-free interface
- Ready for GitHub Pages deployment

## GitHub Pages Setup

This project is configured to work with GitHub Pages and a custom domain.

### Custom Domain Configuration

The site is configured to use the custom domain: `blocked.marthin.web.id`

### Deployment Steps

1. Push this repository to GitHub
2. Go to your repository settings
3. Navigate to "Pages" section
4. Set source to "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. The custom domain should be automatically detected from the CNAME file
7. Ensure your DNS is configured to point `blocked.marthin.web.id` to your GitHub Pages site

### DNS Configuration

For the custom domain to work, you need to configure your DNS:

- Create a CNAME record pointing `blocked.marthin.web.id` to `yourusername.github.io`
- Or create A records pointing to GitHub Pages IP addresses:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

## File Structure

```
.
├── index.html    # Main blocking page
├── CNAME         # Custom domain configuration
└── README.md     # This file
```

## Usage

Once deployed, this page can be used as a redirect target for blocked websites in:
- Browser extensions
- Parental control software
- Network-level blocking solutions
- Focus and productivity apps

## Customization

You can customize the blocking message by editing the `index.html` file. The current styling uses a clean, Apple-inspired design that's easy on the eyes.