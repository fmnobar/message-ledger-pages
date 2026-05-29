---
title: Message Ledger Support
permalink: /support/
---

# Message Ledger Support

Message Ledger is a local-first Mac app. Most setup issues are related to the
selected Messages folder, local Contacts permission, or the local analytics
cache.

## First Launch

On first launch, choose the `Messages` folder on your Mac. Message Ledger checks
that the folder contains `chat.db`, then stores a local bookmark so future
refreshes can reuse the selected source.

If the app cannot find `chat.db`, confirm that Messages has local history on
this Mac and choose the Messages folder again.

## Contacts

Contacts access is optional. If disabled, Message Ledger remains usable with
identifiers and fallback labels. You can change Contacts permission in macOS
System Settings.

## Cache Reset

If the local analytics cache becomes unavailable or you want to rebuild imported
analytics, use the app's cache reset controls. Cache reset rebuilds imported
analytics from the selected Messages source and does not modify your Messages
database.

## Diagnostics

The app includes local diagnostics to help understand cache, source, permission,
and sync state. Review diagnostics before sharing them externally.

## Contact

For product support, use the App Store support link or the public support issue
tracker:

https://github.com/fmnobar/message-ledger-pages/issues
