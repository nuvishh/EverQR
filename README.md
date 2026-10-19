# EverQR — Free Static QR Code Generator

*Your QR. Your Style. No Expiry.*

Generate **fully static QR codes that never expire** — customize colors, module styles, add your logo, and download as PNG or SVG. 100% client-side: your data never leaves the browser.

## Why "never expires"?

Most online QR generators create **dynamic** QR codes — the QR points to *their* server, which redirects to your link. Stop paying (or the service shuts down) and your QR dies.

EverQR generates **static** QR codes: your content is encoded *directly* into the QR image. No servers, no accounts, no redirects — nothing to expire. Ever.

## Features

- **Content types** — Link/Text, WiFi, vCard contact, Email, Phone, SMS
- **Customize** — QR color, background color, 3 module styles (square / rounded / dots)
- **Sizes** — 512 / 1024 / 2048 px PNG export, plus vector SVG
- **Center logo** — upload your logo (use Q/H error correction for best scans)
- **Download** — PNG, SVG, or copy to clipboard
- **Offline** — single page, zero external requests after load

## Tech

Single `index.html` + `qrcode.min.js` (qrcode-generator, MIT). Canvas rendering for PNG, hand-built SVG export. No build step, no dependencies to install.

## Host it

Any static host works — GitHub Pages, Netlify, Vercel, or just open `index.html` locally.

## License

MIT
