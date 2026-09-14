# FinFeed Store

A small customer-facing storefront for **FinFeed**, a family-run seller of premium fish feed for aquariums, koi ponds and small fish farms.

## What's here

- `index.html` &mdash; the single-page storefront (hero, best-seller grid, about, contact).

## Product range

| SKU | Product | Price |
|-----|---------|-------|
| FF-SP1 | Sinking Pellets 1kg | $14.99 |
| FF-TF2 | Tropical Flakes 200g | $8.49 |
| FF-KS5 | Koi Growth Sticks 5kg | $39.00 |
| FF-FS1 | Fry Starter 100g | $6.25 |

## Running locally

Serve the storefront over HTTP so the live availability badge can fetch `availability.json`:

```bash
cd /home/runner/work/finfeed-store/finfeed-store
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Roadmap

- Live per-product availability badge
- Cart + checkout
- Subscription auto-refill

---
&copy; 2026 FinFeed Ltd. Free shipping on orders over $45.
