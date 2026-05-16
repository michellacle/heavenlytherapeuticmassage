# Heavenly Therapeutic Massage Website

This repository contains the rebuilt marketing website for **Heavenly Therapeutic Massage**, a massage and wellness business in Homestead, Florida.

## Client Context

- **Business:** Heavenly Therapeutic Massage  
- **Website:** https://www.heavenlytherapeuticmassage.com/  
- **Location:** 42 W Mowry Drive #216, Homestead, FL 33030  
- **Primary phone:** 786-873-1191  
- **Core differentiator:** Post-op lymphatic drainage and therapeutic massage care

This rebuild replaces a legacy Vagaro/Salon Builder template site with a cleaner custom frontend focused on trust, clarity, and conversion.

## Current Project Stage

This is **Stage 1** of the redesign:

- New homepage structure and visual system
- Refined service positioning and clearer pricing cues
- Preserved core brand themes and selected real imagery
- Transitional booking section while platform migration is planned

## Booking and Payments Direction

Current live flow still references Vagaro during transition.

Recommended migration path:

1. **Payments:** Stripe Payment Links + Stripe Invoicing for deposits and package balances  
2. **Scheduling:** Acuity Scheduling (Squarespace Scheduling) for calendar management, intake forms, and appointment confirmations

## Tech Stack

Static site (no build step):

- `index.html`
- `css/rebuild.css`
- `js/main.js`

## Local Development

Open `index.html` directly in a browser for basic review.

If you want a local server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Repository Notes

- This repo is currently intentionally simple and frontend-only.
- Future stages are expected to add booking/payment integration details, expanded SEO pages, and structured content for service-area growth.
