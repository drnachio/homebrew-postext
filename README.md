# Homebrew tap for Postext

The [postext](https://postext.dev/docs/command-line) command line for macOS (Apple silicon and Intel) and Linux (x86-64 and ARM64): PDF, HTML, EPUB, page images and Word files from a `.postext` book or loose Markdown, in one self-contained executable.

```bash
brew install drnachio/postext/postext
```

`brew upgrade postext` follows the releases. The formula installs the executable that every [release](https://github.com/drnachio/postext/releases/latest) of Postext publishes, checked against its SHA256.

`Formula/postext.rb` is written by the release workflow of [drnachio/postext](https://github.com/drnachio/postext) (`.github/scripts/package-managers.mjs`): change it there, not here. Issues go to [drnachio/postext](https://github.com/drnachio/postext/issues).
