<div align="center">

<img src="assets/icon-256.png" width="96" alt="Boundless icon" />

# Boundless

**Your reading, on your terms.**

A reader for manga, manhwa, webtoons, and novels that hosts nothing of its own.
It runs entirely on your device, and it never requires an account.

[![Latest release](https://img.shields.io/github/v/release/realwuji/boundless-public?label=release&color=6C5CE7)](https://github.com/realwuji/boundless-public/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/realwuji/boundless-public/total?label=downloads&color=00B4D8)](https://github.com/realwuji/boundless-public/releases)
[![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-6C5CE7)](#download)
[![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)](#download)

<a href="https://github.com/realwuji/boundless-public/releases/latest/download/boundless-android.apk">
<img src="https://img.shields.io/badge/Download-Android%20APK-6C5CE7?style=for-the-badge&logo=android&logoColor=white" alt="Download for Android" height="50" />
</a>
&nbsp;
<a href="https://apps.apple.com/app/id6804857456">
<img src="https://img.shields.io/badge/Download-App%20Store-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Download on the App Store" height="50" />
</a>

Always the latest build. No sign-up, no Play Store account, no tracking.

</div>

<br>

<div align="center">
<img src="assets/demo.gif" width="300" alt="Boundless reading demo" />
</div>

<br>

## Why Boundless

Most readers ask you to trust a server somewhere, or a company's app store review process, with a library you built yourself. Boundless doesn't. Everything, your files, your progress, your settings, stays on your device unless you explicitly choose to sync it. There's nothing to sign up for to start reading, and nothing phoning home in the background.

<table>
<tr>
<td width="33%" valign="top">

### 📖 Read anything
CBZ, CBR, ZIP, PDF, EPUB, and TXT out of the box. Connect a self-hosted Komga library, or add sources through the extension system.

</td>
<td width="33%" valign="top">

### 🎨 Tuned to you
Reading mode, page scaling, border cropping (with an automatic per-page mode), color filters, tap zones, fonts, margins. Every option, for comics and novels separately.

</td>
<td width="33%" valign="top">

### 🔌 Works offline
A real reading cache keeps chapters you've opened available with no connection, with a size limit you control. Downloads keep chapters forever until you delete them.

</td>
</tr>
<tr>
<td width="33%" valign="top">

### 🔄 Sync when you want it
An optional free account keeps your library, progress, and categories in sync across devices. Skip it entirely and everything still works, offline-first by design.

</td>
<td width="33%" valign="top">

### 📊 Tracker integration
Link AniList, Kitsu, MyAnimeList, MangaUpdates, Shikimori, or Bangumi, and your progress pushes automatically as you read.

</td>
<td width="33%" valign="top">

### 🔒 Built for every reader
Content rating controls, parental controls with reading-hour limits, and an app lock with PIN or biometrics.

</td>
</tr>
</table>

## Screenshots

<table>
<tr>
<td align="center" width="25%"><img src="assets/screenshots/android-library.png" width="100%" alt="Library" /><br><sub><b>Library</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/android-detail.png" width="100%" alt="Title detail" /><br><sub><b>Title detail</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/android-reader.png" width="100%" alt="Reader" /><br><sub><b>Distraction-free reader</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/android-reading-settings.png" width="100%" alt="Reading settings" /><br><sub><b>Deep customization</b></sub></td>
</tr>
</table>

<details>
<summary><b>More screenshots</b> (sources, and the iOS build)</summary>
<br>

<table>
<tr>
<td align="center" width="25%"><img src="assets/screenshots/android-sources.png" width="100%" alt="Sources" /><br><sub><b>Android: sources</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/ios-detail.png" width="100%" alt="iOS detail" /><br><sub><b>iOS: title detail</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/ios-reader.png" width="100%" alt="iOS reader" /><br><sub><b>iOS: reader</b></sub></td>
<td align="center" width="25%"><img src="assets/screenshots/ios-settings.png" width="100%" alt="iOS settings" /><br><sub><b>iOS: settings</b></sub></td>
</tr>
</table>

</details>

## How it works

```mermaid
flowchart LR
    A["Your own files<br/>(CBZ · CBR · ZIP · PDF · EPUB · TXT)"] --> D(("Boundless"))
    B["A self-hosted library<br/>(Komga)"] --> D
    C["Sources<br/>(the extension system)"] --> D
    D --> E["One reader.<br/>One library.<br/>Fully customized."]
```

Nothing is bundled or hosted by the app itself. You point Boundless at content you already have the rights to, and it takes care of organizing, caching, and presenting it consistently.

## Download

**Android.** Download the APK above, or grab it directly from the [latest release](https://github.com/realwuji/boundless-public/releases/latest). Requires Android 7.0 or newer. It's release-signed and distributed outside the Play Store, so Android will ask for a one-time permission to install from your browser or file manager the first time, the same prompt any app outside the Play Store shows.

Updating works the same way: install the newer APK over the existing one. Since every release is signed with the same key, your library, settings, and reading progress stay exactly where you left them.

**iOS.** Available on the [App Store](https://apps.apple.com/app/id6804857456).

## Getting started

New to Boundless? The [getting started guide](docs/getting-started.md) walks through adding your first titles, the reader, offline reading, sync, and the settings most worth knowing about.

## Links

- Website: [boundless.moe](https://boundless.moe)
- Privacy policy: [boundless.moe/privacy](https://boundless.moe/privacy)
- Terms: [boundless.moe/terms](https://boundless.moe/terms)
- Release notes: [CHANGELOG.md](CHANGELOG.md)

---

<sub>This repository holds public documentation and Android release builds only. The app's source code is not published here. The "Source code" archives GitHub attaches to each release below are an automatic snapshot of this documentation repository, not the app.</sub>
