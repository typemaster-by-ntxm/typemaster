# Privacy Policy - TypeMaster 0.1.2 (Windows desktop app)

Publisher: ntxm.org (https://ntxm.org, contact@ntxm.org).

## In one paragraph

TypeMaster works offline. It has no accounts, no sign-in, no advertising and no analytics or tracking inside the
app. Your typing speed, accuracy and progress are saved on your own computer and are not uploaded. When your
computer is online the app makes two small, optional network requests, described below, so please read them.

## What the app does when you are online

| What | Where it goes | What it contains | If you are offline |
|------|---------------|------------------|--------------------|
| Launch counter | One request to `https://typemaster.ntxm.org/increment.php?app=desktop` each time the app starts | Nothing but the address itself (`app=desktop`). No typing, no progress, no name, no email, no device or user ID. Like any web request, the server can see your IP address and standard request headers | The request fails silently and the app carries on |
| Fonts | The interface style sheet asks `fonts.googleapis.com` (Google Fonts) for its fonts | A normal font request, which Google handles under its own policy | The app uses fonts installed on your PC |
| Links you click | Your default web browser opens the page (for example ntxm.org or a social profile) | Whatever your browser sends to that site | Not applicable |

This list comes from reading the source code of version 0.1.2. The app's program code has no network client of
its own; the two requests above come from its interface layer.

## What the app does NOT do

- It does not ask you to sign in or create an account.
- It does not collect your name, email address, location or any identifier.
- It does not upload your typing, statistics or progress.
- It does not show advertisements and does not include advertising networks.
- It does not check for updates. New versions are published on the GitHub releases page only.

## What is stored on your computer

| What | Where on Windows | Content |
|------|------------------|---------|
| Progress and settings | A file in `%APPDATA%\org.ntxm.typemaster` | Level, story and coding progress; theme; sound volumes; keyboard layout |
| Web view data | `%LOCALAPPDATA%\org.ntxm.typemaster` | The cache and storage of the built-in web view |

Nothing in these folders is sent to ntxm.org. You can look at them, copy them or delete them at any time.
Deleting the progress folder resets your progress.

## Children

The app does not collect information from anyone, including children under 13.

## Changes

If this policy changes, the new version will be published in this repository.

## Contact

ntxm.org - https://ntxm.org - contact@ntxm.org
