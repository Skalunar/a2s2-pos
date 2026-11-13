A2S2 POS — GitHub Pages PWA

CONTENTS
index.html — billing app (categories, prices, cart, Cash/UPI, receipt, sales summary, CSV export)
manifest.webmanifest — install metadata
service-worker.js — app shell offline cache
icons/ — SVG source and PNG app icons

UPLOAD TO GITHUB
1. On GitHub, create a new repository named a2s2-pos. A public repository is the simplest setup for GitHub Pages.
2. Download and unzip this package on your computer. Open the extracted a2s2-pos-pwa folder.
3. In the empty GitHub repository, choose Add file → Upload files. Drag the CONTENTS of a2s2-pos-pwa (index.html, manifest.webmanifest, service-worker.js, icons folder, README.txt) into the upload area. Do not upload only the ZIP.
4. Enter a commit message such as “Add A2S2 POS app” and click Commit changes.
5. Open repository Settings → Pages. Under Build and deployment, choose Deploy from a branch; select branch main and folder /(root); click Save.
6. Wait for the Pages deployment to finish. Its address is https://YOUR-GITHUB-USERNAME.github.io/a2s2-pos/ . Replace YOUR-GITHUB-USERNAME with your GitHub username.
7. On Android, open that HTTPS address in Chrome, wait until it loads once, then use Chrome menu → Install app (or Add to Home screen). Open the installed A2S2 POS once online before relying on offline use.

OFFLINE AND DATA
The app shell is cached after the first successful online visit. Bills are saved in this browser's local storage on this device; they do not sync to GitHub or other phones. Keep browser/site storage enabled. Export sales CSV regularly using Export sales and keep copies somewhere safe. Clearing Chrome site data, uninstalling/resetting the browser, or losing the phone can erase saved bills. CSV is a readable sales report, not an automatic restore file.

PRINTING
Receipts use the browser's print dialog. This project does not implement Bluetooth printing. On Android, printer choices depend on the printer manufacturer's app or an installed Android print service (for example, RawBT where compatible), device permissions, and printer model. Pair/configure the printer in its supported app/service first; choose it in the print dialog if it is offered. If no printer destination appears, use the printer vendor's supported workflow.

TROUBLESHOOTING
If installation is unavailable, verify Pages finished publishing and that you opened the HTTPS Pages URL (not a local HTML file). Offline mode is available only after the app has loaded successfully online. If sales data cannot be saved, the app keeps the current cart and displays an error; free device storage and retry.
