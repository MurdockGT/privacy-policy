---
title: Personal Library App – Privacy Policy
---

# Personal Library App – Privacy Policy

**Effective date:** November 25, 2026

This Privacy Policy explains how the Personal Library App for Android (package name `com.booklibrary.tracker`, the "App") handles information. The App is developed and published by **Shane Kelly** ("we", "us").

**The short version:** the App has no accounts, no ads, no analytics and no tracking. Your library is stored on your phone. We do not run any servers and we never receive, see, sell or share your data. The only information that leaves your device is the book barcode number (ISBN or ASIN) you look up, which is sent to public book databases so they can return the book's details and cover.

## 1. Information stored on your device

Everything you enter into the App is saved in a private database on your phone, which other apps cannot read. This includes:

- Book details (title, authors, publisher, date, pages, ISBN/ASIN, description, subjects, series, cover images)
- Your own information about each book: reading status, start and finish dates, star rating, comments, shelves, tags, storage location and wishlist entries
- Lending records you create: the borrower's name and an optional return date
- Cover photos you take with the camera or choose from your gallery
- Settings such as theme and sort order, and your optional Hardcover API token

This information stays on your device. We have no access to it.

**Lending records.** If you record that you lent a book to someone, you are storing that person's name on your own phone. It is never sent anywhere by the App.

## 2. Camera

The App asks for camera permission so you can scan barcodes and take cover photos. Camera use is optional; you can always type an ISBN instead.

- **Barcode scanning** is processed entirely on your device using Google ML Kit's on-device barcode scanner. Camera frames are analysed in memory to read the barcode and are not saved or sent anywhere.
- **Cover photos** you take are saved only inside the App's private storage on your phone.

## 3. Internet access and third-party book services

The App uses the internet only to look up book details and download cover images. When you scan or type a barcode, or when the App fills in missing details, it sends **only the ISBN or ASIN** to these services:

| Service | When it is used | Privacy policy |
|---|---|---|
| Open Library (Internet Archive) | ISBN lookups and covers | <https://archive.org/about/terms.php> |
| Google Books | ISBN lookups and covers | <https://policies.google.com/privacy> |
| Hardcover.app | Only if you enter your own Hardcover API token in settings | <https://hardcover.app/privacy> |
| Amazon.com | Fills in missing details for ISBNs and Kindle ASINs by reading the public product page | <https://www.amazon.com/privacy> |

Like any website you visit, these services may receive your device's IP address and basic technical information (such as the request's user-agent string) as part of the normal internet connection. Their handling of that information is governed by their own privacy policies above, not by this one. No other part of your library (titles, ratings, comments, borrower names, etc.) is sent to them.

**Hardcover token.** If you choose to enter a Hardcover API token, it is stored only on your phone and is sent only to Hardcover with your lookup requests, to authenticate you to their service.

## 4. Google ML Kit

The barcode scanner is provided by Google ML Kit. Barcode images are processed on your device. According to Google, ML Kit may contact Google servers to receive updates and may send limited, non-identifying diagnostic and usage information about the ML Kit library's performance to Google. See Google's ML Kit terms at <https://developers.google.com/ml-kit/terms> and Google's privacy policy at <https://policies.google.com/privacy>.

## 5. Backups and exports

- **Automatic backup.** The App saves a backup file (`auto_backup.zip`) inside its own private storage on your phone.
- **Auto-backup folder.** If you pick a folder for automatic backups, the App also writes `BookLibrary_backup.zip` to that folder. If the folder you choose is synced to a cloud service (for example Google Drive), that copy is handled by that service under its own terms.
- **Manual backups and CSV exports** are saved only where you choose to save them.
- **Android backup.** Depending on your device settings, Android may include the App's data in your device backup to your Google account. This is a feature of Android, controlled by you in your device settings, and is handled by Google under its privacy policy.

Backup and export files contain your whole library, including comments and borrower names, so keep them somewhere you trust.

## 6. What we do not do

- We do not require or offer user accounts.
- We do not show ads or include advertising SDKs.
- We do not use analytics, crash-reporting or tracking tools.
- We do not collect your location, contacts, or other personal information.
- We do not sell, rent or share your information with anyone.

## 7. Keeping and deleting your data

Your data stays on your device until you delete it. You can:

- Delete individual books (along with their comments and cover) inside the App
- Clear all App data in Android Settings → Apps → Personal Library App → Storage → Clear data
- Uninstall the App, which removes its private storage

Backup or export files you saved outside the App (for example in your auto-backup folder or Downloads) are not removed when you uninstall; delete them yourself if you no longer want them. Because we never receive your data, there is nothing for us to delete on our side.

## 8. Security

Your library is stored in the App's private storage, which Android protects from other apps. Book lookups to the services above are made over encrypted HTTPS connections. No method of storage or transmission is completely secure, so please protect your phone with a screen lock and store backup files carefully.

## 9. Children

The App is a general-audience book-cataloguing tool and is not directed at children under 13. We do not knowingly collect any personal information from children, and the App does not collect personal information from anyone.

## 10. Changes to this policy

If the App changes in a way that affects your privacy, we will update this policy and change the effective date above. Significant changes will also be noted in the App's release notes on Google Play.

## 11. Contact

If you have questions about this Privacy Policy, contact **Shane Kelly** at **[Genappllc54@gmail.com](mailto:Genappllc54@gmail.com)**.
