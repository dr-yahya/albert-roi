# Albert Roi

Luxury perfume brand landing page — reached via QR code on product packaging.

**Live site:** https://albert-roi.com/  
**GitHub Pages:** https://dr-yahya.github.io/albert-roi/

## Project structure

```
├── assets/
│   ├── images/          # Product photography
│   │   ├── masculine-variant.png
│   │   └── feminine-variant.png
│   └── packaging/       # Print-ready barcodes
│       ├── qr.png / qr.svg
│       ├── ean13-masculine.png / .svg
│       └── ean13-feminine.png / .svg
├── css/style.css
├── index.html
├── CNAME
├── robots.txt
└── sitemap.xml
```

## Packaging assets

| File | Use |
|------|-----|
| `assets/packaging/qr.png` | QR code → https://albert-roi.com/ |
| `assets/packaging/ean13-masculine.*` | EAN-13 for black & gold box |
| `assets/packaging/ean13-feminine.*` | EAN-13 for white & gold box |

## Domain setup

DNS records for `albert-roi.com`:

```
A    @    185.199.108.153
A    @    185.199.109.153
A    @    185.199.110.153
A    @    185.199.111.153
```

Optional `www`: `CNAME www dr-yahya.github.io`

Enable the custom domain in [GitHub Pages settings](https://github.com/dr-yahya/albert-roi/settings/pages).

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Docs

Product terminology: [CONTEXT.md](./CONTEXT.md)
