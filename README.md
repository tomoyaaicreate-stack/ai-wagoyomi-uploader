AI Wagoyomi Uploader
A personal command-line tool that uploads my own videos to my own YouTube channel using the YouTube Data API v3.

This is not a product. It is a private utility with one user — me. It is published here only so that the source and the privacy policy are publicly inspectable.

Why it exists
I run AI和ごよみ, a channel about the traditional Japanese calendar — the 24 solar terms, seasonal customs, and the origins of Japanese annual events. I write, narrate and render every video myself.

I publish roughly one video a day. Each upload needs a title, a description with chapter timestamps, a tag list, a thumbnail and a scheduled release time. I already write all of that into a local text file while producing the video. Re-typing it by hand into YouTube Studio is slow and easy to get wrong, so this tool submits it through the API instead.

What it does
Reads the metadata I have already written for an episode
Uploads the video file
Sets the title, description, tags and scheduled publish time
Uploads the thumbnail
Adds the video to the relevant playlist
What it deliberately does not do
It does not read or collect data about any other user or channel
It does not display YouTube content anywhere
It has no server, no database, no analytics and no telemetry
It is not distributed to anyone
API usage
Method	Approx. quota cost	Frequency
videos.insert	1,600 units	once per upload
thumbnails.set	50 units	once per upload
playlistItems.insert	50 units	once per upload
videos.update	50 units	rarely, to fix a mistake
At one upload per day this is roughly 1,750 units — well inside the default quota of 10,000 units per day. No quota extension is needed.

Credentials
OAuth client secrets and tokens are stored locally and are not part of this repository.

Privacy
See PRIVACY.md. In short: the tool collects nothing about anyone.

Licence
Personal use. Not offered for redistribution.
