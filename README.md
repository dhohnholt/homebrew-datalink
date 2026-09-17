# dhohnholt/homebrew-datalink

Homebrew tap for [DataLink
Scanner](https://github.com/dhohnholt/datalink_Mac_OS_interface) — a macOS
interface for the Apperson DataLink 1200 optical mark scanner.

```bash
brew install dhohnholt/datalink/datalink-scanner
datalink-scanner install-app     # adds it to /Applications, Dock and Spotlight
```

Update later with:

```bash
brew upgrade datalink-scanner
```

The app is a thin launcher around the `datalink-scanner` command, so upgrading
the formula upgrades the app — nothing to re-download or re-approve.

This tap is generated from `packaging/homebrew/datalink-scanner.rb` in the main
repository; edit it there.
