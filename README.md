# Open Vending — Releases

Windows installers and auto-update files for Open Vending. No source code lives here.

## Before you start

You need two things from your Open Vending administrator:

1. **A setup code** — one long line of text. It connects the PC to the shared
   database. Treat it like a password: do not post or forward it.
2. **An app username and password.**

You do not need the vending portal logins: the app gets them for you after you log in.

Windows 10 or 11 (64-bit), about 1 GB of free disk space, and an internet connection.

## Install

1. Download `Open-Vending-Setup-x.y.z.exe` from the
   [latest release](https://github.com/liewcc/open-vending-releases/releases/latest).
2. Run it. If Windows shows **"Windows protected your PC"**, click
   **More info**, then **Run anyway** (the installer is not code-signed).
3. Choose **Only for me** (recommended — updates then install without admin prompts).
4. Keep the suggested folder unless you have a reason to change it. A very long
   folder path does not work.
5. Finish, with **Run Open Vending** ticked.

## First start

1. **Preparing Open Vending** — the app downloads the browser it uses to read the
   vending portal (about 200 MB). This happens once; keep the app open.
2. **Setup code** — paste the code and click **Connect**.
3. **Log in** with your app username and password.
4. The app downloads each profile's starting data (a bar at the bottom shows
   the progress), then runs its first scan of the portal. The first scan of
   each profile reads its sales history and can take several minutes. You can
   switch profiles while it runs.

**Refunds** (refund users only): open the Refunds page and click
**Connect Google**, then sign in with the Google account that can read the
refund requests sheet.

## Updates

The installed app checks this page for new versions and updates itself;
your data and logins are kept. Uninstalling (Settings → Apps) also keeps them,
in `%APPDATA%\open-vending`.
