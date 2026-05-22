# Mike Becker Portfolio Site

## To update the site

1. Open `content/site.txt` in any text editor.
2. Change the values you want to change.
3. Drop new video files into the matching `media/` folders if needed.
4. Save, zip the whole `mike-becker-site` folder, upload to Cloudflare.

That's it. Everything editable is in `content/site.txt`.

## Folder layout

```
mike-becker-site/
├── index.html
├── content/
│   └── site.txt            EDIT THIS FILE to change anything
├── media/
│   ├── reel/
│   │   ├── reel.mp4        Your hero reel
│   │   └── poster.jpg      First frame of the reel (for the intro)
│   ├── tile-1/             Drop tile 1 video here
│   ├── tile-2/             ...etc
│   └── tile-6/
└── resume.pdf
```

## Video size limits (Cloudflare free tier)

- Each video file under 25MB
- 1920x1080 max resolution
- H.264 MP4 recommended
