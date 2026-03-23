# B&Sh Creative House — Website

البيت الإبداعي — الموقع الرسمي

## Files

```
bsh-website/
├── index.html          ← Main website (HTML + CSS + JS all-in-one)
├── 404.html            ← Custom 404 error page
├── favicon.svg         ← Vector favicon (modern browsers)
├── favicon-32.png      ← 32x32 favicon
├── favicon-16.png      ← 16x16 favicon
├── apple-touch-icon.png← 180x180 iOS icon
├── apple-touch-icon.svg← Vector iOS icon
├── og-image.png        ← Social sharing image (1200x630)
├── robots.txt          ← SEO crawl rules
├── sitemap.xml         ← SEO sitemap
├── netlify.toml        ← Netlify config
├── _redirects          ← Netlify redirects
├── _headers            ← Netlify security headers
├── vercel.json         ← Vercel config
└── README.md           ← This file
```

## Deploy

### Option 1: Netlify (Recommended — Free)
1. Go to https://app.netlify.com
2. Drag and drop the entire `bsh-website` folder
3. Done! Your site is live.

### Option 2: Vercel (Free)
1. Go to https://vercel.com
2. Import the folder or connect to GitHub
3. Deploy automatically.

### Option 3: GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages → Source: main branch
4. Your site will be at `username.github.io/repo-name`

### Option 4: Any Web Hosting
1. Upload all files via FTP/cPanel to your `public_html` folder
2. Done!

## Custom Domain
After deploying, connect your custom domain:
- Add CNAME record pointing to your hosting provider
- Or add A records as specified by your host
- Update `og:url` and `canonical` in index.html with your actual domain

## Editing Prices
Search for `100 SAR` in index.html to find and update individual prices.

## Contact Info
- Email: BshCHBsh@gmail.com
- Phone: +966 50 253 2550
- Instagram: @bsh.ch1
- TikTok: @bsh.creative.house
