# YouTube ReVanced Setup Guide (Pixel 6)

Oct 14, 2026 · @Crud

Setup takes about 15 minutes and does not need root. Download only from revanced.app, the official ReVanced GitHub, and APKMirror. Avoid look-alike sites such as "revanced.net" or Vanced mirror sites.

## Step 1: Clean up old apps

1. Go to **Settings → Apps → See all apps → YouTube** and tap **Disable**. On a Pixel, YouTube is a system app, so it can't be fully uninstalled; disabling it is enough.
2. Uninstall any old **Vanced, ReVanced, RVX, or Vanced MicroG** apps.
3. Leave **Google Play Services** alone.

## Step 2: Install ReVanced Manager

1. On your phone, open [revanced.app/download](https://revanced.app/download) and download **ReVanced Manager**.
2. Open the downloaded file and tap **Install**.
3. If Android blocks it, tap **Settings → Allow from this source**, go back, and tap **Install** again.

## Step 3: Install GmsCore

GmsCore is needed for Google sign-in.

1. Open ReVanced Manager. If it asks you to install **GmsCore**, accept. Otherwise, download it from the official ReVanced GmsCore GitHub releases page.
2. After it installs, go to **Settings → Apps → GmsCore → App battery usage** and set it to **Unrestricted**. This prevents sign-in and notification problems.

## Step 4: Get the correct YouTube APK

1. In ReVanced Manager, select **YouTube** and note the **suggested version**. Patching any other version often fails or produces an app that won't play videos.
2. If the Manager offers to download that version for you, use that option. If not, search APKMirror for **YouTube \[that exact version\]** and download it.
3. On APKMirror, choose the version marked **APK**, not **BUNDLE**. ReVanced can only patch the plain APK. For a Pixel 6, choose **arm64-v8a** or **universal**.
4. **Don't install the APK.** Just leave it in Downloads.

## Step 5: Patch and install

1. In ReVanced Manager, go to **YouTube** and choose the APK you just downloaded from storage.
2. Keep the **default patch selection**. The defaults are tested to work together.
3. Tap **Patch**. Keep the Manager open and the screen on until it finishes, which takes a few minutes.
4. Tap **Install**.

## Step 6: Sign in

1. Open **YouTube ReVanced** and sign in with your Google account.
2. If sign-in fails, restart the phone, open GmsCore once, then try again.
3. Optional: go to **Settings → Apps → YouTube ReVanced → Open by default** and turn on **Open supported links** so YouTube links open in ReVanced.

## Step 7: Customize

Open **YouTube ReVanced → Settings → ReVanced**. You now have:

- No ads
- Background playback, including with the screen off
- SponsorBlock, which skips sponsored segments
- Picture-in-picture
- Return YouTube Dislike
- Your subscriptions and watch history

## Sources

- [Notebookcheck: ReVanced guide](https://www.notebookcheck.net/While-Google-continues-to-crack-down-on-ad-blockers-here-s-the-best-way-to-keep-blocking-YouTube-ads-on-Android.836457.0.html)
- [ReVanced Download 2026 guide](https://www.codegenes.net/blog/revanced-download/)
