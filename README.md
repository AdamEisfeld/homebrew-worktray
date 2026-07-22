# homebrew-worktray

Homebrew tap and release host for [Worktray](https://worktray.io).

```
brew tap adameisfeld/worktray
brew trust adameisfeld/worktray
brew install worktray
```

Recent Homebrew versions require explicitly trusting a new third-party tap before its casks will load — without the `brew trust` step, `brew install adameisfeld/worktray/worktray` fails with "Refusing to load cask ... from untrusted tap."

Releases (signed, notarized `.dmg`) and the Cask definition in `Casks/worktray.rb` are published automatically by CI in the (private) source repo. This repo intentionally contains no application source code.
