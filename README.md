# دليلك — Daliluka
مساعد إلكتروني للبحث عن خدمات صحية واجتماعية في لبنان.

## Architecture
- JSON runtime files exported by Apps Script → Cloudflare CDN
- Browser loads from CDN first, falls back to Google Sheets
- Services cached locally in localStorage
- Zero Google Sheets calls during conversations
