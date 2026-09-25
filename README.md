# Gym booking prototype

A mobile sized browser prototype for exploring a BFT class booking interface. The complete app is `dist/index.html`; its only asset is `dist/bean-curd-unicorn.png`. There is no build step or external package dependency.

## Run locally

Open `dist/index.html` in a browser, or serve `dist/` with any static web server. All times and dates use Singapore time.

## What is included

- The class programme in the JavaScript `programmeRows` table covers 21 September–14 November 2026. Weekdays have classes at 06:10, 07:15, 08:20, 12:00, 17:10, 18:15 and 19:20; Saturdays at 07:30, 08:45, 10:00 and 11:15.
- Searchable studio picker, date navigation, profile for Bean Curd and trainer names.
- Demo booking and waitlist controls, cancellation, share text and calendar file export. Availability and user actions are held in browser memory and reset on refresh. There are no real member accounts, payments, notifications or live studio records.
- Classes can be booked within a rolling 14-day period. Completed classes are disabled. Waitlist capacity is 20; class capacity is 24.

## GitHub

To copy this exact prototype into your own repository, put `dist/index.html` and `dist/bean-curd-unicorn.png` together at the repository root as `index.html` and `bean-curd-unicorn.png`. You may also upload this README. GitHub stores and tracks the files. To view the browser prototype through a GitHub URL, enable GitHub Pages for the repository root. GitHub Pages publishes a public website, even if the repository is private.

For changes in an AI coding tool, give it access to this repository and ask it to edit `index.html` while preserving the schedule, studio picker, booking states and mobile layout. Check the result in a browser and commit the working change.
