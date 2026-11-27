# 1TV privacy policy

Last updated: 27 November 2026

1TV is an IPTV and media player for Windows, Android phones and Google TV. It has no server and no user accounts of its own, and its developer receives none of your data.

## Data on your device

Your sources (including provider logins), favourites, watch progress, settings, downloads and recordings are stored on your device. Provider logins are encrypted with the device's own protection (Windows DPAPI, Android Keystore).

## Sync with Google

Sync is optional. When you choose **Sign in with Google**, 1TV asks for:

- `drive.appdata`: access to a hidden folder in your Google Drive that only 1TV can read. 1TV keeps two files there: your synced data, encrypted with AES-256-GCM, and the random key that encrypts it. 1TV can't see or change any other file in your Drive.
- `email` and `openid`: your account's email address, shown in Settings so you know which account syncs.

This data goes straight between your devices and your Google account. 1TV doesn't send it anywhere else, and doesn't use it for advertising or anything other than sync. To stop syncing, choose **Sign out** in Settings. To delete the synced data, open Google Drive → Settings → Manage apps → 1TV → Delete hidden app data, then remove 1TV's access at https://myaccount.google.com/permissions.

1TV's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Other services

To show artwork, descriptions, subtitles and skip-intro times, 1TV sends titles (not your identity) to public services: Cinemeta, Wikidata, TVmaze, OpenSubtitles, TheIntroDB, AniSkip and Jikan. Streams and guides come from the providers you add. Updates are downloaded from this GitHub repository.

## Contact

onetv.support@gmail.com
