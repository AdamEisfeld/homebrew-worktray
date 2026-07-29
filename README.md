<div align="center">
  <img
    src="https://github.com/user-attachments/assets/c1eaba56-007a-4257-bf39-1f972d030dd5"
    width="92"
    alt="Worktray logo"
  />
  <h1>Worktray</h1>
  <p><strong>A private, local-first workbench for the files behind your ideas.</strong></p>
  <p>
    <a href="https://worktray.io">Open the web app</a>
    ·
    <a href="https://docs.worktray.io">Read the docs</a>
    ·
    <a href="https://github.com/AdamEisfeld/homebrew-worktray/releases/latest/download/Worktray.dmg">Download for Mac</a>
  </p>
</div>

<img
  src="https://github.com/user-attachments/assets/3b4bd68c-dcaa-4ea3-8022-9554dfd8ed2e"
  alt="Worktray — a private workbench for any file"
/>

## Why I built it

Worktray started with a small frustration: quick tasks often meant opening something much heavier than the task itself, or bouncing between focused web tools with ads, accounts, and uncertainty about where my data was going. I wanted one calm place to edit Markdown, inspect JSON, compose cURL, work with an SVG, or handle whatever small file was in front of me — without an account, ads, or a backend.

Once I found myself using the web app every day, the desktop version felt inevitable. I wanted the same simple workspace with native cURL requests and real files on disk, so a tray could live in Google Drive, iCloud Drive, Dropbox, git, or wherever I already keep my work. I chose [Tauri](https://tauri.app) to keep the desktop app as lightweight as possible, and the project snowballed from there.

## What you get

- Purpose-built editors for Markdown, JSON, YAML, XML, cURL, JWTs, code, images, SVGs, tasks, and more
- Browser-local storage with no account or backend
- Folder-backed trays and native cURL execution in the Mac app
- Files that remain ordinary files, ready for your existing sync or version-control tools

Your content stays local unless you explicitly send a request somewhere.

## Install on macOS

```sh
brew tap adameisfeld/worktray
brew trust adameisfeld/worktray
brew install worktray
```

Homebrew requires an explicit trust step for third-party taps before their casks can be loaded. If you prefer, you can also [download the latest signed and notarized DMG](https://github.com/AdamEisfeld/homebrew-worktray/releases/latest/download/Worktray.dmg) directly.

## About this repository

This public repository hosts Worktray's signed Mac releases and Homebrew Cask. The application source is private while the project is still being fleshed out; I may open-source it in the future.

> If Worktray earns a place in your toolkit, consider [starring this repository](https://github.com/AdamEisfeld/homebrew-worktray). It helps others find it and provides a small signal of public interest for a future submission to [Homebrew's official cask repository](https://docs.brew.sh/Acceptable-Casks).
