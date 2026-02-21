## Cloud City: Privacy Policy

Welcome to the Cloud City app for Android!

As a developer, I take privacy very seriously. I know how frustrating it is when apps collect your data without your knowledge.

### Data collected by the app

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data created by you (the user) is stored locally on your device only, and can be erased by clearing the app's data or uninstalling it. No analytics software is present in the app.

However, Cloud City integrates third-party services — specifically **Google AdMob** (for advertising) and **Google Play Billing** (for in-app purchases) — which may collect certain data independently. Please refer to the relevant sections below for details.

### Third-party services

#### Google AdMob

Cloud City displays advertisements via Google AdMob. AdMob may collect and use data such as your device's advertising identifier, IP address, and ad interaction data to serve relevant ads. This data is governed by Google's Privacy Policy:

https://policies.google.com/privacy

You can opt out of personalised advertising at any time through your device's settings under **Google → Ads → Opt out of Ads Personalisation**.

#### Google Play Billing

In-app purchases are handled entirely by the Google Play Billing system. Any payment or transaction data you provide is processed by Google and is subject to Google's Terms of Service and Privacy Policy. The app itself does not store or transmit your payment information.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file.

| Permission | Why it is required |
| :---: | --- |
| `android.permission.INTERNET` | Required to load game assets via CDN (React, Three.js, Tailwind CSS) and to serve advertisements through Google AdMob. |
| `android.permission.ACCESS_NETWORK_STATE` | Required by Google AdMob to check network connectivity before attempting to load ads, ensuring a smooth experience when offline. |
| `com.android.vending.BILLING` | Required to facilitate in-app purchases through the Google Play Billing system. Without this permission, no purchases can be made within the app. |
| `android.permission.WAKE_LOCK` | An optional permission that prevents the device screen from dimming or turning off while you are actively playing the game. |

---

If you find any security vulnerability that has been inadvertently introduced, or have any question regarding how the app protects your privacy, please reach out and I will do my best to help.