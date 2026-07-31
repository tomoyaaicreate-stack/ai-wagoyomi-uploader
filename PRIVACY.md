Privacy Policy — AI Wagoyomi Uploader
Last updated: 2026-08-01

What this tool is
AI Wagoyomi Uploader is a personal, single-user command-line tool. Its only purpose is to upload videos that I have produced myself to my own YouTube channel, using the YouTube Data API v3.

The tool is not distributed, not sold, and not offered as a service. I am the only user.

What data the tool accesses
The tool uses OAuth 2.0 to obtain permission to write to my own YouTube channel only. It requests these scopes:

https://www.googleapis.com/auth/youtube.upload
https://www.googleapis.com/auth/youtube
Using those permissions, it performs only these operations:

Operation	Purpose
videos.insert	Upload a video file I created
thumbnails.set	Set a thumbnail image I created
playlistItems.insert	Add the video to one of my own playlists
videos.update	Correct metadata on my own video if I find a mistake
What data is collected
None.

The tool does not collect, store, transmit, sell, or share any personal data about any person. It has no analytics, no telemetry, and no server component.

It does not read, request, or process data belonging to any other YouTube user or channel. It writes only to my own channel.

Where credentials are stored
An OAuth access token and refresh token are stored in a single file on my own computer, in a folder that is excluded from version control. These tokens are never transmitted anywhere except to Google's own OAuth and YouTube API endpoints.

No credentials are stored in this repository.

Third parties
The tool communicates with Google / YouTube API endpoints only. It sends no data to any other third party.

Its use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements.

Revoking access
Access granted to this tool can be revoked at any time from the Google Account permissions page at https://myaccount.google.com/permissions.

Data retention and deletion
No user data is retained, because none is collected. The locally stored OAuth token can be deleted at any time by removing the token file, which immediately stops the tool from working until it is re-authorised.

Contact
For any question about this tool, please contact the repository owner through the contact address listed on the associated YouTube channel: https://www.youtube.com/channel/UC6gs5VS8bFNF3moWmCwadHA
