# QR & Barcode Tools

A small, self-contained web app to read QR codes and barcodes with your device camera, and to generate styled QR codes as SVG.

**Live app: https://www.tintamarre.be/qr-code/**

## Features

- **Read** — scan QR codes and barcodes (EAN-13, Code 128, UPC, etc.) using the camera.
- **ISBN book lookup** — when a scanned barcode is a book ISBN, the app fetches the reference (title, author, publisher, year, summary, cover) from the [BnF](https://catalogue.bnf.fr) (best coverage for French books), falling back to Google Books and Open Library.
- **Generate** — create a QR code from text or a URL, pick a style preset, and download it as SVG.

## Usage

It's a single `index.html` file with no build step. Open it over **HTTPS** (required for camera access) — either the live link above or your own host.
