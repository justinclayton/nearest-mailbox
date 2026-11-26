# Nearest Mailbox

A single-page web app that lists the USPS collection boxes closest to a location.

- Box locations and pickup schedules come from OpenStreetMap through the Overpass API.
- Address search uses Nominatim.
- The page is not affiliated with USPS. The official locator is at https://tools.usps.com/find-location.htm.

The app is one file, `index.html`. GitHub Pages serves the file over HTTPS, which the browser requires before the browser shares a device location.
