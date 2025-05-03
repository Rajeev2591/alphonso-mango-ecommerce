# Deployment Instructions for Jamuna Alphonso Mangoes Website

This document provides instructions to deploy the static website for Jamuna Alphonso Mangoes.

## Deploying on Netlify

1. Create a free account on [Netlify](https://www.netlify.com/).
2. Click on "Add new site" > "Deploy manually".
3. Drag and drop the project folder containing `index.html` and other files.
4. Set the custom domain to `jamunaalphonsomangoes.com` in the site settings.
5. Update your domain DNS records to point to Netlify's servers as per their instructions.

## Deploying on Vercel

1. Create a free account on [Vercel](https://vercel.com/).
2. Click on "New Project" and import your GitHub repository or upload files manually.
3. Set the root directory if needed.
4. Set the custom domain to `jamunaalphonsomangoes.com` in the project settings.
5. Update your domain DNS records to point to Vercel's servers as per their instructions.

## Notes

- Ensure all files are in the root directory or properly linked.
- For any issues, refer to the hosting platform's documentation.

## Local Development

To view the site locally, run:

```bash
python3 -m http.server 8000
```

and open `http://localhost:8000` in your browser.
