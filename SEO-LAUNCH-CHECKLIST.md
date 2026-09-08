# 🔍 SEO Launch Checklist — Godinez Landscaping & Lawn Care

## ✅ Already Done (in the website)

- [x] Title tag optimized with primary + secondary keywords + city
- [x] Meta description with all target cities and service keywords
- [x] `<meta name="robots" content="index,follow,max-snippet:-1,max-image-preview:large"/>` — unlocks rich previews in Google
- [x] Geo meta tags (`geo.region`, `geo.placename`, `geo.position`, `ICBM`) — signals location to search engines
- [x] Canonical URL tag
- [x] Open Graph tags (Facebook / LinkedIn sharing)
- [x] Twitter Card tags
- [x] JSON-LD Schema: **LawnCareService + LocalBusiness** (with areaServed, geo coordinates, hours, pricing, ratings)
- [x] JSON-LD Schema: **FAQPage** — FAQ answers may appear as rich results in Google
- [x] JSON-LD Schema: **WebSite + BreadcrumbList**
- [x] Schema reviews with author, rating, and publisher
- [x] NAP block in footer with microdata (`itemscope`, `itemprop`) — name, address, phone must match Google Business Profile exactly
- [x] City-by-city service articles (Galt, Elk Grove, Lodi, Herald, Wilton, Rancho Murieta) with `itemprop` markup
- [x] Sacramento Valley local keyword prose paragraph (zip codes, city names, "lawn care near me" variations)
- [x] All images have descriptive `alt` text with city + service keywords
- [x] `sitemap.xml` with lastmod dates
- [x] `robots.txt` pointing to sitemap

---

## 🔧 Do These Before Launch (takes ~1 hour total)

### 1. Replace All Placeholders in index.html (5 min)
Find and replace every instance of:
- `yourdomain.com` → your real domain
- `(209) 555-0100` → your real phone number
- `info@yourdomain.com` → your real email
- `YOUR_WEB3FORMS_ACCESS_KEY` → key from web3forms.com

### 2. Update sitemap.xml (2 min)
Replace `yourdomain.com` with your real domain in `sitemap.xml`.
Update `<lastmod>` dates whenever you make content changes.

### 3. Create an OG Image (15 min)
Create a 1200×630px image (use Canva free tier):
- Green background with lawn photo
- Logo: "Godinez Landscaping & Lawn Care"
- Tagline: "Serving Galt, Elk Grove & Sacramento County"
- Save as `og-image.jpg`, upload to root of your GitHub repo
This image shows when people share your site on social media.

---

## 🚀 After Launch — Do These Within the First Week

### 4. Google Search Console (most important — free, 10 min)
1. Go to **search.google.com/search-console**
2. Add property → Domain → enter `yourdomain.com`
3. Verify via DNS record (GitHub Pages: add TXT record in your domain registrar)
4. Once verified → Sitemaps → enter `https://yourdomain.com/sitemap.xml` → Submit
5. Come back in 3–5 days and check **Coverage** for any indexing errors

### 5. Google Business Profile (most important for local — free, 20 min)
This is what makes you show up in **Google Maps** and the **local 3-pack** (the map results at the top of "lawn care near me" searches).
1. Go to **business.google.com**
2. Search your business name → Claim or Create listing
3. **CRITICAL:** Use the EXACT same business name, address, and phone number as in your website footer:
   - Name: `Godinez Landscaping & Lawn Care`
   - Address: Galt, CA 95632
   - Phone: (209) 555-0100
4. Add your website URL, hours, services (match the site exactly)
5. Upload photos — use your own yard before/afters
6. Set service area cities: Galt, Elk Grove, Lodi, Herald, Wilton, Rancho Murieta, Sacramento County

### 6. Bing Webmaster Tools (free, 5 min)
1. Go to **bing.com/webmasters**
2. Sign in with Microsoft account
3. Add site → import from Google Search Console (one-click if already set up)
Bing/Yahoo still accounts for ~6% of US searches — worth doing.

### 7. Yelp Business Listing (free, 15 min)
1. **biz.yelp.com** → Add your business
2. Use same NAP (name, address, phone) as Google Business Profile
3. Select categories: Landscaping, Lawn Services
4. Add service area cities

### 8. Nextdoor Business Page (free, 10 min)
Nextdoor is huge for hyperlocal lawn care leads in Galt and Elk Grove specifically.
1. **business.nextdoor.com** → Create a free Local Deal page
2. Target neighborhoods: Galt, Elk Grove, Lodi, Herald, Wilton

---

## 📈 Ongoing — Monthly Actions for Better Rankings

| Action | Why | Time |
|---|---|---|
| Ask happy customers for Google reviews | #1 local ranking factor | Ongoing |
| Post 1–2 before/after photos to GBP monthly | Signals activity to Google | 5 min/mo |
| Update `<lastmod>` in sitemap when you edit content | Tells Google to re-crawl | 1 min |
| Add real before/after photos to the site gallery | Improves dwell time & trust | As available |
| Reply to every Google review (good and bad) | Shows engagement, boosts trust | Ongoing |

---

## 🔑 Target Keywords by Priority

### Tier 1 — Highest Intent (people ready to hire)
- `lawn care Galt CA`
- `lawn mowing Galt CA`
- `landscaping Elk Grove CA`
- `lawn service near me Galt`
- `yard cleanup Galt CA`

### Tier 2 — High Volume
- `lawn mowing Elk Grove`
- `landscaping Lodi CA`
- `lawn care Sacramento County`
- `bush trimming Elk Grove CA`
- `lawn mowing near me` (+ your GBP location = Galt)

### Tier 3 — Long-tail (easier to rank, convert well)
- `affordable lawn care Galt California`
- `residential landscaping Elk Grove no contract`
- `lawn mowing service Herald CA`
- `yard cleanup Wilton California`
- `weekly lawn mowing Elk Grove CA`

---

## 🔎 How to Check Your Rankings (free)

- **Google:** Search `lawn care Galt CA` in an incognito window (so your own visit history doesn't skew results)
- **Google Search Console:** Performance tab → shows which queries you appear for and your average position
- **Google Business Profile:** Insights tab → shows how many people found you via Maps search

---

## 📞 NAP Consistency Rule
Your Name, Address, and Phone must be **100% identical** everywhere:
- Website footer
- Google Business Profile
- Yelp
- Nextdoor
- Any directory listing

Even small differences (St. vs Street, LLC vs L&LC) can confuse Google's local algorithm. Pick one format and stick to it everywhere.
