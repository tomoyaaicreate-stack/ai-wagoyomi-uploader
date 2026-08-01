# Privacy Policy — AI Wagoyomi Uploader

Last updated: 2026-08-01

## 1. What this tool is

AI Wagoyomi Uploader is a personal, single-user command-line tool. Its only
purpose is to upload videos that I have produced myself to my own YouTube
channel.

The tool is not distributed, not sold, and not offered as a service to anyone.
I am the only user.

## 2. Use of YouTube API Services

**This application uses YouTube API Services.**

By using this application you are agreeing to be bound by the
**[YouTube Terms of Service](https://www.youtube.com/t/terms)**.

Google's own privacy practices are described in the
**[Google Privacy Policy](https://policies.google.com/privacy)**.

You can revoke this application's access to your data at any time via the
**[Google security settings page](https://myaccount.google.com/permissions)**.

This application's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## 3. What data the tool accesses

The tool uses OAuth 2.0 to obtain permission to write to **my own YouTube
channel only**. It requests these scopes:

- `https://www.googleapis.com/auth/youtube.upload`
- `https://www.googleapis.com/auth/youtube`

Using those permissions, it performs only these operations:

| Operation | Purpose |
|---|---|
| `videos.insert` | Upload a video file I created |
| `thumbnails.set` | Set a thumbnail image I created |
| `playlistItems.insert` | Add the video to one of my own playlists |
| `videos.update` | Correct metadata on my own video if I find a mistake |

## 4. What data is collected

**None.**

The tool does not collect, store, transmit, sell, or share any personal data
about any person. It has no analytics, no telemetry, and no server component.

It does not read, request, or process data belonging to any other YouTube user
or channel. It writes only to my own channel.

## 5. How data is stored

An OAuth access token and refresh token are stored in a single file on my own
computer, in a folder excluded from version control. These tokens are never
transmitted anywhere except to Google's own OAuth and YouTube API endpoints.

No credentials and no user data are stored in this repository, on any server,
or with any third party.

## 6. Sharing with third parties

**None.** The tool communicates with Google / YouTube API endpoints only.
No data is sent to any other party for any purpose.

## 7. Data retention and deletion policy

No user data is retained, because none is collected.

The only stored item is the local OAuth token. It can be deleted at any time by
removing the token file from my computer, which immediately stops the tool from
working until it is re-authorised.

Authorisation can also be revoked from Google's side at
https://myaccount.google.com/permissions — this invalidates the stored token
regardless of whether the local file is deleted.

Because the tool holds no database and no user records, there is nothing else
to delete and no deletion request process is needed.

## 8. Children

The tool has no users other than myself and collects no data, so it neither
targets nor knowingly processes any information relating to children.

## 9. Changes to this policy

Any change to this policy will be committed to this repository, so the full
revision history is publicly visible.

## 10. Contact

For any question about this tool, please contact the repository owner through
the contact address listed on the associated YouTube channel:
https://www.youtube.com/channel/UC6gs5VS8bFNF3moWmCwadHA
