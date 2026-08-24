# Morrow Privacy Policy

Effective date: 2026-08-24

Morrow is a personal reading record app. This policy describes how the Android
app handles user data.

## Developer and contact

- App: Morrow
- Developer: Moon Studio
- Privacy contact: moon.studio.privacy@gmail.com

## Data you create in the app

Morrow lets you create private reading records. A record may include:

- a short memo you enter about what you read;
- photos you attach from the camera or photo library;
- book information you select from book search results;
- local metadata needed to show, edit, sort, or delete your records.

## Local storage

Morrow stores reading records on your device. Attached photos are copied into
app-owned local storage, and record metadata is stored in the app's local
database. The device remains the working copy and source for editing records.

You may optionally connect Google Drive for recovery backup as described below.
Morrow does not provide a Morrow account, multi-device sync, public profiles, or
social sharing in the production app.

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

## Book recommendation

When you open the discovery tab, Morrow sends the memo text from your recent
reading records to Morrow's recommendation API so it can rank books that relate
to what you wrote. The API forwards that text to an embedding provider to
compute the ranking.

Your memo text is used only to produce that ranking. It is not stored on
Morrow's servers, and attached photos are never sent.

## Accounts, backup, and sync

Morrow does not require or create a Morrow account. If you choose to connect
Google Drive, Morrow requests the limited `drive.appdata` permission and writes
an opaque recovery archive to your own hidden Google Drive app data folder. The
archive can contain memo text, page context, linked-book information, and the
app-owned copies of photos attached to your records.

After you connect Drive, Morrow may update the backup automatically when your
local archive changes. Morrow reads back its own archive to verify uploads and
may download it to restore records. It keeps the newest two fully verified
archive copies for recovery safety. These files are not sent to or stored on
Morrow's servers.

Settings lets you disconnect the Drive session without deleting the remote
backup, or permanently delete recognized Morrow backup files. Permanent backup
deletion also disconnects Drive authorization so automatic backup cannot
immediately recreate the deleted files. Morrow may show the selected Google
account email or identifier in Settings and use the account identifier to
revoke access; it does not send that account information to Morrow's servers.

Drive backup is recovery, not real-time or multi-device sync. Google manages
encryption in transit and at rest. Morrow does not add application-layer
end-to-end encryption or a separate backup passphrase.

## Sharing and sale of data

Morrow does not sell personal data.

Your reading records and attached photos are not uploaded to Morrow's servers
for storage. If you enable Drive backup, they are uploaded only to your own
Google Drive app data folder under Google's terms and privacy policy.
Book-search queries and memo text used by Discover are sent over the network
only to return search results or a book ranking as described above.

## Retention and deletion

You can delete individual reading records in the app. When a record is deleted,
Morrow removes the local record and attempts to remove the app-owned local photo
files attached to that record.

Deleting the app or clearing its data may remove local records and attached
photos from the device. If you previously enabled Drive backup and did not
permanently delete it, Morrow may be able to restore a verified backup after you
reconnect the same Google account. Morrow does not guarantee recovery from an
incomplete, corrupt, deleted, or inaccessible provider archive.

Deleting one local record is reflected in a later successful backup rather
than deleting an individual object from Drive immediately. You can permanently
delete every recognized Morrow backup copy from Settings; Morrow confirms their
absence before clearing its local backup state.

## Security

Morrow keeps its working records and attached photos in app-owned storage on
your device. Production network requests use HTTPS. Google Drive backup uses
Google-managed encryption in transit and at rest but is not end-to-end
encrypted by Morrow.

## Children

Morrow is not designed for children and is not intentionally directed to
children.

## Changes to this policy

This policy may be updated when Morrow's behavior changes, especially if a
Morrow account, sync, public sharing, analytics, or other server-backed
features are added.
