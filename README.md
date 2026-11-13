# Awesome-Digital-Document-E-Book-Reader

## Top Digital Document & E-Book Reader Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on PDF/EPUB Viewing, Annotation & Library Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Document & E-Book Readers**. These tools help users read, annotate, and manage PDFs, EPUBs, comics, and other document formats—covering everything from lightweight PDF viewers to full-featured e-book library managers with sync and text-to-speech.

**Examples** include Adobe Acrobat Reader, Foxit PDF Reader, Apple Books, Kindle Cloud Reader, Kobo, Calibre, Thorium Reader, Okular, and SumatraPDF (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted reading apps, open-source PDF viewers, and community-driven library managers—ideal for users seeking privacy, no subscriptions, and full control over their reading data. The open-source landscape is exceptionally strong: **Calibre** is the standard e-book manager , **Thorium Reader** is the EPUB 3 reference implementation from EDRLab , and **Okular** provides universal document viewing with privacy-first annotation .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global digital document and e-book reader ecosystem encompasses dedicated e-reader hardware (valued at approximately $8.5B–$9.5B growing at ~6% CAGR) and the digital publishing/document software market valued at over $50B. The industry exhibits a bifurcated market structure: consumer hardware and commercial app distribution are highly concentrated around tech giants (Amazon Kindle, Apple, Rakuten Kobo, Adobe) with winner-take-most platform lock-in, while specialized productivity, local-first annotation, and open-source PDF/EPUB tooling remain moderately to highly fragmented across independent developers and privacy-focused open ecosystems.

## SaaS/Hosted Platforms

| Product | Description | Company Valuation / Revenue | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|----------------------------|-------------------|--------------------------|
| **[Apple Books](https://www.apple.com/apple-books/)** | Apple's built-in e-book reader across macOS, iOS, and iPadOS. Syncs reading position via iCloud and supports EPUB/PDF reading. | ~$3.5T Market Cap / ~$391B Annual Revenue (Apple Inc.) | $0.00 (included with macOS/iOS devices; paid books individually priced) | **Free Forever**: Full reader features with unlimited personal EPUB/PDF imports; cloud sync limited by standard free 5GB iCloud storage tier |
| **[Kindle Cloud Reader](https://read.amazon.com/)** | Web browser & cloud-based Kindle reading interface enabling instant library access without app installation. | ~$2.2T Market Cap / ~$575B Annual Revenue (Amazon.com, Inc.) | $11.99/month (Kindle Unlimited starting subscription; or a-la-carte book purchases) | **Free Forever**: Web reader is free to read purchased or free catalog books; 30-day free trial for Kindle Unlimited (up to 20 titles borrowed concurrently) |
| **[Adobe Acrobat](https://www.adobe.com/acrobat/pdf-reader.html)** | Standard PDF viewer and cloud document platform with annotation, form-filling, OCR, and cloud storage. | ~$215B Market Cap / ~$19.4B Annual Revenue (Adobe Inc.) | $12.99/month (Acrobat Standard, billed annually) or $19.99/month (Acrobat Pro) | **Free Forever**: Acrobat Reader desktop/mobile enables viewing, basic annotation, commenting, and form filling; web tools include 7-day free trial for Pro features |
| **[Kobo](https://www.kobo.com/)** | Global digital reading platform with cross-platform e-reader apps, cloud sync, and integrated digital bookstore. | ~$12B Market Cap / ~$14B Annual Revenue (Parent: Rakuten Group, Inc.) | $7.99/month (Kobo Plus Read eBook subscription; or per-title purchases) | **Free Forever**: Unlimited reading of sideloaded personal EPUB/PDF documents and public domain titles on free apps; 14-day free trial for Kobo Plus catalog |
| **[Foxit PDF Reader](https://www.foxit.com/pdf-reader/)** | High-performance PDF viewing, commenting, and form-processing ecosystem built as a modular alternative to Adobe. | ~$900M Market Cap / ~$150M Annual Revenue (Foxit Software Inc., STAR: 688095) | $129.99/year (Foxit PDF Editor annual license) or $10.83/month billed annually | **Free Forever**: Foxit Reader allows viewing, basic note-taking, printing, and form-filling; full editor features available via a 14-day free trial |
| **[Kami](https://www.kamiapp.com/)** | Cloud-based collaborative PDF annotation and interactive learning workspace designed for schools and teams. | ~$180M Valuation (NZD $300M+) / ~$22M Annual Revenue (Kami / Authentic Minds) | $149.00/year (Teacher Plan, single license) or $12.42/month | **Free Forever**: Basic Plan includes essential annotation tools (markup, highlights, text insertion) with Google Drive/OneDrive sync; premium LMS sync and audio comments locked behind 60-day teacher trial |
| **[PocketBook Cloud](https://pocketbook.ch/)** | Digital reading and cross-device sync platform connecting mobile apps, web readers, and E Ink hardware. | ~$40M Estimated Annual Revenue (PocketBook International S.A., private) | $0.00 (free reading apps and cloud sync; books purchased individually from PocketBook shop) | **Free Forever**: Free account includes cloud sync of reading progress, notes, and up to 2GB free cloud storage for personal e-books (PDF, EPUB, MOBI) across 5 devices |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Calibre](https://github.com/kovidgoyal/calibre)** | [![Stars](https://img.shields.io/github/stars/kovidgoyal/calibre?style=social&color=white)](https://github.com/kovidgoyal/calibre/stargazers) | **The standard open-source e-book manager and the most complete library solution.** View, convert, edit, and catalog e-books in all major formats. Talks to e-book reader devices (Kindle, Kobo, Nook), fetches metadata from the internet, downloads news/RSS and converts to e-books, and includes a built-in viewer for all major formats . Cross-platform: Linux, Windows, macOS . **The default choice for anyone managing a large e-book library.** |
| **[Thorium Reader](https://github.com/edrlab/thorium-reader)** | [![Stars](https://img.shields.io/github/stars/edrlab/thorium-reader?style=social&color=white)](https://github.com/edrlab/thorium-reader/stargazers) | **The EPUB 3 reference implementation from EDRLab.** Over **1.5 million downloads** for the desktop variant. Supports EPUB 2/3, PDF, DAISY 2.02/3, audiobooks, and Divina. **LCP DRM support** for library lending. **Accessibility-first design** for visually impaired and dyslexic readers. OPDS catalog navigation, bookmarks, full-text search, and Read Aloud. Available for Windows, macOS, Linux; mobile in development . **Best for library patrons and accessibility needs.** |
| **[Okular](https://github.com/KDE/okular)** | [![Stars](https://img.shields.io/github/stars/KDE/okular?style=social&color=white)](https://github.com/KDE/okular/stargazers) | **Universal document viewer from KDE with privacy-first annotation.** Supports PDF, EPUB, DjVu, PostScript, XPS, ComicBook (CBZ/CBR), FictionBook, Markdown, and images . **Annotations stored separately from source files by default** (can be embedded on save). Fast, lightweight (<300 MB installed), no telemetry, no account required. Available for Linux, Windows, macOS . **Best for users who want a fast, privacy-respecting universal viewer with powerful annotation.** |
| **[SumatraPDF](https://github.com/sumatrapdfreader/sumatrapdf)** | [![Stars](https://img.shields.io/github/stars/sumatrapdfreader/sumatrapdf?style=social&color=white)](https://github.com/sumatrapdfreader/sumatrapdf/stargazers) | **The fastest, lightest PDF and e-book reader for Windows.** Supports PDF, EPUB, MOBI, CBZ/CBR, DjVu, XPS, CHM, and images. **Opens documents instantly with minimal memory use**; portable option runs from USB drive. No ads, no bundled software, no subscription. **Windows-only.** Widely praised as faster and lighter than Adobe Reader, Foxit, and most alternatives . |
| **[Koodo Reader](https://github.com/koodo-reader/koodo-reader)** | [![Stars](https://img.shields.io/github/stars/koodo-reader/koodo-reader?style=social&color=white)](https://github.com/koodo-reader/koodo-reader/stargazers) | **All-in-one e-book reader with sync and backup across platforms.** ~29k stars on GitHub. Supports Windows, macOS, Linux, Android, iOS, and Web. Features sync across devices, backup, annotation, and multiple view modes. AGPL-3.0 licensed . **Best for users who want cross-platform sync without a paid service.** |
| **[Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF)** | [![Stars](https://img.shields.io/github/stars/Stirling-Tools/Stirling-PDF?style=social&color=white)](https://github.com/Stirling-Tools/Stirling-PDF/stargazers) | **The open-source alternative to Adobe Acrobat for PDF manipulation.** Merge, split, compress, convert, OCR, sign, redact, compare, and watermark PDFs. **Version 2.0** adds native desktop apps (Windows/macOS/Linux) and alpha text editing (paid early access). **Free for individuals and groups up to 5 users**; organizations >5 users require commercial license. 18M downloads; used by 72% of Fortune 500 per developers . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Zathura](https://github.com/pwmt/zathura)** | [![Stars](https://img.shields.io/github/stars/pwmt/zathura?style=social&color=white)](https://github.com/pwmt/zathura/stargazers) | **Minimalist, keyboard-driven document viewer with vim-like bindings.** PDF support via plugin; optional CB, DjVu, and PS plugins. Bookmarking, link following, full-text search, SyncTeX forward/backward sync. **Linux/Unix focus.** Best for users who live in the terminal and want keyboard-only navigation . |
| **[Theorem](https://github.com/fundaments-work/theorem)** | [![Stars](https://img.shields.io/github/stars/fundaments-work/theorem?style=social&color=white)](https://github.com/fundaments-work/theorem/stargazers) | **Local-first reading app with LAN device sync.** EPUB, PDF, MOBI, CBZ, CBR, and RSS. Highlighting, annotations, TTS, vocabulary builder, reading statistics with streaks and heatmaps, RSVP speed reader, and encrypted peer-to-peer sync between devices (no account, no server). Built with Tauri/Rust/React. Cross-platform desktop + Android . |
| **[Episteme](https://github.com/topics/ebook-reader)** | — | Free open-source e-book reader supporting PDF, EPUB, MOBI, AZW3, FB2, DOCX, ODT, Markdown, HTML, CBZ, CBR, and CB7. Android, Windows, Linux (no macOS). **OSS Offline edition strips all network permissions**—cannot phone home. AI features optional via BYOK. On F-Droid and GitHub . |

**Frameworks for building custom systems**: Choose **Calibre** for library management and format conversion, **Thorium Reader** for EPUB 3 compliance and accessibility, **Okular** for universal document viewing with privacy-first annotation, and **SumatraPDF** for the fastest Windows reading experience—all free and open-source without subscriptions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document readers may handle sensitive personal or business documents; verify that any cloud sync or telemetry features are disabled if privacy is required. **Okular explicitly collects no user data and requires no registration** .
- **Licensing changes matter.** Stirling PDF 2.0 introduced **commercial licensing for organizations >5 users**—existing users are grandfathered, but new enterprise deployments require a $99/month or $1,000/year license . **Platform limitations**: SumatraPDF is **Windows-only** ; Zathura is Linux/Unix-focused . **Calibre** is primarily an e-book manager with a built-in viewer—not a lightweight PDF reader. **Thorium Reader** is the best choice for library lending (LCP DRM) and accessibility, but less suited for casual PDF viewing. Always validate current licensing and platform support against your needs before committing.

---

**Made for readers, students, researchers, and organizations managing digital documents.**  
Let's make digital document and e-book reading more open, private, and accessible.
