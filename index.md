# Morrow Privacy Policy

Effective date: 2026-06-24

Morrow is a personal reading record app. This policy describes how the first
Android release handles user data.

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

The first Android release stores reading records on your device. Attached
photos are copied into app-owned local storage, and record metadata is stored in
the app's local database.

Morrow does not currently provide account backup, cloud sync, public profiles,
or social sharing. If you delete the app, lose the device, or move to another
device before a backup/sync feature exists, your local records and photos may
not be recoverable.

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

## Accounts, backup, and sync

The first Android release does not offer active account creation, cloud backup,
multi-device sync, public sharing, advertising, or analytics tracking.

If Morrow later adds accounts, backup, sync, paid features, sharing, analytics,
or other server-backed features, this policy should be updated before those
features are released.

## Sharing and sale of data

Morrow does not sell personal data.

In the first Android release, your reading records and attached photos are not
uploaded to Morrow's servers for storage. Book-search queries are sent over the
network only to provide book-search results.

## Retention and deletion

You can delete individual reading records in the app. When a record is deleted,
Morrow removes the local record and attempts to remove the app-owned local photo
files attached to that record.

Because the first Android release is local-first, deleting the app or clearing
the app's data may remove local records and attached photos from the device.
Morrow does not currently maintain a cloud copy that can restore them.

## Security

Morrow keeps reading records and attached photos in app-owned storage on your
device. Network requests, such as book search, should be sent over HTTPS in
production.

## Children

Morrow is not designed for children and is not intentionally directed to
children.

## Changes to this policy

This policy may be updated when Morrow's behavior changes, especially if account
backup, sync, sharing, analytics, or other server-backed features are added.
