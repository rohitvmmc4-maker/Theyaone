# THEYA WELLNESS app (PWA starter)

## Included
- Responsive premium gold/ivory clinic interface
- Theya logo and supplied Dr. Soumya photograph
- Treatment catalogue based on the current Theya Wellness website
- Patient appointment request form
- Preferred date and two-hour time-window selection (10–12, 12–2, 2–4, 4–6, 6–7)
- WhatsApp handoff to +91 96676 62291
- Clinic address, Google Maps directions and embedded map
- PWA manifest and basic service worker

## Preview
Open `index.html` in a browser. For PWA installation, host the folder on HTTPS (for example GitHub Pages or your website), then open it in Chrome on Android and choose **Install app** / **Add to Home screen**.

## Important booking behaviour
This starter sends an appointment REQUEST to WhatsApp. It does not connect to a clinic calendar/database, prevent double booking, or confirm a slot automatically. A live booking system requires a backend/admin calendar and secure data handling.

## Publish to your website
Upload the contents of this folder to a dedicated directory on your hosting, or deploy the folder as a separate GitHub Pages site. Keep the `assets` folder alongside `index.html`.

## Android APK
This is a Progressive Web App source bundle, not a signed APK. To create an APK, first host it on HTTPS and wrap the URL using Android Studio WebView or a Trusted Web Activity (Bubblewrap). A release APK needs signing and testing on Android devices.
