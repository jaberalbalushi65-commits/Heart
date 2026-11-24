# Sanctuary: install on your iPhone

## 1. Put it online privately (about 3 minutes)
1. Unzip this folder on a computer.
2. Go to https://app.netlify.com/drop (free account) and drag the whole "sanctuary-pwa" folder onto the page.
3. Netlify gives you a web address like https://random-name.netlify.app. In Site settings you can rename it to something only you know.
Cloudflare Pages and GitHub Pages also work. Only the app code is online. Your hearts, journal and photos never leave your device.

## 2. Add it to your iPhone
1. Open the address in **Safari** (not inside another app).
2. Tap Share, then **Add to Home Screen**, then Add.
3. Open Sanctuary from its icon. After the first load it works offline.

## 3. Moving your existing data
Safari and the home-screen app keep **separate storage**. Data you entered on another link will not appear automatically.
- On the old link: Menu (hamburger button), unlock the Vault, press Export, copy the text somewhere safe (Notes, a message to yourself).
- In the installed app: unlock the Vault with any new PIN, paste the text, press Restore, and enter the PIN used for the backup.

## 4. Updating later
1. Replace the files on Netlify (drag the new folder onto Deploys).
2. In sw.js change `sanctuary-v1` to `sanctuary-v2` (then v3, and so on). Without this, phones keep the old version.
3. Open the app twice while online. The second open shows the update.

## 5. Keep backups
Browser storage can be cleared by iOS if the phone is low on space or the app is deleted. Export an encrypted backup regularly and keep it somewhere safe.

## Limits
- Face ID and fingerprint unlock are not possible in a web app. The Vault uses a PIN with real encryption. A forgotten PIN cannot be recovered.
- The elegant font loads from Google Fonts. Offline it falls back to Georgia.
