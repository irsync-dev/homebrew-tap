# irsync Homebrew tap

Homebrew formula for [irsync](https://irsync.org), a file sync tool, and
its companion `fileset`. Works on macOS (Apple Silicon) and Linux (x86_64
and arm64).

## Install

```sh
brew install irsync-dev/tap/irsync
```

This installs both `irsync` and `fileset`. To update:

```sh
brew upgrade irsync
```

## About this repo

`Formula/irsync.rb` is written by the release workflow in
[irsync-dev/irsync](https://github.com/irsync-dev/irsync) for every stable
release. Don't edit it by hand: the next release overwrites it. Pre-releases
(alpha, beta) are not published here.

Report problems with irsync or the formula at
[irsync-dev/irsync issues](https://github.com/irsync-dev/irsync/issues).
