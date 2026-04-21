# protectorium-personal-site

Static personal site for Lev Menshchikov.

## Target host

- `levmenshchikov.protectorium.com`

## Files

- `index.html` — personal homepage
- `blog/index.html` — blog landing page
- `blog/why-claims-should-compile.html` — local essay
- `blog/security-products-should-not-panic.html` — local essay
- `styles.css` — shared styles for home and blog
- `images/Lev.jpg` — portrait photo
- `images/protectorium-logo.png` — favicon and logo source
- `social-card.svg` — Open Graph preview image

## Local preview

```bash
cd /root/protectorium-personal-site
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Current profile data

- Name: `Lev Menshchikov`
- Role: `Co-Founder & CEO at Protectorium.com`
- Email: `lev.menshchikov@protectorium.com`
- GitHub: `https://github.com/Nurnberg-Meistersinger`
- LinkedIn: `https://www.linkedin.com/in/hilaymanai/`
- Twitter: `https://x.com/Hilaymanai`

## Note about deployment

The site files are ready for the `levmenshchikov.protectorium.com` subdomain,
but actual DNS and web-server routing still need to be configured outside this
project folder.
