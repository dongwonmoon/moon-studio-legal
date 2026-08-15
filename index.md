# Morrow Privacy Policy

Effective date: 2026-08-15

Morrow is a personal reading record app. This policy describes how Morrow
handles user data, including the optional Google Drive backup.

## Developer and contact

- App: Morrow
- Developer: Moon Studio
- Privacy contact: moon.studio.privacy@gmail.com

## Data you create in the app

Morrow lets you create private reading records. A record may include:

- text you enter, such as a quote, page, or memo;
- photos you attach from the camera or photo library;
- book information you select from book search results;
- local metadata needed to show, edit, sort, or delete your records.

## Local storage

Morrow stores reading records on your device. Attached photos are copied into
app-owned local storage, and record metadata is stored in the app's local
database.

## Camera and photo access

Morrow requests camera or photo-library access only when you choose to attach a
photo to a reading record.

- Camera access is used to take a new photo for a record.
- Photo-library access is used to select an existing image for a record.

Morrow does not use camera or photo access for advertising, tracking, or
background collection.

## Book search

When you search for a book, the search query is sent to Morrow's book-search
API so that the app can return matching book results. The API may forward the
query to an external book-search provider.

Book search is used only to help you connect a book to a reading record.

## Google Drive backup

Morrow offers an optional backup that you can turn on from Settings. It is off
until you choose to connect a Google account.

- When you connect a Google account, Morrow uploads versioned snapshots of your
  reading records and attached photos to an app-private folder on your own
  Google Drive. The folder uses Google's drive.appdata scope: only Morrow can
  read or write it, it is not visible to other apps, and Moon Studio cannot
  read it.
- Backups run automatically after you record something, and you can also run
  one manually from Settings. Records and photos are never uploaded to Moon
  Studio's servers.
- If you reinstall the app or move to a new device, you can restore your
  records and photos from the Drive backup. Restoring onto a device that
  already has records is never automatic: the app asks you to choose between
  replacing the device's records with the backup and keeping them, and shows
  how many records and photos each choice affects.
- You can disconnect Google Drive from Settings at any time. Existing Drive
  backups remain stored in your Drive until you delete them. You can
  permanently delete every Morrow backup from your Drive in Settings.

## Accounts, backup, and sync

Morrow has no account of its own. The only third-party connection is the
optional Google Drive backup described above.

Morrow does not offer multi-device sync, public profiles, social sharing,
advertising, or analytics tracking. If Morrow later adds accounts, sync, paid
features, sharing, analytics, or other server-backed features, this policy
will be updated before those features are released.

## Sharing and sale of data

Morrow does not sell personal data.

Reading records and attached photos are stored on your device and, only when
you enable backup, copied to an app-private folder in your own Google Drive.
They are never uploaded to Moon Studio's servers. Book-search queries are sent
over the network only to provide book-search results.

## Retention and deletion

You can delete individual reading records in the app. When a record is
deleted, Morrow removes the local record and attempts to remove the app-owned
local photo files attached to that record. If Drive backup is on, the next
backup reflects the deletion.

You can permanently delete the Drive backups from Settings; this also
disconnects Google Drive.

If you delete the app or clear its data without Drive backup, local records
and photos cannot be recovered.

## Security

Morrow keeps reading records and attached photos in app-owned storage on your
device. Drive backup transfers are encrypted in transit and stored in your
Google Drive account. Network requests, such as book search and Drive access,
are sent over HTTPS in production.

## Children

Morrow is not designed for children and is not intentionally directed to
children.

## Changes to this policy

This policy may be updated when Morrow's behavior changes.
