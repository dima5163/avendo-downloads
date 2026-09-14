# Avendo — direct downloads

**Avendo is a lightweight business assistant for freelancers and small service
businesses.** Clients, jobs, payments, tasks, reminders and bookings in one
place, without the complexity of a traditional CRM.

The free plan works fully offline, stores your data locally on your device, and
**does not require an account**.

- Website: <https://avendo-app.com/en/>
- All download options: <https://avendo-app.com/en/download/>

This repository hosts the **public release binaries** for direct download. The
application source code is not published here; builds are produced from a
private repository and attached to GitHub Releases so that the website can serve
them anonymously.

## Download

Current release: **[`avendo-1.0.17-direct`](https://github.com/dima5163/avendo-downloads/releases/latest)**

| Platform | Artifacts |
|---|---|
| **Windows** | `.msi` and `-setup.exe`, x64 and ARM64 |
| **Linux** | `.deb` and `.AppImage`, amd64 and arm64 |
| **macOS** | universal `.dmg` |
| **Android** | `.apk` |

Also available from the app stores:

- **iOS** — [App Store](https://apps.apple.com/us/app/avendo/id6780777012)
- **macOS** — [Mac App Store](https://apps.apple.com/us/app/avendo-desktop/id6782857894?mt=12)
- **Android** — [Google Play](https://play.google.com/store/apps/details?id=com.avendoapp.mobile)
- **Web** — <https://app.avendo-app.com>

## Installing

**Windows** — run the `.msi` or `-setup.exe` for your architecture. A
[winget package](https://github.com/microsoft/winget-pkgs/pull/432666)
(`AvendoApp.Avendo`) is currently in review; once merged, `winget install
AvendoApp.Avendo` will work.

**Linux (Debian/Ubuntu)**

```sh
sudo dpkg -i Avendo-1.0.17-linux-amd64-*.deb
```

**Linux (AppImage)**

```sh
chmod +x Avendo-1.0.17-linux-amd64-*.AppImage
./Avendo-1.0.17-linux-amd64-*.AppImage
```

**macOS** — open the `.dmg` and drag Avendo to Applications.

**Android** — installing the `.apk` directly requires enabling installation from
unknown sources. Most people should use Google Play instead.

## Verifying a download

Each release lists the exact file sizes published by GitHub. Filenames embed the
build hash (for example `233a6366`) so a given binary is reproducible from its
name and tag.

## Plans

| Plan | Price | Includes |
|---|---|---|
| **Free** | $0 | Clients, jobs, tasks, reminders. Offline, local storage, no account required, one device. |
| **Pro** | $4.99/mo | Adds cloud sync, web access, team collaboration, booking page. |
| **Max** | $9.99/mo | Adds AI summaries, insights, automations, AI copywriting, chat with your data. |

## Issues

This repository carries release binaries only. For product questions or problems
with the application itself, please use the contact routes on
<https://avendo-app.com/en/>.
