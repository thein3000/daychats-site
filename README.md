# Day Chats

Static site for [daychats.com](https://daychats.com). `index.html` is the landing page; `privacy/index.html` serves the privacy policy at `/privacy/`. `privacy.md` is the policy source. Keep its wording and `CNAME` intact.

Both pages are standalone HTML with identical inline CSS, header, and footer. The app’s LaunchMark is embedded as a PNG data URI. There are no runtime dependencies, scripts, fonts to download, forms, or tracking.

Preview locally with `python3 -m http.server 8765` and open `http://localhost:8765/`.

The two “Join the beta on TestFlight” links currently use `href="#"`. When a public TestFlight URL is available, replace both destinations and update the “Public beta link coming soon.” note. Contact uses the email already published in the privacy policy.

Review screenshots and validation evidence are in `.github/review/`; they are not page dependencies.
