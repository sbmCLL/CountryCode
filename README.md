# Country Calling Codes & ISO Lookup (Offline HTML)

A single-file HTML reference that lets users search **country calling codes** and **ISO country codes** (ISO 3166-1 alpha-2 / alpha-3) instantly — then jump to **CountryCode.online** for full dialing guides.

## What this project does

- ✅ Search by **country name** (e.g., `Japan`, `Congo`)
- ✅ Search by **calling code** (e.g., `+81`, `81`, `+1`)
- ✅ Search by **ISO2 / ISO3** (e.g., `JP`, `JPN`)
- ✅ Shows key fields: **calling code(s)**, **ISO2/ISO3**, **capital**, **continent**, **currency**, **languages**
- ✅ Click any result to open a detail modal and get a **direct link to CountryCode.online**

## Files

- `index.html` — everything (UI + dataset + search logic) in one file.

## Quick start

### Option A: Use it locally (offline)

1. Download `index.html`
2. Open it in any browser (Chrome / Edge / Firefox / Safari)

### Option B: Publish via GitHub Pages (recommended)

1. Create a new GitHub repo (example: `country-code-iso-lookup`)
2. Upload `index.html` to the repo root
3. Go to **Settings → Pages**
4. Select **Deploy from a branch** → `main` / `(root)` → **Save**
5. Your page will be available at `https://<your-username>.github.io/<repo>/`

## Customization

### Change the outbound links (backlinks)

Search for `https://countrycode.online/` inside `index.html` and replace it with your preferred URLs, e.g.:

- Country directory: `https://countrycode.online/countries/`
- Product / dataset page: `https://countrycode.online/product/all-country-code-list/`
- Tools: `/tools/world-time/`, `/tools/international-dialing/`, etc.

### Update the embedded dataset

The dataset is embedded as JSON inside:

```html
<script id="countries-data" type="application/json">...</script>
<script id="iso2to3-data" type="application/json">...</script>
```

### More Tools
<a href="https://imageconver.com/">Image Convert</a>: https://imageconver.com/

<a href="https://countrycode.online/">Country Code</a>: https://countrycode.online/

<a href="https://quickconver.com/">Country Code</a>: https://quickconver.com/

