# CARMEN / OPERA

**An Instrument for Poetic Composition**  
Version **2.7.0** · Created by **Majyutsudo**

CARMEN / OPERA is a browser-based writing studio for poetry and lyrics, featuring a writing editor, Rhyme Book, Focus Mode, preview, collections, dictionaries and Word Oracle. Five color themes include **Passion**.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the **contents of this folder** to its root.
2. In repository **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save.
3. Open the HTTPS GitHub Pages URL after deployment. Compatible browsers can offer **Install app** or **Add to Home Screen**.

The `index.html` also works as a standalone local HTML file. Service workers require HTTPS (or localhost) and do not work from `file://`.

## Data and offline use

- Works without an account; writing data and personal dictionaries are stored locally in the browser (localStorage / IndexedDB).
- After the first successful online visit and service-worker installation, the app shell can load offline. **Offline access is not guaranteed** if browser storage is cleared, caching fails, or the browser evicts stored files.
- Your writing is **not uploaded to GitHub** by the app. Browser profiles, devices and origins have separate storage.
- Use the application's export / backup tools regularly. **Moving from a `file://` version to the GitHub Pages URL does not migrate existing local data automatically**: export from the old copy, then import in the hosted copy.
- Updating the app shell does not intentionally clear user data, but browser storage is not a substitute for a backup.

## License

Free to use, including commercial writing. Personal code modifications are permitted; redistribution and sale of the app or modified versions require permission. **This is not an open-source license.** See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

© 2026 Majyutsudo.
