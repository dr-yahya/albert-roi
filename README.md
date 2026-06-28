# Albert Roi

Luxury perfume brand landing page — reached via QR code on product packaging.

**Live site:** https://dr-yahya.github.io/albert-roi/  
**Custom domain:** https://albert-roi.com/

## Domain setup (GitHub Pages)

The repo `CNAME` file is set to `albert-roi.com`. At your domain registrar, add:

### Apex domain (`albert-roi.com`)

```
A    @    185.199.108.153
A    @    185.199.109.153
A    @    185.199.110.153
A    @    185.199.111.153
```

### Optional `www`

```
CNAME    www    dr-yahya.github.io
```

### GitHub Pages

1. Open [Pages settings](https://github.com/dr-yahya/albert-roi/settings/pages)
2. **Custom domain:** `albert-roi.com` → Save
3. Wait for DNS verification, then enable **Enforce HTTPS**

QR codes in `qr/` point to **https://albert-roi.com/**.

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Project docs

Domain and product terminology: [CONTEXT.md](./CONTEXT.md)
