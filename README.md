# My Finances: home-screen app

## Files
- Upload these to GitHub: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`
- Do not upload your data file (`my_data_*.json`) or any backup. The code holds no personal numbers. Your data lives only on your phone.

## One-time setup (about 10 minutes, on your PC)
1. Create a free account at github.com.
2. Tap **+** → **New repository**, name it `finances`, choose **Public**, then **Create repository**.
3. Click **uploading an existing file**, drag in the 6 files listed above, then click **Commit changes**.
4. Go to **Settings** → **Pages**. Under Source choose **Deploy from a branch**, set Branch to `main` and folder to `/ (root)`, then **Save**. After 1-2 minutes the app is live at `https://YOUR-USERNAME.github.io/finances/`.

## On the iPhone
1. Send `my_data_nov16.json` to your phone (iCloud Drive, or email it to yourself and save it to Files).
2. Open the link in **Safari** → **Share** → **Add to Home Screen** → **Add**.
3. Open **Finances** from the home screen, not from Safari. Tap **Choose data file** and pick `my_data_nov16.json`.
   The app and Safari keep separate storage, so always load and use the data inside the home-screen app.

## How your data is stored
- Everything you do is saved instantly in the app's own storage on your iPhone. It works offline.
- It is not in iCloud and not synced to other devices. There is no bank connection; automatic payments are posted from your schedule each time you open the app.
- **Backup weekly:** More → **Save backup file** → Save to Files (iCloud Drive). Home reminds you after 7 days.
- **Restore:** More → **Restore or import a file** → choose the backup.
- Deleting the app from the home screen, or clearing Safari website data, erases the data. Restore from a backup if that happens.

## Updates
- App changes: replace `index.html` on GitHub (Add file → Upload files). The app updates the next time it opens online. Your data is kept.
- Changes to amounts, dates or limits: Claude sends a small update file. Import it in More, and your transactions are not touched.
