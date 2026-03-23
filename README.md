# ZamAI

<p align="center">
  <img src="./assets/logo.svg" alt="ZamAI logo" width="96" height="96" />
</p>

<p align="center">
  <strong>Home of Zeerak — the flagship AI assistant by ZamAI.</strong>
</p>

<p align="center">
  ZamAI is a growing AI ecosystem focused on intelligent assistants, digital products, tools, and future-facing experiences.
</p>

<p align="center">
  <a href="https://zamai.dev">Live Site</a>
  ·
  <a href="https://github.com/ZamAI/zamai.github.io">Website Repo</a>
</p>

---

## Overview

**ZamAI** is the public-facing organization and ecosystem behind **Zeerak**, the flagship AI assistant by ZamAI.

This repository contains the official public website for the ZamAI brand, including:
- the main landing page
- public-facing product messaging
- ecosystem positioning
- future showcase and documentation surfaces

The purpose of this repository is to provide a polished, professional public home for ZamAI while keeping Zeerak’s core implementation private.

### Brand Structure

- **ZamAI** → parent organization, ecosystem, and public identity
- **Zeerak** → flagship AI assistant by ZamAI

### Why ZamAI

ZamAI exists to bring multiple AI efforts under one strong identity:
- a unified public brand
- a flagship assistant product
- a scalable ecosystem for future tools and experiences
- a clean foundation for public website, docs, and launch surfaces

---

## Live Website

- **Production:** https://zamai.dev

---

## Repository Purpose

This repository is intended for:
- ZamAI landing page development
- public website updates
- branding and messaging
- future docs, showcase pages, and ecosystem content
- public-facing web assets

This repository does **not** contain:
- Zeerak’s private core source code
- private backend systems
- internal infrastructure or private model logic

---

## Tech Stack

This public website currently uses:

- **HTML**
- **Tailwind CSS** via CDN
- **Vanilla JavaScript**
- **GitHub Pages** for deployment

---

## Project Structure

```text
.
├── index.html
├── CNAME
├── README.md
└── assets/
    ├── favicon.svg
    ├── logo.svg
    └── og-image.png
```

---

## Getting Started

If you want to run or edit the website locally:

### 1. Clone the repository

```bash
git clone https://github.com/ZamAI/zamai.github.io.git
cd zamai.github.io
```

### 2. Open locally

Because this is currently a static site, you can open `index.html` directly in your browser.

For a better local development experience, you can also use a simple local server.

#### Option A: VS Code Live Server
If you use VS Code, install the **Live Server** extension and run the site from the repository root.

#### Option B: Python local server
```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

---

## Deployment

The site is deployed through **GitHub Pages**.

### Deployment flow

1. Push changes to the default branch
2. GitHub Pages publishes from the repository root
3. The custom domain points to the published site

### Current custom domain

- `zamai.dev`

### Required supporting files

- `CNAME` should contain:
```text
zamai.dev
```

---

## Making Changes Live

To update the live site:

1. Edit `index.html` or files inside `assets/`
2. Commit and push changes to the default branch
3. Wait for GitHub Pages to rebuild and deploy
4. Refresh `https://zamai.dev`

---

## Accessibility and SEO

The public site should continue improving in these areas:

### Accessibility goals
- semantic HTML structure
- readable contrast
- keyboard-accessible navigation
- clear headings and hierarchy
- meaningful alt text for future image assets

### SEO goals
- strong page title and meta description
- Open Graph and Twitter preview metadata
- branded custom domain
- clean information hierarchy
- future structured content for public product pages

---

## Roadmap

Planned improvements include:

- favicon and branding polish
- Open Graph social preview image
- dedicated Zeerak product page
- additional ecosystem/project pages
- improved SEO metadata
- docs or public release notes
- optional contact/waitlist flow
- expanded multi-page site structure

---

## Contributing

At the moment, this repository is primarily maintained by the ZamAI team.

If public collaboration opens later, contribution guidelines may include:
- submitting design/content improvements
- reporting bugs or broken links
- proposing public-facing website enhancements

For now, if you want to suggest improvements, open an issue or start a discussion in the repository when available.

---

## FAQ

### Is Zeerak open source?
Not at this time. Zeerak is presented publicly as the flagship assistant by ZamAI, while its core implementation remains private.

### What is public in this repository?
This repository contains the public ZamAI website, branding surfaces, and related public web assets.

### What is ZamAI?
ZamAI is the organization and ecosystem behind Zeerak and future AI tools, products, and digital experiences.

---

## Media

Planned public media assets may include:
- homepage screenshots
- social preview graphics
- product preview cards
- launch visuals for ZamAI and Zeerak

---

## Contributors

Currently maintained as part of the ZamAI launch and public brand setup.

Future contributor acknowledgements can be added here as the project grows.

---

## License

No license has been added yet.

If you plan to make parts of this repository openly reusable, consider adding an appropriate license later.

---

## Summary

**ZamAI** is the public home of **Zeerak** and the foundation for a broader AI ecosystem.

This repository exists to present that vision clearly, professionally, and publicly — while preserving the privacy of Zeerak’s core implementation.
