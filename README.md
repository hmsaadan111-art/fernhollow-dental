# Fernhollow Dental

Website for a private dental practice in Clifton, Bristol (UK). Fernhollow is a concept brand, designed and built by [SFF Digital Limited](https://hmsaadan111-art.github.io).

**Live site:** https://hmsaadan111-art.github.io/fernhollow-dental/

## Features

- **Online booking** in 5 steps: appointment type, clinician, date and time (UK time), patient details, then confirmation with a booking reference.
- **Manage a booking:** find it with the reference and email, then move or cancel it. A late-cancellation notice shows inside 24 hours.
- **Add to calendar:** downloads an .ics file with the Europe/London timezone and a 2-hour reminder.
- **Treatment price calculator** in GBP, with quantities and options (filling size, root canal tooth type and others). It shows Care Plan savings and an interest-free monthly split for treatment over £500, and the estimate can be downloaded.
- **Live opening status** that works out "Open now" or "Opens tomorrow" from UK time.
- Same-day emergency slots, clinician working days and lunch breaks are all reflected in availability.
- Privacy policy written for UK GDPR. It also lets visitors delete booking data saved in their browser.
- Responsive from 360px up, keyboard accessible, and respects reduced-motion settings. Includes schema.org `Dentist` structured data.

## Tech

Plain HTML, CSS and JavaScript in a single page, with no framework and no build step. Bookings are stored in the browser's localStorage, so the site is fully static and hosted on GitHub Pages.

Phone numbers on the site come from Ofcom's range reserved for fictional use.
