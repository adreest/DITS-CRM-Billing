# DITS CRM Billing Android Apps

This is a complete GitHub-ready Android WebView project for two APKs:

- **Admin App** opens `https://billing.dits.com.pk/admin/`
- **Customer App** opens `https://billing.dits.com.pk/client/`

## What is included

- Two separate Android app modules: `adminApp` and `customerApp`
- Proper WebView configuration
- JavaScript, DOM storage, cookies, mixed content support
- File upload support from CRM forms
- Download support for PDFs, invoices, documents, reports
- Back button support inside WebView
- Internet/offline message
- Splash/progress loading bar
- Separate app labels/icons
- Android permissions
- GitHub Actions workflow at `.github/workflows/build-apk.yml`
- APK artifact output names:
  - `Admin-App.apk`
  - `Customer-App.apk`

## Build on GitHub

1. Extract this ZIP.
2. Upload all files/folders to GitHub repository root.
3. Open **Actions** tab.
4. Run **Build Admin and Customer APK**.
5. Download artifact **DITS-CRM-Billing-APK-Files**.

## Important note about full CRM inside APK

Your CRM/Billing Software is PHP/MySQL based, so the complete working system cannot run fully offline inside a 3MB-10MB Android APK. This app runs your full live CRM inside Android using WebView. Admin and Customer panels will work exactly as your hosted web software works.

For real push notifications, Firebase keys are required. See `docs/FIREBASE_PUSH_NOTIFICATION_SETUP.md`.
