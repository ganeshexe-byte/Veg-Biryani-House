# Veg Biryani House

A cinematic, scroll-driven showcase for a pure-vegetarian biryani house. Plain HTML, CSS and JavaScript, with no build step.

## Run it
Keep `index.html` and `style.css` in the same folder and open `index.html` in a browser (needs internet for Google Fonts).

## What's inside
- "Lifting the lid" loader (0 to 100%)
- Full-screen scroll showcase of 10 vegetarian biryanis. Between dishes the dough-sealed pot closes, then the lid lifts with a steam bloom and the photo rises in
- Giant gradient word, mouse parallax, "The Table" index
- Photo mode: real dish photos in `images/` (see `images/README.md`); falls back to a drawn pot when photos are missing
- Order panel that sends the order to WhatsApp

## Customise
- Dishes, prices, colours and ingredients: the `DISHES` array in the `<script>` of `index.html`
- WhatsApp number: `WHATSAPP` constant in the same script (country code, no `+`)
