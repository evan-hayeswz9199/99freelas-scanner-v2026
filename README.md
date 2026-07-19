# 99Freelas Scanner v2026 - browser scraper 2026

> **A browser-only 99Freelas project scanner for portfolio matching, dashboard filtering, and local persistence, built around a 100% client-side workflow.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evan-hayeswz9199/99freelas-scanner-v2026?style=flat-square)](https://github.com/evan-hayeswz9199/99freelas-scanner-v2026)

---

<p align="center">
  <a href="https://evan-hayeswz9199.github.io/99freelas-scanner-v2026/">
    <img src="https://img.shields.io/badge/Download-99Freelas%20Scanner%20Latest-brightgreen?style=for-the-badge" alt="Download 99Freelas Scanner">
  </a>
</p>

> **[Download Latest Build - 99Freelas Scanner v2026](https://evan-hayeswz9199.github.io/99freelas-scanner-v2026/)**

---

[Download Latest Build](https://evan-hayeswz9199.github.io/99freelas-scanner-v2026/)

---

## Overview

99Freelas Scanner is a web-based scraper designed for finding 99Freelas projects and comparing them with portfolio text. Everything happens in the browser, with DOMParser-driven parsing and a CORS proxy used to gather project data and evaluate how well it aligns with the provided profile content.

It fits workflows that call for fast review, visible match results, and lightweight state retention without needing a backend. The dashboard is used to sort matches, track scanning activity as it happens, and refine the output through status and refresh controls.

---

## Capabilities

- Operates entirely in the browser, with no backend service needed
- Pulls 99Freelas project data through a CORS proxy
- Uses DOMParser to extract content on the client side
- Automatically identifies skills from portfolio text
- Dynamically compares profile data against project listings
- Displays matches in a dashboard with filtering controls
- Persists data in localStorage between sessions
- Provides live progress logs along with refresh and status filters

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/evan-hayeswz9199/99freelas-scanner-v2026.git
2. Open the project folder in a browser-friendly local server or through the hosted build.
3. Launch the main HTML entry point and let the scanner initialize in the dashboard.

If you are using the published build, open the latest download link and start from the browser interface.

---

## How to Use

1. Open or connect the source page you want to scan.
2. Let the scanner gather project listings through the browser workflow.
3. Inspect detected skills and match scores in the dashboard.
4. Apply filters to reduce results by status or other visible criteria.
5. Refresh the scan whenever you want the current matches updated.
6. Review the progress log if you need to follow the parsing or matching stage.

Typical workflow:
- Add your portfolio text
- Start the scan
- Review the matched projects
- Filter the results
- Save and revisit the session later

---

## Configuration

Most options are managed in the browser and saved locally. The main persistence layer is `localStorage`, which lets session data stay available between visits.

Example settings area:

    {
      "storage": "localStorage",
      "matching": "portfolio + project comparison",
      "filters": "status-based dashboard filters",
      "proxy": "CORS proxy endpoint"
    }

If the proxy or scan source needs adjustment, update the relevant values in the app's browser-side configuration or script entry point.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Access to a working CORS proxy for project scraping
- Enough local storage space for saved scan data and dashboard state
- A local or hosted HTML entry point for loading the interface

---

## FAQ

**How do I update the scanner?**  
Replace the current build with the newest release, then reload the page so the browser loads the updated files.

**Where is my data stored?**  
The app saves state in `localStorage`, so your data stays in the browser until you clear it manually.

**Why are some results not loading?**  
Verify the CORS proxy setup, refresh the scan, and make sure the source page can be reached from the browser environment.

**Can I change the matching behavior?**  
Yes. Matching depends on portfolio text and project content, so changing the input text or scan source can change the results.

**What should I do if the dashboard looks stale?**  
Use the refresh control, clear browser storage if needed, and run a new scan.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
