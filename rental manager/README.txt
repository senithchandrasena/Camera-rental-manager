# Camera Rental Manager

A mobile-friendly 3-camera rental calendar.

## Included
- 3 independent cameras
- Monthly calendar
- Daily availability
- Double-booking prevention
- Customer name and phone
- Pickup and return dates
- Rental amount and deposit
- Booking status and notes
- Rental history
- Customer summary
- Camera inventory/status
- Persistent browser storage (localStorage)
- Installable PWA manifest

## Important
This version stores data in the browser on the device. It does NOT yet synchronize bookings between devices.

## Use on a computer
Open `index.html` in a modern browser.

## Put it online for phone access
Upload `index.html` and `manifest.json` to a static web host such as GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Then open the resulting HTTPS address on your phone and use "Add to Home Screen".

## Recommended next production upgrade
For true PC + phone synchronization, replace localStorage with a cloud database/authentication layer. The UI is intentionally separated so this can be added without redesigning the calendar.
