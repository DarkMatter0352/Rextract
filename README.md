<div align="center">

<img src="assets/rextract-logo.png" alt="Rextract dinosaur logo" width="136" />

# Rextract

### Your media. Your transcripts. One place.

**A Windows media downloader and local AI transcription desktop app.**  
By **speakerfreak & darkmatter**

[**Download Rextract for Windows**](https://github.com/DarkMatter0352/Rextract/releases/latest) · [Latest release](https://github.com/DarkMatter0352/Rextract/releases/latest) · [Licenses & credits](LICENSING.md)

</div>

---

## Meet Rextract

Rextract brings **downloads**, **transcription** and a **media library** together in one dark-themed desktop application. It integrates the native [Vibe](https://github.com/thewh1teagle/vibe) transcription experience, so you don't need to install a separate copy of Vibe.

| Download | Transcribe | Library | Settings |
| --- | --- | --- | --- |
| Paste one link or several and download supported media. | Transcribe audio or video locally with Vibe's engine. | Find and open your downloaded files. | Check for signed Rextract updates, read licenses, or uninstall. |

### Features

- **Save media** from supported YouTube, Instagram, X/Twitter and Bluesky links. Site support can change when the services change.
- **Choose your format:** videos, audio-only downloads, photo formats and quality options as applicable.
- **Download progress you can see:** status, progress indicator, Stop, and a live activity log.
- **Built-in transcription:** use Vibe's native transcription workflow, history, playback, and export features.
- **One media folder:** downloads are saved under your **Documents / Rextract** folder by default.
- **Signed in-app updates:** check and install newer published Rextract releases from **Settings → Rextract Updates**.
- **Uninstall choices:** remove only the app, or request a full cleanup of Rextract/Vibe-related data. **Full uninstall is destructive.**

> **Early-access Windows build:** Rextract is being actively developed. Test with nonessential files first, keep backups of important transcripts, and report unexpected behavior to the project maintainers.

## Download and install

**[⬇ Download the latest official Rextract release](https://github.com/DarkMatter0352/Rextract/releases/latest)**

1. Open the link above. You do **not** need a GitHub account.
2. Expand **Assets** if necessary.
3. Download the Windows installer named **`Rextract_*_x64-setup.exe`**. This is the app installer, not the `.sig` or `latest.json` files.
4. Run the installer, then open **Rextract** from Windows.

### Chrome Companion (v0.2.16 and newer)

The optional Chrome Companion adds one-click download arrows to supported **YouTube, Instagram, X/Twitter and Bluesky** posts. It communicates only with the Rextract helper installed on your own Windows computer.

1. On the **same release page** as the Windows installer, download **`Rextract-Chrome-Companion.zip`**.
2. Extract the ZIP into a **permanent folder** (don't load the ZIP itself).
3. In Chrome, open `chrome://extensions`, turn on **Developer mode**, click **Load unpacked**, and select the extracted folder containing `manifest.json`.
4. Open Rextract → **Settings → Chrome Companion → Repair Chrome connection**; reload the extension if asked.
5. Refresh the site. Use the small download arrow beside the site's post controls; the ring reflects download activity.

This Chrome Companion is **not listed on the Chrome Web Store**. You install it using Chrome's Load unpacked option. It can stop working if social sites change their page layouts; if an arrow is missing, the extension popup's **Download current post** can be used on a supported media permalink.

### Background operation and full quit (v0.2.16+)

Chrome downloads can run quietly using Rextract's background tray process. You can **Quit Rextract completely** from Settings or its Windows tray menu to free resources. In Settings, **Quit when closing its window (X)** changes X from hide-to-tray to a full exit. The next Chrome download may start Rextract again as needed. Quitting while downloading interrupts active work.

**System:** Windows x64. An internet connection is needed for downloads and for obtaining any transcription models that aren't already on your computer. Rextract includes the native Vibe application experience; a separate standalone Vibe installation is **not required**.

**A note about Windows SmartScreen:** Rextract's in-app updater uses a cryptographic signature, but the downloadable installer does **not yet** have a Windows-trusted publisher/code-signing certificate. Windows may show an **Unknown publisher** warning. Only run installers you obtained from this official repository and personally trust; never disable SmartScreen globally.

## How to use it

**Download:** Open **Download**, paste one or more supported URLs, choose your download options, and click **Download**. Watch the progress indicator; use **Stop** if needed, or **Open folder** to see your files.

**Transcribe:** Open **Transcribe**, add a supported audio or video file, and use the native Vibe transcription interface. You can also use **Transcribe last download** after downloading a media file.

**Library:** Open the **Library** tab to access saved media.

**Update:** Open **Settings → Rextract Updates → Check now**. If an update is available, select **Update and restart**. This updates **Rextract as a whole**, including its embedded Vibe integration when we ship a newer integrated engine. It does **not** independently install new upstream Vibe versions.

## The app

Rextract uses a dark navy and blue interface with four tabs: **Download · Transcribe · Library · Settings**.

*Actual app screenshots will be added here once any personal file paths and private account details have been removed.*

## Frequently asked questions

<details><summary><b>Do I have to install Vibe separately?</b></summary>

No. Rextract integrates the native Vibe transcription experience. Models may need to be downloaded separately on first use.

</details>

<details><summary><b>Do I need Python, Node.js, PowerShell or GitHub?</b></summary>

No. Those are developer/build tools. Regular Windows users install the downloaded `.exe` and use the app.

</details>

<details><summary><b>How do I get newer versions?</b></summary>

Use **Settings → Rextract Updates → Check now**. The built-in updater verifies officially signed Rextract update packages. You can also visit the [Releases page](https://github.com/DarkMatter0352/Rextract/releases/latest) for manual downloads.

</details>

<details><summary><b>Will upgrading delete my downloads or transcripts?</b></summary>

Normal in-place updates are intended to keep app data and media. Back up anything important before testing a new release. Avoid **Full uninstall** unless you deliberately want data removed.

</details>

<details><summary><b>Why does Windows say “Unknown publisher”?</b></summary>

Windows code signing is a separate system from the secure in-app update signatures. Windows-trusted publisher signing has not yet been configured for Rextract, so SmartScreen may warn on installation.

</details>

## Licenses, source and credits

**Rextract** is by **speakerfreak & darkmatter**. The original Rextract branding and private project contributions are rights-reserved; the source repository is not made public by this installer distribution.

Rextract includes and credits **[Vibe](https://github.com/thewh1teagle/vibe)** by thewh1teagle, which remains available under the **MIT License**, including its permissions for commercial use, modification, and redistribution. Other included third-party components may use other licenses.

Read [Licensing & Credits](LICENSING.md) and [Vibe's MIT notice](VIBE-MIT.txt).

---

<div align="center">

**Get Rextract:** [Latest Windows installer](https://github.com/DarkMatter0352/Rextract/releases/latest)  
**Updates:** Delivered through signed Rextract releases · **Source:** Kept private

*Rextract · speakerfreak & darkmatter · Vibe MIT*

</div>
