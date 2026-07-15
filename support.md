---
title: Messages Analytics Support
permalink: /support/
---

# Messages Analytics Support

Messages Analytics is a local-first Mac app. Most setup issues are related to the
selected Messages folder, local Contacts permission, or the local analytics
cache.

## First Launch

On first launch, choose the `Messages` folder on your Mac. Messages Analytics checks
that the folder contains `chat.db`, then stores a local bookmark so future
refreshes can reuse the selected source.

If the app cannot find `chat.db`, confirm that Messages has local history on
this Mac and choose the Messages folder again.

## App Review Sample Data

Apple App Review can use the synthetic sample package at
[Messages Analytics App Review Sample Data](https://fmnobar.github.io/message-ledger-pages/review/)
to review the app without access to a real Messages history. The package
contains a synthetic `Messages/chat.db`, an optional fictional Contacts vCard,
and setup instructions.

## Contacts

Contacts access is optional. If disabled, Messages Analytics remains usable with
identifiers and fallback labels. You can change Contacts permission in macOS
System Settings.

## Cache Reset

If the local analytics cache becomes unavailable or you want to rebuild imported
analytics, choose Help > Troubleshooting, expand Advanced, and select Reset
Analytics Cache. The reset leaves your Messages database unchanged and preserves
hidden contacts, merge choices, iCloud sync settings, App Lock, and other
preferences. Use Messages > Refresh from Messages afterward to rebuild the
local analytics cache.

## Troubleshooting

Help > Troubleshooting shows actionable problems or `No problems detected`
without loading technical details during normal use. Choose Copy Support
Information or expand Advanced > Technical Details when support information is
needed. Both paths redact user-specific filesystem components and exclude
message bodies, chat titles, contact identifiers, hidden-contact names, and
analytics exports. Review support information before sharing it externally.

## Contact

For product support, use the App Store support link or the public support issue
tracker:

https://github.com/fmnobar/message-ledger-pages/issues
