# DITS CRM Billing Mobile Apps

This repository builds two Android WebView APK files from GitHub Actions:

- **Admin App** → opens `https://billing.dits.com.pk/admin/`
- **Customer App** → opens `https://billing.dits.com.pk/client/`

## Build APK on GitHub

1. Upload all files and folders from this ZIP into your GitHub repository.
2. Open the **Actions** tab.
3. Click **Build Admin and Customer APK**.
4. Click **Run workflow**.
5. After build completes, open the workflow result.
6. Download artifact **DITS-CRM-Billing-APK-Files**.
7. Inside it you will get:
   - `Admin-App.apk`
   - `Customer-App.apk`

## Change URL later

Admin URL file:
`adminApp/src/main/java/com/dits/crmbilling/admin/AdminActivity.java`

Customer URL file:
`customerApp/src/main/java/com/dits/crmbilling/customer/CustomerActivity.java`
