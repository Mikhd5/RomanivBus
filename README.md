# RomanivBus — website concept v2

Responsive static website concept for RomanivBus, built as a mobile-friendly single-page site.

## Included
- `index.html` — complete responsive site, navigation, route cards, benefits, parcel-delivery section, booking form, and contacts.
- `assets/` — locally stored WebP visuals. Hero, booking background, interior, parcel image, and four destination visuals are exported on 3840 × 2160 canvases (4K UHD dimensions) and optimized for web delivery.

## Features
- Responsive navigation with mobile menu.
- Route cards for Poland, Germany, Netherlands, and Belgium; tapping a card preselects the destination in the booking form.
- Booking form with required-field validation and a minimum date of today.
- Form creates a prefilled WhatsApp message to the Ukraine contact number (+380673363931). The visitor must review and send the message; the site does not store bookings or confirm seat availability.
- Smooth section navigation, reveal-on-scroll effects, reduced-motion support, and a back-to-top control.
- All visual assets are local; no external stock-photo links are required.

## Run locally
Open `index.html` in a browser, or serve this folder with any static web server.

## Deploy to Vercel
Import the folder/repository as a static project. No build command is required; the project root is the folder containing `index.html`.

## Important before production
- Generated images are illustrative design visuals, not verified photographs of RomanivBus vehicles or staff. Replace them with the carrier's real fleet/interior photos when supplied.
- Confirm the schedule (the supplied materials mention Monday departures from Ukraine and Wednesday from Germany, while another description says daily departures).
- Confirm exact city stops, route coverage, pricing, and current service conditions before publishing.
- Add a backend/CRM or booking provider if the business needs stored bookings, admin management, automated confirmations, or live seat availability.
- Connect the official domain only after the domain owner confirms the domain and DNS access.
