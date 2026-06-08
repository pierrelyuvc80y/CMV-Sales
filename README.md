# CHEMI Vietnam — Sales Report PWA

Mobile sales dashboard for CHEMI Vietnam, installable as an Android app.

## Installation on Android

1. Open Chrome on your Android phone
2. Navigate to the GitHub Pages URL of this repo
3. Chrome will show **"Add to Home Screen"** banner — tap it
4. The app installs like a native app

## Files

| File | Role |
|------|------|
| `index.html` | Main app (all HTML + JS + CSS) |
| `manifest.json` | PWA manifest (name, icons, colors) |
| `sw.js` | Service Worker (offline cache) |
| `icons/` | App icons 192×192 and 512×512 |
| `Sales_export_file.xlsx` | Data source |

## Data

The app automatically loads `Sales_export_file.xlsx` from the same GitHub Pages folder.  
You can also load a file manually via the **File** tab.

## Features

- **KPIs**: Total Qty, Amount, Avg price, SF/F split
- **Trend**: Monthly & yearly charts by type and index
- **Clients**: Treemap + top client rankings
- **Products**: Pie charts + top 10 products
- **Filters**: Year, Customer, SF/F, Index (1.56/1.60/1.67/1.74), IC/IG/OG

## Enable GitHub Pages

In your repo settings → Pages → Source: **main branch / root**
