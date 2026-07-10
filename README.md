# Pinterest Video Downloader

Download Pinterest videos at the highest available resolution with optional rotation.

## Features

- Paste any Pinterest video URL to preview and download
- Auto-upgrades to 1080p when available
- Rotate video before downloading (re-encodes with rotation baked in)
- Custom filename support

## Usage

Open `index.html` in any browser, paste a Pinterest video URL (e.g. `https://v1.pinimg.com/videos/mc/720p/...`), and click **Load** then **Download**.

## Notes

- Video rotation uses canvas + MediaRecorder to re-encode the video with rotation baked in
- Downloaded file format is WebM when rotated, MP4 when not rotated
- Falls back to opening the original URL if proxy is unavailable
