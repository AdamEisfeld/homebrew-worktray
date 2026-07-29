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

> If Worktray is useful to you, consider [starring the repository](https://github.com/AdamEisfeld/homebrew-worktray). It helps show public interest and supports a future submission to [Homebrew's official cask repository](https://docs.brew.sh/Acceptable-Casks).

## The short version

Not every job needs a full IDE, a design suite, or a different web tool. Worktray covers the middle: edit Markdown, inspect JSON, compose a cURL request, tweak an SVG. It runs locally, without accounts, ads, or a backend.

The Mac app adds real files, folder-backed trays that work with existing sync tools, and native cURL execution. It uses [Tauri](https://tauri.app) to keep the desktop footprint small.

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
