# Starboard Reviews 2.10.1

* Added: custom review forms reuse existing Cloudflare Turnstile keys, with server-side token, hostname and action verification.
* Added: review honeypots, attempt throttling and verification replay checks; verification failures never create a review or upload a photo.
* Improved: lazy verification in review dialogs, retry states and fresh checks after submissions.
* Improved: scoped control resets protect widget buttons, fields and reviewer spacing from Elementor and theme globals.
