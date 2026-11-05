# Kgwebo Business Manager — first Android-friendly prototype

## What is included
- Dashboard with sales, expenses, net result and product count
- Sales recording, optionally deducting product stock
- Product inventory with low-stock indicators and stock adjustment
- Expense tracking with categories
- Customer list and customer payment/balance tracking
- Basic reports, CSV export and JSON backup
- English interface and Botswana pula default
- Local-device storage; no account or internet required for day-to-day records

## Important limitations
This is a functional prototype, not a signed Android APK and not yet a production accounting system. Data is stored in the browser on the device. Clearing browser data or uninstalling/clearing the app can remove records, so export backups regularly. There is no cloud sync, user login, payment processing, tax compliance, multi-user access or live Premium billing. Premium features are marked as planned only.

## Try it on Android
1. Extract this ZIP using your phone's Files app.
2. Open `index.html` in Chrome to try the app.
3. For installable offline PWA behaviour, the folder must be hosted on an HTTPS website. Then open the website in Chrome and choose **Install app** or **Add to Home screen**.
4. To produce a Play Store APK/AAB, the web app must later be wrapped and tested using an Android build environment, then signed and published through a Google Play developer account.

## Backup
Use More → Your data → Download data backup. Export the CSV for spreadsheet use.
