# Albert Roi

Luxury perfume brand landing page — reached via QR code on product packaging.

**Live site:** https://dr-yahya.github.io/albert-roi/  
**Custom domain (pending DNS):** https://albert-roi.ae.kg/

## Custom domain setup

The repo is configured for `albert-roi.ae.kg`. Complete these steps to activate it:

### 1. Free DNS — Hurricane Electric

1. Create a free account at [dns.he.net](https://dns.he.net/)
2. **Add a new domain** → enter `albert-roi.ae.kg`
3. Add a **CNAME** record:
   - **Name:** `@`
   - **Target:** `dr-yahya.github.io`
4. Note your nameservers: `ns1.he.net`, `ns2.he.net` (and `ns3`–`ns5` if shown)

### 2. Register subdomain — Kevin Service

1. Sign in at [registry.kevsrv.me](https://registry.kevsrv.me) (Google login works)
2. **Register Domain** → search `albert-roi` under `.ae.kg`
3. Enter Hurricane Electric nameservers from step 1
4. Purpose: brand landing page for open-source perfume project  
   GitHub repo: `https://github.com/dr-yahya/albert-roi`

### 3. GitHub Pages

1. Open [Pages settings](https://github.com/dr-yahya/albert-roi/settings/pages)
2. **Custom domain:** `albert-roi.ae.kg` → Save
3. Wait for DNS check (up to 24 h), then enable **Enforce HTTPS**

The `CNAME` file in this repo is already set. QR codes in `qr/` point to the new domain.

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Project docs

Domain and product terminology: [CONTEXT.md](./CONTEXT.md)
