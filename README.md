<div align="center">

<img src="https://github.com/user-attachments/assets/914fe974-889c-4cd9-b553-9cc7ae3278a1" alt="Anitsuki" width="110">

# Anitsuki

**Same skies, different worlds.**

A cinematic desktop anime client for Windows, built for late-night viewing.<br>
Install it, open it, press play. No extensions, no DNS changes, no setup.

[Download](../../releases/latest) &nbsp;•&nbsp; [Website](https://anitsuki.pages.dev/) &nbsp;•&nbsp; [Telegram](https://t.me/AnitsukiOfficial)

</div>

<br>

## Overview

Anitsuki is a free desktop application that turns watching anime into a calm, uninterrupted experience. It opens straight into a dark, cinematic interface, remembers where you stopped, and keeps itself up to date in the background.

There is nothing to configure on first launch. Pick a title and watch it.

## Features

| | |
|---|---|
| **Watching** | Continue Watching row and Up Next queue. Sub or dub. A default server and language you set once. Automatic fallback across servers when one fails. A mini player that keeps your episode running while you browse. |
| **Discovery** | A rotating featured banner on Home. Search with filters, shortcuts for Airing Now, This Season, Movies and Top Rated, and genre browsing. A weekly Release Calendar with countdowns that highlights titles from your own list. |
| **Anime pages** | Overview, episode list, characters, relations and related titles in one place. |
| **Library** | Organise by Watching, Completed, Planning, Paused, Dropped and Rewatching. Search, sort and filter. Track progress, rate titles and count rewatches. Correct a wrong match yourself with the Match button. |
| **Accounts** | Sign in to track your list, or use Guest mode and skip it entirely. |
| **Updates** | Silent background updates, with a small notice when a new version is ready. |
| **Control** | 18+ titles are hidden by default and appear only if you turn them on in Settings. A built-in Help section with setup steps and a FAQ. |

## Requirements

| | |
|---|---|
| **Operating system** | Windows 10 or Windows 11 |
| **Network** | Internet connection |
| **Account** | None required |

## Installation

1. Open the [latest release](../../releases/latest) and download the installer (`.exe`).
2. Run the installer.
3. If Windows SmartScreen shows a warning, select **More info**, then **Run anyway**.

Anitsuki is a new application that is not yet widely downloaded, which is why SmartScreen may flag it. After the first install, updates are delivered automatically.

### Verify your download

Each release lists the SHA-256 checksum of its installer. To check your copy, run this in PowerShell from the folder containing the file:

```powershell
Get-FileHash .\Anitsuki-Setup-<version>.exe -Algorithm SHA256
```

The result should match the value on the release page.

## FAQ

<details>
<summary><b>An episode will not play.</b></summary>
<br>
Switch servers from the player. If none of them has the episode, it is not available on any server right now. Try again later.
</details>

<details>
<summary><b>Do I need an account?</b></summary>
<br>
No. Guest mode covers browsing and watching. Sign in only if you want to track your list.
</details>

<details>
<summary><b>How do updates work?</b></summary>
<br>
Anitsuki checks for new versions and installs them quietly in the background. A small notice tells you when an update is ready.
</details>

<details>
<summary><b>Is the source code available?</b></summary>
<br>
This repository contains release builds only.
</details>

## Updates and support

- **Release news and patch notes:** [Telegram channel](https://t.me/AnitsukiOfficial)
- **Bug reports and suggestions:** message on Telegram and include your Windows version, the Anitsuki version, and what you were doing when the problem occurred.

Release notes are published with every release on the [Releases](../../releases) page.

## Disclaimer

Anitsuki is an independent desktop client. It does not host or store any video content and is not affiliated with any anime studio or service.

<br>

<div align="center">
<sub>Built and maintained by an independent developer.</sub>
</div>
