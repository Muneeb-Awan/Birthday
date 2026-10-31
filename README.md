# 🎂 Birthday Wish Page

An interactive birthday surprise: Yes/No intro → pop balloons → blow the candle → rose bouquet → swipeable photos → letter in an envelope → gift with confetti. Works on phones and computers.

## ✏️ Customize
Open `index.html` and edit the `CONFIG` block at the top:
- `name`, `letterGreeting`, `balloonWords`, `letter`, `letterSignoff`, `finalTitle`, `finalMessage`
- `photos` — list of `{ src, caption }`
- `music` — optional, e.g. `"music.mp3"` (put the file next to index.html)
- `bouquetImage` — optional picture to replace the drawn bouquet

## 📸 Replace pictures
Put your photos in the `photos/` folder. Easiest: name them `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg` to overwrite the placeholders.
Using different names or more photos? Just update the `photos` list in `CONFIG`.
Tip: portrait photos (3:4) look best. File names are case-sensitive on GitHub (`Photo.JPG` ≠ `photo.jpg`).

## 🚀 Put it online with GitHub Pages (free)
1. Create a new **public** repository on github.com.
2. Click **Add file → Upload files** and drag in `index.html`, `README.md`, and the `photos` folder (plus `music.mp3` if used). Commit.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, Save.
4. After a minute your link appears there: `https://<your-username>.github.io/<repo-name>/`

Netlify Drop (app.netlify.com/drop) also works — just drag the whole folder in.
