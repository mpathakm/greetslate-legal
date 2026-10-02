# Privacy Policy for GreetSlate

**Effective date:** 30 September 2026  
**App:** GreetSlate (Android package `com.greetslate`)  
**Developer:** Manoj Pathak  
**Contact:** manojpathakiiita@gmail.com

This policy explains what GreetSlate does with information when you install and use the app. It is written for the Google Play listing and for people who use the app.

GreetSlate does not have user accounts. It does not ask you to sign in. It does not sell personal information. It does not show ads. It does not upload your name, your photos, your greeting text, or your place name to the developer’s servers.

Some information stays on your phone. Some information is sent to service providers so the app can load greeting content and, if you allow it, record anonymous usage. Those cases are described below.

## 1. Who this policy covers

This policy applies to the GreetSlate mobile app published on Google Play. It does not apply to other websites or apps you open when you share a card, such as WhatsApp, Messages, or Instagram. Those services have their own policies.

If you do not agree with this policy, do not use the app. You can stop use at any time by uninstalling it.

## 2. Summary

| Topic | What happens |
| --- | --- |
| Account | None. No sign-in, no password, no profile on our servers. |
| Name you type | Stored only on your phone, to print on a card if you turn that on. |
| Photos you pick | Stored only in the app’s private files on your phone, unless you save or share a card. |
| Location | Optional. Approximate location is used to find a city and region. Coordinates are not saved. The city text is saved only on your phone. |
| Usage analytics | Optional, on by default. Anonymous app events are sent to Google Analytics for Firebase. You can turn this off in Settings. |
| Greeting content | Images and quotes are downloaded from our content host (Supabase). The request does not include your name or photos. |
| Ads and sale of data | None. |

## 3. Information stored only on your phone

The app saves preferences in local storage on the device (Android app storage). The developer does not receive a copy of this information. It includes:

- The language you choose (English or Hindi).
- The name you enter for the signature, if you enter one.
- Whether the signature shows your name, the date, your photo, or your city.
- The city and region text, such as “Ottawa, Ontario”, if you turn on “Include my location”, and the time that text was last updated.
- The signature photo file, if you add one. It is copied into the app’s private files so it is still available after the original gallery item changes.
- Whether daily notifications are on, and the time you chose.
- Whether religious images are included, and which tradition you selected.
- Whether anonymous usage analytics are on.
- Whether you have finished first-time setup.
- A random identifier created on the device, used only to remember which cards you have already skipped on that phone. It is not an account and it is not sent to the developer.

Uninstalling the app deletes this local information from the phone. Clearing the app’s storage in Android settings does the same.

## 4. Location

Location is off until you turn on “Include my location” in setup, Settings, or the signature options for a card.

When you turn it on, the app asks Android for **approximate location** (coarse location), not precise GPS. Android may show a permission prompt. If you refuse, the switch stays off and the rest of the app still works.

The app uses that approximate position once to ask the phone’s geocoder for a place name. On Android, that geocoder is provided by the device, usually through Google Play services. The coordinates are held in memory only long enough to make that request. GreetSlate does not write the coordinates to storage, does not send them to the developer, and does not send them to Supabase or to Firebase.

What is saved on the phone is the human-readable result: city and region when both are available, otherwise a broader place name. Street, neighborhood, and postal code are not kept. The saved label can be wrong by a few kilometers, and it can be out of date until the next refresh.

While the setting stays on, the app may refresh that city about once a day when the app is open. It does not track you in the background and it does not request background location. Turning the setting off deletes the saved city text from the app’s settings.

If you leave the city on the signature and then share or save the card, that city text is part of the picture. After you share, the developer cannot remove it from the message you already sent.

## 5. Photos and files

The app can open your photo library only after you tap a control to choose a picture, for a card background or a signature photo. It uses the system picker. It does not scan your gallery in the background, and it does not use the camera.

A picture you choose for the signature is stored in the app’s private files on the phone. A picture you choose as a card background is used for that card.

If you tap save, the finished card image is written to your photo library, which you permit with the save permission Android requires. If you tap share, the image is handed to the Android share sheet and then to the app you pick. The developer does not upload that image to the developer’s own servers.

## 6. Notifications

If you turn notifications on, the app asks for permission to post notifications and schedules a daily reminder at the time you chose. The reminder text is a greeting title such as “Good Morning”. It does not contain your name, your city, or your photos.

Notification settings stay on the phone. The developer does not operate a push server that stores your device token for marketing.

## 7. Usage analytics

If “Share anonymous usage data” is on, the app sends usage events to **Google Analytics for Firebase**, operated by Google. This is on by default. You can turn it off in Settings. When it is off, the app stops sending these events.

The events describe how the app is used, not who you are. They can include:

- Which screen was opened.
- Greeting category and detail, such as daily / good morning.
- App language (English or Hindi).
- Whether a card used a gallery photo, a signature photo, an accent, or decorations, as yes/no or a count.
- Font style and font size chosen for a card.
- Whether notifications, religious images, or a signature photo are enabled, as yes/no flags when you save settings.
- Whether a content request failed, and a short reason such as timeout.

The app is written so these events do **not** include your name, your photos, the quote text, file paths, latitude, longitude, or the city label.

Google’s Firebase SDK may also process standard technical data that comes with Analytics, such as an app-instance identifier, device model, operating-system version, and general locale. Advertising ID collection is turned off in this app. The developer does not use Analytics to identify you or to build an advertising profile.

Google’s use of that information is described in Google’s privacy policy: https://policies.google.com/privacy

The developer uses these events to see which greetings are used, which actions fail, and whether a change made the app better. The developer does not sell this information.

## 8. Greeting content downloaded by the app

Quotes and background images are loaded from **Supabase**, a hosted database and file service. The app sends the kind of greeting you asked for (for example category, language, and a content id) so the service can return a quote and an image. Those requests are not an account. They are not your name, your photo, or your location.

Supabase and the network operator can see normal connection data, such as the IP address of the phone, as part of delivering the download. The developer uses that service to host the greeting catalog, not to build a profile of you.

Supabase’s privacy information is at https://supabase.com/privacy

## 9. When you share or save a card

A finished card can show the quote, your name, the date, your photo, and your city, depending on the switches you turned on. Sharing or saving is an action you take. The image then goes to your gallery or to the other app you chose. The developer does not control that other app and does not receive the image back.

## 10. Android permissions

The app requests only the permissions it needs for the features above.

| Permission | Why |
| --- | --- |
| Internet | Download greeting quotes and images, and send optional analytics. |
| Approximate location (`ACCESS_COARSE_LOCATION`) | Only if you turn on “Include my location”, to resolve a city and region. |
| Notifications | Only if you turn on daily reminders. |
| Exact alarm scheduling | So a reminder you set for a clock time can fire at that time. |
| Photos / storage, as required by your Android version | Only when you pick a photo, or when you save a card to the gallery. |
| Vibration | For the notification channel. |

The app does not request precise location, background location, camera, contacts, microphone, SMS, or phone-state access. The Advertising ID permission is removed from the app.

## 11. How information is used

Information is used to:

- Show the app in the language you chose.
- Build and display the greeting card you asked for.
- Remember your signature and notification choices on that phone.
- Deliver the daily reminder you turned on.
- Show a city on the card if you opted in.
- Understand aggregate app usage and fix failures, if analytics is on.

The developer does not use this information for advertising, credit, insurance, or employment decisions, and does not sell it.

## 12. Who information is shared with

The developer does not sell personal information and does not share your name, photos, or city label with a data broker.

Information can be processed by:

- **Google (Firebase Analytics)** — usage events, if you leave analytics on.
- **Google Play services / the device geocoder** — approximate coordinates, only in the moment you look up a city, if you turn location on. The developer does not receive those coordinates.
- **Supabase** — the content request needed to download a quote and image.
- **The app you pick in the share sheet, and your photo library** — the card image, only when you share or save.

The developer may also disclose information if required by law, or to protect the rights and safety of users, and only to the extent the law requires. Because the developer does not hold your card content on a server, there is usually nothing of that kind to disclose.

## 13. How long information is kept

On the phone, preferences and the signature photo stay until you change them, turn a feature off, clear the app’s storage, or uninstall the app. Turning off “Include my location” removes the saved city text.

Analytics events are kept by Google under the retention settings of the Firebase project and Google’s policies. The developer does not keep a separate database of those events tied to your name, because the app does not send your name.

Content requests to Supabase are not stored by the developer as a user history.

## 14. Your choices

- **Location:** leave “Include my location” off, or turn it off later. You can also deny or revoke approximate location in Android settings.
- **Analytics:** turn off “Share anonymous usage data” in Settings.
- **Notifications:** turn them off in the app, or revoke notification permission in Android settings.
- **Photos:** do not pick a photo. Delete a signature photo by turning off the signature image. Remove a saved card from your gallery yourself.
- **All local data:** uninstall the app, or clear its storage in Android settings.

The app has no account, so there is no online profile to delete. If analytics was sent before you turned it off, the developer cannot look up those events by your name. You can also use Google’s tools for Analytics and advertising controls described in Google’s privacy policy.

If you are in the European Economic Area, the United Kingdom, or another region that gives you rights to access, correct, or delete personal data, or to object to certain processing, contact the email at the top of this policy. Because name, photos, and the city label stay on your device, the practical way to delete them is to remove them in the app or uninstall it.

## 15. Children

GreetSlate is a general greeting app. It is not directed at children under 13, and the developer does not knowingly collect personal information from children. The app has no account signup. If you believe a child has provided personal information through the app, contact the email at the top of this policy.

## 16. Security

Local data is kept in the app’s private storage, which other apps cannot read on a normal Android device. Connections to Supabase and Google use HTTPS. No method of storage or transmission is perfectly secure. Do not include secrets in a greeting quote or in the name field.

## 17. International use

The app can be used outside the country where the developer lives. Supabase and Google may process technical and analytics data in countries other than yours, including the United States. Those providers are responsible for their own international transfers under their policies.

## 18. Changes to this policy

If this policy changes, the developer will update the effective date at the top and post the new version at the same public web address used on the Play listing. If a change materially expands how personal information is used, the app or the store listing will say so in plain language. Continued use after the new date means you accept the updated policy. If you do not accept it, uninstall the app.

## 19. Contact

Questions about this policy or about the app’s privacy practices:

**Manoj Pathak**  
**Email:** manojpathakiiita@gmail.com