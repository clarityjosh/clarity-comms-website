# Clarity Comms Website

Static business website ready for GitHub + Netlify.

## Files
- `index.html` — homepage
- `services.html` — service details
- `about.html` — company overview
- `contact.html` — Netlify contact form
- `privacy.html` — starter privacy notice (must be completed/reviewed)
- `thanks.html` — successful form submission page
- `assets/style.css` — all styling
- `assets/main.js` — mobile menu + footer year

## IMPORTANT: Add the real logo
Copy the original Clarity Comms logo into:
`assets/clarity-comms-logo.png`

Do not substitute or redraw the logo if exact branding is required.

## Before launch
Search the site for `INSERT` and update:
- business email
- phone number
- company / registered details
- service area
- any required privacy information

## Netlify
This is a static site. No build command is required.

If Netlify asks:
- Branch: `main`
- Build command: leave blank
- Publish directory: `.`

The contact form uses Netlify Forms:
`<form name="contact" method="POST" data-netlify="true">`

After the first production deploy, check Netlify > Forms and submit a test enquiry.
