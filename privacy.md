---
title: Messages Analytics Privacy Policy
permalink: /privacy/
---

# Messages Analytics Privacy Policy

Effective date: July 14, 2026

Messages Analytics is a local-first macOS app. It helps you analyze aggregate
patterns in your own Messages history while keeping the source data under your
control.

## Messages Source Access

Messages Analytics asks you to choose your local Messages folder. The app stores a
local security-scoped bookmark so it can refresh the local analytics cache after
you approve access.

Messages Analytics opens the Messages `chat.db` database in read-only mode. It does
not write to or modify your Messages database.

## Local Analytics Cache

Messages Analytics creates a local analytics cache on your Mac. The cache stores
derived facts and metadata such as counts, dates, participant labels, message
lengths, emoji/reaction counts, shared item categories, and app user-state.

Messages Analytics does not persist raw message bodies, subjects, attributed-body
strings, attachment filenames, attachment URLs, or raw Messages database tables
as exportable app data.

## Contacts

Contacts access is optional. If you allow Contacts access, Messages Analytics uses
local contact information to improve participant display names and grouping.
The app does not upload the Contacts address book, contact photos, or local
Contacts cache. If you separately create a hidden-contact or merge rule and
turn on **Sync hidden and merge choices**, only the rule name and participant
identifiers already stored in that rule are covered by the separate consent and
sync boundary below.

If you deny Contacts access, Messages Analytics remains usable with identifiers and
fallback labels.

## iCloud Sync

Messages Analytics can optionally use your private iCloud database to sync app
user-state rules across your Macs. Settings > Sync shows the data involved,
private-iCloud destination, and sync purpose beside a switch that is off by
default and shown off until this Mac has current consent. Turning that switch
on is your explicit consent before any private-iCloud rule read or write.
Synced records are limited to hidden-contact rules, historical
person merge rules, accepted group merge rules, and technical sync metadata.
The rules can contain rule names and participant identifiers, such as phone
numbers or email addresses, needed to identify the choices you made. Consent
and sync enablement remain local to each Mac; data from iCloud cannot turn sync
on or off for another Mac.

This information is used only to reproduce your hidden-contact and merge choices
on your Macs. The private iCloud database belongs to your Apple Account and is
not visible to the developer.

iCloud user-state sync does not include message bodies, analytics cache contents,
Contacts address-book records or photos, the local Contacts cache, diagnostics
reports, or selected-summary exports.

## Support Information And Exports

Support information and selected-summary exports are user-initiated. Help >
Troubleshooting loads the support report only for Copy Support Information or
Technical Details, and both paths redact user-specific path components.
Selected-summary exports contain aggregate summary fields only.

Messages Analytics does not use advertising, tracking, or third-party analytics
SDKs.

## Data Deletion

You can reset the local analytics cache from the app. Cache reset removes
imported Messages analytics and cached contact resolution while preserving
user-state settings such as hidden contacts and merge rules where applicable.

You can also remove the app and its local Application Support data from your Mac
using normal macOS file-management tools.

Turning off **Settings > Sync > Sync hidden and merge choices** withdraws consent
and prevents new private-iCloud rule reads and writes on that Mac. The inline
disclosure remains visible before you turn sync on again. Turning sync off does
not itself delete rule records already stored in iCloud.

Existing synced rule records remain in your private iCloud database until they
are replaced through sync or you remove the app's iCloud data. To delete that
copy on macOS, open **System Settings > [your name] > iCloud > Manage**, select
Messages Analytics in the app list, choose **Delete from iCloud**, and confirm.
Apple documents this control in [Manage iCloud storage on Mac](https://support.apple.com/guide/mac-help/manage-icloud-storage-mh36833/mac).
Because the private database is not visible to the developer, the developer
cannot inspect or delete it on your behalf.

## Support

For help, see the [support page](https://fmnobar.github.io/message-ledger-pages/support/).
