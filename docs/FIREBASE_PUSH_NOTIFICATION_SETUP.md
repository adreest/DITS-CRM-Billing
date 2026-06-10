# Firebase Push Notification Setup

Push notification code needs Firebase project keys from the app owner.

Required later:

1. Create Firebase project.
2. Add Android app package:
   - Admin: `com.dits.crmbilling.admin`
   - Customer: `com.dits.crmbilling.customer`
3. Download `google-services.json` for each app.
4. Add Firebase Messaging dependency and service.
5. Connect CRM backend to Firebase Cloud Messaging server API.

Without Firebase keys and backend token saving API, real push notifications cannot work. This project already has notification permission ready for Android 13+.
