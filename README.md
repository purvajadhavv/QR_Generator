# Creative QR

A static, client-side branded QR designer. Users can enter text/URLs, optionally add a logo, customize module and finder-eye styles, colors, gradients and transparent backgrounds, then export a real SVG or high-resolution PNG.

## Privacy
Everything runs in the browser. User-entered content and logos are kept in runtime memory only. There is no backend, database, authentication, analytics, QR API, localStorage, sessionStorage, or upload service.

## Run
Open `index.html` directly or serve the folder with any static web server. No build step is required.

## Logo behavior
The uploaded logo is rasterized locally to a PNG data URL in memory. A clean background knockout is placed behind it, and the QR encoder uses high error correction. Keep the logo moderate in size for best scanning.
