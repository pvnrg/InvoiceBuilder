# InvoiceBuilder (BillCraft)

A free, no-login invoice builder. Open the page and start editing the invoice directly, then download it as a PDF.

**Live:** https://pvnrg.github.io/InvoiceBuilder/

## Features

- No registration or login; the invoice opens straight in edit mode
- Editable business details, invoice number, date, client details and notes
- Logo upload
- Line items with quantity, rate and a per-line discount (flat ₹ or %)
- Automatic subtotal, total discount and grand total
- Amount in words (Indian lakh/crore format)
- Three colour themes
- Save Defaults, Sample and Clear buttons
- Download as an A4 PDF (falls back to the browser's print dialog)

## Usage

It is a single static file with no build step. Open `index.html` in a browser, or serve the folder with any static host.

## Data and privacy

Everything is stored in your own browser (localStorage). There is no backend, and nothing is sent to a server. Clearing browser data removes your saved invoice and defaults.

## Deploying

The site is hosted on GitHub Pages from the `main` branch (root folder). Pushing to `main` redeploys it.

## Tech

Plain HTML, CSS and JavaScript, plus [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) loaded from a CDN for PDF export.
