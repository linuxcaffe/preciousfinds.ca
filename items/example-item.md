---
title: Example Item
category: example
status: available
price: $0.00
image: images/example.jpg
description: A short description shown in the shop and on the item page.
condition: Excellent
size: 10 × 5 × 3 cm
shipping: Canada Post, ~$8
platform: Etsy
listing: https://etsy.com/listing/example
tags: [new]
---

The body of the note is the item's full description page.

Each item lives in the `items/` folder with this frontmatter:

| Field | Purpose |
|-------|---------|
| category | Groups items in the nav and generates /category/\<name\> pages |
| status | `available` shows the item; `sold` shows it as sold; anything else hides it |
| price | Displayed as-is — e.g. $24.00 |
| image | Filename from the notebook's `images/` folder (comma-separate for a gallery) |
| description | Short text for cards and the item header |
| condition | Free text — Excellent, Good, As-is, etc. |
| size | Free text |
| shipping | Free text |
| platform | External marketplace name (Etsy, eBay, etc.) |
| listing | URL to external listing |

Tag an item `featured` to include it in the featured section on the home page.

*Delete this note when you have real items to list.*
