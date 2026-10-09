# Diêu Atelier — GitHub Pages
Visit https://levinhieyagi.github.io/dieuatelier/ after deployment finishes.

## Edit
- Open index.html in VS Code to change the workshop text and destination links.
- Replace assets/profile_dieuatelier.png to change the portrait/background image.
- The original CSS is kept in assets/.

## Behavior and checks
- Three workshop links and the Instagram link retain their original destinations.
- The email link opens a mail client for the address in the supplied page data.
- Platform scripts, embedded runtime data, and challenge iframes were removed. This is a static snapshot; it does not sync with Beacons or include its analytics/editor.
- Original Beacons footer links are retained.
- All referenced local HTML assets were checked to exist. Fonts still load from Google Fonts, with browser fallbacks when unavailable.
- Desktop/mobile visual verification could not run because the available environment has no installed browser. Preview index.html locally before publishing.
