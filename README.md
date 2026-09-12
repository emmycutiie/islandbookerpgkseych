# IslandBooker

**Stay • Explore • Experience**

Commercial tropical booking marketplace for hotels, guesthouses, tours, boat trips and activities.

## Included
- Customer marketplace with live approved listings
- Business owner sign-up/sign-in
- Business profile management
- Business listings with prices, currencies, units and guest limits
- Listings appear publicly after admin approval
- Booking request flow
- Booking/customer details stored in Supabase
- Business payment-account instructions (customers pay businesses directly)
- Owner dashboard
- Admin access and business approval/suspension
- Tropical/beach-focused responsive UI
- Netlify-ready static deployment

## Deployment
This is a plain static HTML application. Netlify should use:

- Build command: leave blank
- Publish directory: `.`
- Production branch: `main`

The project is designed for the Netlify site `islandbooker`.

## Supabase
The frontend is already configured for the IslandBooker Supabase project and uses the public publishable client key in the browser. Do not put a Supabase service-role key or OpenAI secret key in this repository.

## Important listing behavior
Business owners can create listings and set:
- title
- listing type
- price
- currency (USD, PGK or SCR)
- pricing unit
- maximum guests
- description

Public listings are filtered to active listings belonging to businesses whose status is `approved`.

## GitHub
Recommended repository:

`Emmycutiie/islandbooker`

After the repository is connected to Netlify, pushes to the production branch can trigger automatic deployments.
