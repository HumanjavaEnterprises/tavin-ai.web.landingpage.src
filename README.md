# tavin-ai.com

Landing page for [tavin-ai.com](https://tavin-ai.com), hosted on GitHub Pages.

## Setup

- **Repo:** [HumanjavaEnterprises/tavin-ai.web.landingpage.src](https://github.com/HumanjavaEnterprises/tavin-ai.web.landingpage.src)
- **Pages source:** `main` branch, `/docs` folder
- **Custom domain:** `tavin-ai.com`

## DNS Configuration

Point `tavin-ai.com` to GitHub Pages:

**A records** (apex domain):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME** (www subdomain):
```
www → humanjavaenterprises.github.io
```

Once DNS propagates, HTTPS is enforced automatically by GitHub Pages.
