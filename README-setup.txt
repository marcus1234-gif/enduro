# Enduro Program — Offline iPhone App Setup

This folder is your complete app. Follow the steps once and you'll have a
real, fullscreen app icon on your iPhone that opens with no signal.

You do NOT need to know any coding. Everything is done by clicking in a
web browser.

---

## What each file is (you don't need to touch any of them)

- index.html ........ the app itself
- manifest.json ..... tells iPhone the app's name and icon
- service-worker.js . copies the app onto your phone so it works offline
- icon-180/192/512 .. the app icon at different sizes

---

## STEP 1 — Make a free GitHub account

1. Go to https://github.com and click "Sign up".
2. Create an account (free). Verify your email.

GitHub is just a free place to park these files at a real web address.
That web address is the only thing your iPhone needs to install the app.

---

## STEP 2 — Create a place to put the files (a "repository")

1. Once logged in, click the "+" in the top-right corner, then
   "New repository".
2. Repository name: type  enduro  (or any name you like).
3. Make sure it is set to "Public".
4. Click "Create repository".

A "repository" (repo) is just a folder that lives on GitHub.

---

## STEP 3 — Upload these files

1. On your new repo's page, click the link
   "uploading an existing file" (or the "Add file" button, then
   "Upload files").
2. Drag ALL the files from THIS folder into the upload box:
   index.html, manifest.json, service-worker.js, and the three icon PNGs.
   (Drag the files themselves, not the folder.)
3. Scroll down and click the green "Commit changes" button.

---

## STEP 4 — Turn on GitHub Pages (the free website feature)

1. In your repo, click "Settings" (top menu).
2. In the left sidebar, click "Pages".
3. Under "Branch", choose "main" and the folder "/ (root)", then "Save".
4. Wait about 1 minute. The page will show a green box with your web
   address. It looks like:

   https://YOUR-USERNAME.github.io/enduro/

   (If it still says "building", refresh the page after a minute.)

That web address is your app's permanent home. Leave the repo alone after
this — don't delete it — and the address keeps working forever.

---

## STEP 5 — Install it on your iPhone

1. Open that https://...github.io/enduro/ address in SAFARI on your
   iPhone (it must be Safari, not Chrome, and not the GitHub app).
2. Let it finish loading once (this is when it copies itself onto your
   phone for offline use).
3. Tap the Share button (the square with the up-arrow).
4. Scroll down and tap "Add to Home Screen".
5. Name it and tap "Add".

Done. You now have an app icon. Tap it and it opens fullscreen.

---

## Does it work with no signal?

Yes. After you've opened it in Safari once (Step 5), the app lives on your
phone. Tapping the home-screen icon runs that local copy — GitHub is not
contacted again. Open it on the trail with zero bars and it works,
including all your saved checkboxes.

---

## Good to know

- Your checkbox progress is saved on THIS phone, in this app. It is not
  synced to iCloud. Clearing Safari data or switching phones resets it.
- Keep the GitHub repo (don't delete it). It's the app's home address.
- If I ever send you an updated app, you'd re-upload index.html in Step 3
  and bump the version. Not needed unless you want changes.
