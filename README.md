# Shawarma TOGO – Demo-Website

A responsive one-page demo website for **Shawarma TOGO**, a snack bar in Dortmund. I built it as a sales demo to show the owner.

## Features

- **Mobile-first, responsive layout.** On phones, Call, Order and Directions buttons stay fixed at the bottom of the screen.
- **German / Arabic switch.** In Arabic the layout flips right-to-left.
- **Pre-ordering by WhatsApp.** Customers add items to a small cart, and the order is sent to the shop as a ready-written WhatsApp message.
- **Live "open now" indicator** and an opening-hours table that highlights today.
- **Tap-to-call** (`tel:`) and a link to Google Maps.
- **A single self-contained `index.html`**: no build step and no dependencies apart from Google Fonts.

## Hosting on GitHub Pages

1. Go to **Settings → Pages**.
2. Under **Source**, choose *Deploy from a branch*, then **Branch:** `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/shawarma-togo-demo/`.

## Still to replace before going live

- [ ] Real menu items and prices. They're in the `M` array in the `<script>` block.
- [ ] Street address. Search for `Musterstraße` to find it.
- [ ] Opening hours, if they aren't 11:00–23:00 every day.
- [ ] Dish photos from the on-site shoot. The striped "Foto beim Shooting" boxes are placeholders.
- [ ] Impressum and Datenschutz pages, which German law requires.
- [ ] Remove the yellow "Demo-Entwurf" banner.
