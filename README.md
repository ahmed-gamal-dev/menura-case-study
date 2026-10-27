# Menura

> Restaurant SaaS: digital menu, online ordering, POS, inventory and accounting.

**Live:** [menura.virvib.com](https://menura.virvib.com/) · **Role:** Architect & developer · **Period:** 2026 · **For:** Own product

![Laravel 13](https://img.shields.io/badge/Laravel_13-2E2A8C?style=flat-square) ![PHP 8.3](https://img.shields.io/badge/PHP_8.3-2E2A8C?style=flat-square) ![React 19](https://img.shields.io/badge/React_19-2E2A8C?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-2E2A8C?style=flat-square) ![Tailwind 4](https://img.shields.io/badge/Tailwind_4-2E2A8C?style=flat-square) ![MySQL](https://img.shields.io/badge/MySQL-2E2A8C?style=flat-square) ![Redis](https://img.shields.io/badge/Redis-2E2A8C?style=flat-square) ![Laravel Reverb](https://img.shields.io/badge/Laravel_Reverb-2E2A8C?style=flat-square) ![Caddy](https://img.shields.io/badge/Caddy-2E2A8C?style=flat-square)

![Menura — home page](screenshots/desktop.png)

## Overview

Every restaurant gets a free subdomain (for example kababgy.menura…) or connects its own domain, then runs its storefront, online orders, POS, inventory and books from one platform.

## What it does

- Branded storefront and digital menu per restaurant
- Online ordering with coupons, loyalty and delivery zones
- POS with shifts and tenders, live orders over websockets
- Inventory, recipes, suppliers and purchase orders
- Double-entry accounting and reports
- Reservations, reviews, multi-branch and multi-language

## Engineering highlights

- Hybrid multi-database: central DB + one database per restaurant
- Custom domains with DNS verification and on-demand TLS certificates
- All prices recalculated on the server in minor units (no client-side money)
- Idempotent ledger postings; corrections are reversals, never edits
- Feature tests for tenant isolation, ordering, POS and payments

## Screenshots (live site)

<p>
  <img src="screenshots/mobile.png" width="260" alt="Mobile">
  <img src="screenshots/page1.png" width="520" alt="Page">
</p>

<details>
<summary>Full home page</summary>

![Full page](screenshots/long.png)

</details>

---

Source code is private (client / commercial project). This repository documents the work only.

Built by **Ahmed Gamal** — Senior Laravel Developer · [LinkedIn](https://www.linkedin.com/in/wzcoder/) · [GitHub](https://github.com/ahmed-gamal-dev)
