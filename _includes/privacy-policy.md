# Privacy Policy for Fridgerio

**Effective Date:** March 22, 2026
**Last Updated:** March 22, 2026

Adam Lukac ("we," "our," or "us") built Fridgerio as a freemium app. This Privacy Policy explains how we collect, use, and protect your information when you use Fridgerio.

By using Fridgerio, you agree to the practices described in this Privacy Policy. If you do not agree, please do not use the app.

---

## 1. Information We Collect

### Information You Provide Directly

- **Product data:** Product names, expiry dates, storage locations, quantities, and categories you enter or scan within the app.
- **Shopping lists:** Shopping list names and items you create.
- **Product photos:** Images you capture for product identification and expiry date scanning. Photos are stored on your device only.
- **Custom products:** Product templates you create for quick entry.
- **Support requests:** If you contact us for support, we collect your email address and the content of your message.

### Information Collected Automatically

- **Barcode lookups:** When you scan a product barcode, the barcode number is sent to Open Food Facts (a public, open-source food database) and UPCitemdb to retrieve product information such as name, brand, category, and nutrition data. No personal information is sent with these requests.

### Information We Do NOT Collect

- We do not collect personal information such as your name, email, or phone number.
- We do not require account creation.
- We do not use analytics or tracking SDKs.
- We do not track you across other apps or websites.
- We do not collect your location.
- We do not use advertising identifiers (IDFA).
- All data stays on your device unless you explicitly enable iCloud sync.

---

## 2. How We Use Your Information

We use the information you provide to:

- Provide Fridgerio's core functionality (inventory tracking, expiry reminders, shopping lists)
- Look up product information from public food databases using scanned barcodes
- Send local notifications about expiring products (processed entirely on your device)
- Sync your data across your Apple devices via iCloud (if you enable it)

We do NOT use your information to:

- Sell your data to third parties
- Build advertising or marketing profiles
- Track your behavior or usage patterns
- Make automated decisions that affect you

---

## 3. How We Share Your Information

We do not sell, rent, or trade your personal information.

We may share information in the following limited circumstances:

- **Barcode lookups:** When you scan a barcode, the barcode number (EAN/UPC code only) is sent to third-party product databases to retrieve product details. No personal data is included in these requests.
- **iCloud sync:** If you enable iCloud, your product data is synced via Apple's CloudKit infrastructure, subject to [Apple's Privacy Policy](https://www.apple.com/privacy/).
- **Legal requirements:** We may disclose information if required by law, regulation, legal process, or government request.

---

## 4. Third-Party Services

Fridgerio uses the following third-party services:

| Service | Purpose | Data Sent | Privacy Policy |
|---------|---------|-----------|----------------|
| Open Food Facts | Product barcode lookup (name, brand, nutrition, scores) | Barcode number only | [Open Food Facts Privacy](https://world.openfoodfacts.org/privacy) |
| UPCitemdb | Fallback barcode lookup (name, brand, category) | Barcode number only | [UPCitemdb Privacy](https://www.upcitemdb.com/wp/privacy) |
| Apple iCloud (CloudKit) | Optional data sync across devices | Product data, shopping lists (encrypted by Apple) | [Apple Privacy Policy](https://www.apple.com/privacy/) |
| Apple StoreKit | In-app subscription purchases | Purchase transaction data (handled by Apple) | [Apple Privacy Policy](https://www.apple.com/privacy/) |

We do not use analytics, advertising, crash reporting, or tracking SDKs.

---

## 5. Data Storage and Retention

- **On-device storage:** All your data (products, shopping lists, photos, custom products) is stored locally on your device using Apple's SwiftData framework.
- **iCloud sync:** If enabled, your data is also stored in Apple's iCloud infrastructure. Apple encrypts this data in transit and at rest.
- **Data retention:** Your data is retained on your device for as long as you use the app. When you delete the app, all local data is removed. iCloud data can be managed through your iCloud settings.
- **No server-side storage:** We do not operate any servers. We do not store any of your data on our infrastructure.

---

## 6. Data Security

We implement the following measures to protect your information:

- All data is stored locally on your device using Apple's secure storage frameworks
- All network communications (barcode lookups) use encryption in transit (HTTPS/TLS)
- iCloud data is encrypted by Apple both in transit and at rest
- No data is transmitted to our servers (we do not operate servers)
- On-device processing: barcode scanning and expiry date OCR are performed entirely on your device using Apple's Vision framework

No method of storage is 100% secure, but your data never leaves your device except for barcode lookups (barcode number only) and optional iCloud sync (managed by Apple).

---

## 7. Camera and Photo Usage

Fridgerio uses your device camera for:

- **Barcode scanning:** To identify products by scanning their barcode
- **Expiry date scanning:** To read expiry dates from product packaging using on-device OCR (Apple Vision framework)
- **Product photos:** To capture images for product identification

Camera processing happens entirely on your device. Photos are stored locally and are not transmitted to any server. Camera access requires your explicit permission and can be revoked at any time in iOS Settings.

---

## 8. Your Rights

You have full control over your data:

- **Access:** All your data is visible within the app at all times.
- **Export:** You can export your data as CSV files from the app settings (Pro feature).
- **Deletion:** You can delete individual products, shopping lists, or all data from within the app. Deleting the app removes all local data.
- **iCloud data:** You can manage or delete iCloud data through iOS Settings > Apple ID > iCloud.

### For European Union Residents (GDPR)

If you are located in the European Economic Area (EEA), you have additional rights under the General Data Protection Regulation (GDPR):

- **Data controller:** Adam Lukac, fridgerio.app@gmail.com
- **Lawful basis for processing:** We process your data based on:
  - Performance of a contract (providing the service you requested)
  - Your consent (iCloud sync, camera access — which you can withdraw at any time)
- **Data subject rights:** You have the right to:
  - Access your personal data
  - Rectify inaccurate data
  - Erase your data ("right to be forgotten")
  - Restrict processing of your data
  - Data portability (export your data)
  - Object to processing
  - Lodge a complaint with your local Data Protection Authority
- **Data transfers:** Barcode lookups are sent to Open Food Facts (servers in Europe) and UPCitemdb (servers in the United States). iCloud data transfers are handled by Apple under their data processing agreements.
- **Data retention:** We retain data only on your device and/or in your iCloud account. We do not maintain separate data stores.
- **Supervisory authority:** You may lodge a complaint with the Office for Personal Data Protection of the Slovak Republic (Úrad na ochranu osobných údajov SR) or your local supervisory authority.

### For California Residents (CCPA)

If you are a California resident:

- **Right to know:** We collect only the data categories described in Section 1. We do not sell your personal information.
- **Right to delete:** You can delete all your data from within the app or by deleting the app.
- **Right to opt-out:** We do not sell or share your personal information. No opt-out is necessary.
- **Non-discrimination:** We will not discriminate against you for exercising your CCPA rights.

---

## 9. Children's Privacy

Fridgerio is not intended for children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us at fridgerio.app@gmail.com.

---

## 10. Subscriptions

Fridgerio offers optional paid subscriptions (Fridgerio Pro) with weekly, annual, and lifetime options:

- Subscriptions are processed and managed entirely by Apple through the App Store.
- We do not collect or store your payment information.
- Subscriptions automatically renew unless cancelled at least 24 hours before the end of the current period.
- You can manage and cancel subscriptions in iOS Settings > Apple ID > Subscriptions.
- Free trial periods, if offered, automatically convert to paid subscriptions unless cancelled before the trial ends.
- Refund requests must be submitted through Apple: [https://reportaproblem.apple.com](https://reportaproblem.apple.com)

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make changes, we will:

- Update the "Last Updated" date at the top of this document
- Post the updated policy at [https://fridgerio.app/privacy](https://fridgerio.app/privacy)

Your continued use of Fridgerio after changes are posted constitutes acceptance of the updated Privacy Policy.

---

## 12. Contact Us

If you have questions or concerns about this Privacy Policy or our data practices, contact us at:

- **Email:** fridgerio.app@gmail.com
- **Developer:** Adam Lukac
- **Website:** https://fridgerio.app
