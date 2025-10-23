# FairGo Website

Static website built with Framer for FairGo.

## Deployment

This site is configured for deployment on Vercel from the repository root.

### Local Development

```bash
npm install
npm run dev
```

### Vercel Deployment

The deployment is configured from the repository root with `vercel.json` that:
- Serves the static website files from the root directory
- Redirects asset requests to the Framer CDN
- Ignores admin, backend, and other directories

### Structure

- `index.html` - Homepage
- `about.html` - About page
- `blog.html` - Blog listing
- `blog/` - Individual blog posts
- `contact.html` - Contact page
- `pricing.html` - Pricing page
- `privacy.html` - Privacy policy
- `terms.html` - Terms of service

