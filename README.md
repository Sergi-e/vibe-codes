# Followers Tracker

A privacy-first Instagram followers analysis tool. See who doesn't follow you back, recent unfollowers, and pending follow requests — entirely in your browser, with no data ever leaving your device.

## How it works

Upload your Instagram JSON export files and the app analyses them locally. Nothing is sent to any server.

**Required files from your Instagram export:**
- `followers_1.json`
- `following.json`
- `recently_unfollowed_profiles.json`
- `recent_follow_requests.json`

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies.

## Deploy

This is a static single-file app. It deploys to Vercel automatically on every push to `main`.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Sergi-e/vibe-codes)

## License

MIT — see [LICENSE](LICENSE)
