# Crave Kitchen — Cloud Kitchen Website

## Files
- index.html — homepage
- menu.html — searchable and filterable menu
- offers.html — coupon/offer page
- about.html — story page
- contact.html — contact form demo
- cart.html — shopping bag and checkout
- admin.html — local demo admin dashboard
- style.css — shared responsive styling
- app.js — shared functionality

## Run
Open this folder in VS Code, install the Live Server extension, right-click index.html and choose "Open with Live Server".

## Important customisation
1. In app.js, change `const kitchen="919876543210"` to your WhatsApp number in international format without +.
2. In contact.html, change the displayed phone number and WhatsApp link.
3. Replace sample menu, prices, photos, delivery charge and kitchen details with your real information.
4. The admin dashboard and orders use browser localStorage. They are only a frontend demo, not a secure multi-user admin system.
5. Checkout opens WhatsApp. It does not process online payments or store orders on a server. Connect a backend/database and a payment provider before taking real orders.
6. Contact and newsletter forms are demo interactions; connect an email service/backend to receive submissions.
