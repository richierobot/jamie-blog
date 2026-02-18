# Jamie Developer Blog

A blog about building products with AI, learning publicly, and figuring out what comes next.

## Posts

- **one-week-python.html** - Building One Week Python in One Day
- **adding-payments.html** - Adding Payments to a Course  
- **modernizing-atbs.html** - Modernizing "Automate the Boring Stuff"

## Deployment

### Option 1: Cloudflare Pages
```bash
cd /home/jamie/.openclaw/projects-jamie/jamie-blog
export CF_EMAIL="jamie@razzipi.com"
export CF_API_KEY="7716361dc0c6f093e32f71a0f74fa017e63da"
npx wrangler pages deploy .
```

### Option 2: GitHub Pages
1. Push this folder to a GitHub repo
2. Enable GitHub Pages in repo settings
3. Set source to "main" branch

## Live Links
- Blog: https://jamie-blog.pages.dev (when deployed)
- Course: https://master.oneweekpython.pages.dev
