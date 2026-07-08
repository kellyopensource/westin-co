# Westin & Co — Database and API Architecture

Westin & Co is a custom embroidery e-commerce business; this repository documents the
database schema, API contract, and system architecture that power the order intake and
fulfillment workflow behind the storefront at [westinandco.net](https://westinandco.net).

Westinandco.net is where I'm building. Westinandco.com is the Shopify handoff. The two are separate due to third-party app costs for features the owner would like to add.

---

## What This Repo Contains

This is not the full application codebase — the customer-facing storefront runs on Shopify.
This repository contains the backend architecture layer:

- **Database schema** — designed in DbSchema, with exports for both SQLite (development)
  and Postgres (production). Covers customers, orders, custom request intake, product
  variants, and order status tracking.

- **API contract documentation** — full documentation of the internal API endpoints,
  including the `POST /customer-requests` intake endpoint. Each endpoint document covers
  request shape, response shape, validation rules, and status codes.

- **State machine documentation** — the intake-to-review-to-checkout workflow that governs
  how a custom embroidery request moves from customer submission through internal review
  to a completed Shopify checkout.

- **Shopify Storefront API integration notes** — how the internal API connects to Shopify
  for checkout creation and order retrieval. No Shopify credentials or proprietary data
  are stored here.

- **FastAPI route stubs** — scaffolding for the API routes, structured to match the
  contract documentation. These are stubs, not production code.

- **Environment variable template** — `.env.example` lists all required environment
  variables with placeholder values.

---

## Tech Stack

| Layer | Tool |
|---|---|
| Database design | [DbSchema](https://dbschema.com) |
| Development database | SQLite |
| Production database | PostgreSQL |
| API framework | [FastAPI](https://fastapi.tiangolo.com) |
| Storefront | Shopify (external) |
| Storefront API | [Shopify Storefront API](https://shopify.dev/docs/api/storefront) |

---

## About This Project

Westin & Co is a working business, not a demo or portfolio project. The schema and API
contract documented here are the actual system used to process real custom embroidery
orders. This repository exists to maintain a clear record of the data architecture and
integration design as the system evolves.

**Live site:** [westinandco.net](https://westinandco.net)
<img width="468" height="648" alt="image" src="https://github.com/user-attachments/assets/da2d1829-1f6c-4555-a8bc-c5e2ad8abf39" />

