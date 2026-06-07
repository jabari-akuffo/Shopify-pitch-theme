# Baka Beauty — Pitch Theme Localization (Variation)

> **Note:** This is a theme variation only. The primary storefront uses the Sense theme. This Pitch theme build is an alternate variation and is not the production theme.

## Overview

This project modifies Shopify's **Pitch** theme for [Baka Beauty](https://bakabeauty.com) and localizes the storefront into three additional languages: **French**, **Spanish**, and **Portuguese**.

**Development store:** [baka-beauty.myshopify.com](https://baka-beauty.myshopify.com)  
**Consultant:** Jabari Akuffo / Jabari L10n

---

## Scope

### Theme Customization
- Base theme: Shopify Pitch
- Custom modifications to layout, sections, and/or styles to align with Baka Beauty's brand
- Variation of the primary Sense theme build — structural differences may apply

### Localization
| Locale | Language   | Market |
|--------|------------|--------|
| `fr`   | French     | FR / CA / Other Francophone |
| `es`   | Spanish    | ES / LATAM |
| `pt`   | Portuguese | PT / BR |

---

## File Structure

```
locales/
  en.default.json       # Source strings (English)
  fr.json               # French translations
  es.json               # Spanish translations
  pt.json               # Portuguese translations
```

---

## Notes

- This theme is a **variation** — refer to the Sense theme README as the primary reference
- All locale files follow Shopify's standard `t` filter pattern
- Dynamic merchant content (product titles, descriptions, metafields) is managed separately via Shopify Markets / Translate & Adapt
- Theme edits are scoped to the Pitch theme source — no third-party apps introduced
