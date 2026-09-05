# Stock Manager Medical & Pharmacy

Installable, offline-first inventory for one pharmacy counter.

## First release

- Medicine, company, category and price entry
- Separate batch, expiry month and quantity tracking
- Stock-in, stock-out and physical-count corrections with movement history
- Low-stock, out-of-stock, 90-day expiry and expired alerts
- Search, alert filters, JSON backup and restore
- PWA manifest and offline service worker
- Versioned local schema ready for a future cloud sync adapter

## Run and test

```bash
python3 -m http.server 8080
npm run check
```

Open `http://localhost:8080`. Inventory is stored in the browser under `stock-manager:v1`; clearing site data removes it, so export regular backups. This release stores no patient information.
