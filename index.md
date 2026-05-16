---
title: Privacy Policy
---

# Privacy Policy for Logly

Effective date: May 16, 2026

Logly is a business trip logging app published by deviapps. This Privacy Policy explains what information Logly collects, how it is used, how it is protected, and the choices you have.

If you have questions or privacy requests, contact us at [deviapps@atomicmail.io](mailto:deviapps@atomicmail.io).

## Information Logly Collects

Logly is designed as a local-first app. Most app data is stored on your device unless you choose to back it up, export it, or enable usage analytics.

### Trip and Vehicle Logbook Data

Logly stores the trip information you enter or record, including:

- trip start and end times;
- trip start and end addresses;
- trip purpose or reason;
- trip distance;
- route points and start/end GPS coordinates for tracked trips;
- opening and closing odometer readings, when provided or calculated;
- tax year configuration, fuel rates, maintenance rates, reimbursement settings, and calculated rebate amounts;
- app settings such as theme preference and analytics consent.

This data is used to record business trips, calculate travel reimbursement or tax logbook values, show trip history, and generate backup or export files.

### Location Data

Logly uses location data to record trips and calculate distance. When you start trip recording, Logly may collect precise GPS location, route points, timestamps, and related location metadata such as accuracy, altitude, or speed. Location collection can continue while a trip is being recorded, including when the app is in the background, so that the trip can be logged accurately.

Before recording location, Logly requests the required Android location permissions. You can revoke location permissions in your device settings, but trip recording features may not work without them.

### Google Drive Backup Data

Google Drive backup is optional. If you choose to connect Google Drive, Logly uses Google Sign-In to access your Google Drive app data folder. Logly may store your connected Google account email address, display name, and profile photo URL locally so the app can show the connected backup account.

When Drive backup is enabled, Logly stores a backup file named `logly_backup.json` in your Google Drive app data folder. This backup can include your trips, route/location data, tax year settings, app settings, and related backup metadata. Logly uses the limited `drive.appdata` scope, which is intended for app-specific Drive data.

### Analytics, Diagnostics, and Session Data

If you grant usage analytics consent, Logly may collect app events, diagnostic information, crash or error details, app version, screen names, session identifiers, and usage information to help improve reliability and understand app behavior.

Logly uses Microsoft Application Insights for structured telemetry and Microsoft Clarity for mobile app analytics and session replay. Clarity may collect screen layout information, interactions, and device/app metadata. Logly pauses Clarity capture unless usage analytics consent is granted.

When a Google account is connected, Logly does not send the raw email address to Application Insights. Instead, Logly may use a SHA-256 hash of the account email for pseudonymous correlation. Logly also uses pseudonymous installation and session identifiers for analytics.

## How Logly Uses Information

Logly uses information to:

- record and manage business trips;
- calculate distance, odometer, and reimbursement values;
- display maps, addresses, and route summaries;
- generate SARS logbook Excel exports and JSON backups;
- back up and restore your data through Google Drive when you choose to use that feature;
- remember app settings and connected Drive state;
- provide app diagnostics, analytics, and reliability improvements when analytics consent is granted;
- respond to support and privacy requests.

## Sharing and Service Providers

Logly does not sell your personal information.

Logly may send data to service providers that are necessary for app features:

- Google Maps, Places, and Geocoding services, to show maps and resolve or suggest addresses;
- Google Sign-In and Google Drive, when you choose to connect Drive backup;
- Microsoft Application Insights, for app telemetry when analytics consent allows it;
- Microsoft Clarity, for usage analytics and session replay when analytics consent allows it;
- Android and Google Play services, for app platform functionality such as permissions, networking, and notifications.

If you use export or share features, Logly creates JSON or Excel files and hands them to the apps or destinations you choose. Those user-selected apps or services are responsible for how they handle the exported files after you share them.

## Data Storage and Security

Trip records, settings, and backup metadata are stored locally on your device using app storage such as SQLite and SharedPreferences. Optional Google Drive backups are stored in your Google Drive app data folder.

Data sent over the network is transmitted using HTTPS/TLS where supported by the relevant service, including Google APIs, Microsoft telemetry services, and Google Drive. Logly does not collect Google passwords, does not operate its own account server, and does not embed a Google client secret in the app.

## Data Retention and Deletion

Local app data is retained on your device until you edit it, delete it, reset Logly, uninstall the app, or clear app data through Android settings.

Google Drive backups remain in your Google Drive app data folder until they are replaced, deleted, or removed through Google account or Drive app-data controls. Disconnecting Google Drive in Logly removes the local connected account state from the device, but it may not delete backup files already stored in Google Drive.

Analytics and diagnostic data retained by Microsoft services is subject to the configured retention settings for those services.

You can contact [deviapps@atomicmail.io](mailto:deviapps@atomicmail.io) for privacy questions or deletion assistance. Because Logly does not create a Logly account or store your trip records on a Logly-controlled backend, most deletion actions are controlled from your device, Google Drive, or the services you selected for exports.

## Your Choices

You can:

- deny or revoke location permissions in Android settings;
- stop a trip recording at any time;
- edit or delete trip records in Logly;
- reset Logly to remove local app data;
- choose whether to connect or disconnect Google Drive backup;
- disable usage analytics in Logly settings;
- choose whether and where to share exported files.

## Information Logly Does Not Collect

Logly does not collect payment card details, banking information, contacts, SMS messages, call logs, photos, audio recordings, or advertising identifiers for advertising. Logly does not use personal data for advertising and does not sell personal data.

## Children's Privacy

Logly is intended for business travel logging and is not directed to children. We do not knowingly collect personal information from children.

## Changes to This Policy

We may update this Privacy Policy when Logly changes or when legal, platform, or service-provider requirements change. The updated policy will be posted at this URL with a revised effective date.

## Contact

For privacy questions or requests, contact:

deviapps  
[deviapps@atomicmail.io](mailto:deviapps@atomicmail.io)