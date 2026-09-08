# Green Edge Lawn Care — Single-File Website

Single `index.html` site following the small-business-site skill pattern.
Everything is self-contained — one file to upload, one file to maintain.

---

## 📁 File Structure

```
greenedge/
├── index.html     ← Entire website (HTML + CSS + JS in one file)
├── sitemap.xml    ← SEO sitemap
├── robots.txt     ← SEO crawler file
└── images/        ← Add your own photos here (optional)
```

---

## 📧 Web3Forms Setup (FREE — Unlimited Submissions)

1. Go to **https://web3forms.com**
2. Enter your email address → click **Get Access Key**
3. Copy the access key (looks like: `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`)
4. Open `index.html` — find this line (around the contact form section):
   ```html
   <input type="hidden" name="access_key" value="YOUR_WEB3FORMS_ACCESS_KEY" />
   ```
5. Replace `YOUR_WEB3FORMS_ACCESS_KEY` with your actual key
6. Save and push to GitHub

✅ All form submissions will be emailed to your Web3Forms email address.
✅ Free tier: **unlimited** submissions — no monthly cap.
✅ Built-in spam protection via honeypot field.

---

## 🚀 GitHub Pages Setup

1. Create a new GitHub repo (e.g. `greenedgelawncare`)
2. Upload `index.html`, `sitemap.xml`, `robots.txt`, and the `images/` folder
3. Go to **Settings → Pages**
4. Source: **Deploy from branch → main → / (root)**
5. Click Save — live at `https://yourusername.github.io/greenedgelawncare`

### Custom Domain (Namecheap ~$10/yr):
Add these DNS records in Namecheap → Advanced DNS:

| Type  | Host | Value                | TTL  |
|-------|------|----------------------|------|
| A     | @    | 185.199.108.153      | Auto |
| A     | @    | 185.199.109.153      | Auto |
| A     | @    | 185.199.110.153      | Auto |
| A     | @    | 185.199.111.153      | Auto |
| CNAME | www  | yourusername.github.io | Auto |

Then in GitHub: **Settings → Pages → Custom domain** → enter domain → **Enforce HTTPS**.

---

## ✏️ Customization Checklist

Search for `<!-- CUSTOMIZE:` comments in `index.html` to find all edit points:

- [ ] `<title>` — business name
- [ ] Meta description — update city and services
- [ ] `https://yourdomain.com` — replace with actual domain (4 places)
- [ ] Phone: `(209) 555-0100` → your real number
- [ ] Email: `info@yourdomain.com` → your real email
- [ ] Web3Forms access key
- [ ] Hero pill status line (e.g. "Now Taking New Clients")
- [ ] Hero title and subtitle
- [ ] Stats in the trust bar (500+ lawns, 8+ years, etc.)
- [ ] About section text
- [ ] Service cards — edit or remove any
- [ ] Gallery images — replace Unsplash URLs with your real photos
- [ ] Service area city chips
- [ ] Testimonials — replace with real Google reviews
- [ ] FAQ items
- [ ] Footer tagline and contact info
- [ ] Privacy modal — business name and domain
- [ ] Schema JSON-LD at top of file (phone, address, services)

---

## 📸 Adding Your Own Photos

Place photos in an `images/` folder next to `index.html`.
Reference them in the gallery strip like:
```html
<img src="images/my-yard-before.jpg" alt="Lawn before cleanup Galt CA" />
```

**Recommended sizes:**
- Hero background: 1400px wide, ~150KB
- Gallery cards: 680px wide, ~80–120KB

---

## 🔍 SEO After Launch

1. **Google Search Console**: submit your sitemap at `https://yourdomain.com/sitemap.xml`
2. **Google Business Profile**: claim at `https://business.google.com` — critical for local SEO
3. **Nextdoor**: register as a local business — great for Galt/Elk Grove neighborhoods
4. **Yelp**: create a free business listing
