# Zrow Browser

A native macOS browser built on SwiftUI and WebKit (WKWebView), not Chromium.
It keeps the Arc-class shell, Spaces, link routing, and Chrome extensions, while
staying light on memory and battery because it shares the engine the system
already runs.

This repository hosts the public release artifacts (the `.dmg` and update feed).

## Download

Grab the latest macOS disk image from the
[**Releases**](https://github.com/zrowdev/browser-releases/releases) page.

- Requires **macOS 14** or later (Apple Silicon and Intel).
- Updates install automatically in the background via Sparkle.

## Features

- **Native WebKit.** Built on SwiftUI and WKWebView, the same engine as Safari.
  No Chromium, no Electron, less memory and battery than a Chromium shell.
- **Spaces.** Themed Spaces, each with its own tint and set of tabs, so
  switching context is a glance instead of a hunt.
- **Folders.** Group tabs into expandable folders in the sidebar tree, nest them,
  and drag tabs in to file them away.
- **Air Traffic Control.** Rules that automatically route opened links into the
  right Space, so a work link never lands in your personal Space.
- **Chrome extensions.** Real Manifest V3 support through WKWebExtension. Not full
  Chrome parity yet, but the extensions people depend on most already work,
  including 1Password and NordPass.
- **Split view.** Two pages side by side inside a single tab.
- **Command bar.** One keystroke to jump to any tab, Space, or URL.
- **Content blocking.** A built-in ad and tracker blocker powered by Brave's
  blocking engine, on by default.
- **Sidebar.** Essentials, pinned tabs, and a live tab tree in one quiet column
  you can collapse.
- **Tab suspension.** Idle tabs sleep to free memory and wake instantly when you
  return to them.
- **Profiles.** Separate cookies, logins, and history per profile.
- **Glance overlay.** Peek at a link in a floating overlay without leaving the
  page you are on.
- **Tab search.** Find any open tab by title or URL across every Space.
- **Automatic updates.** Sparkle keeps the browser current without a manual
  download trip.

Built to respect macOS system settings end to end: Reduce Motion, Reduce
Transparency, Increase Contrast, and Bold Text all have explicit paths.

## Report an issue

Found a bug or have a request? Open an issue:
[github.com/zrowdev/browser-releases/issues/new](https://github.com/zrowdev/browser-releases/issues/new).
