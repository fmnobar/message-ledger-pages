---
title: Message Ledger Privacy Policy
permalink: /privacy/
---

# Message Ledger Privacy Policy

Effective date: May 28, 2026

Message Ledger is a local-first macOS app. It helps you analyze aggregate
patterns in your own Messages history while keeping the source data under your
control.

## Messages Source Access

Message Ledger asks you to choose your local Messages folder. The app stores a
local security-scoped bookmark so it can refresh the local analytics cache after
you approve access.

Message Ledger opens the Messages `chat.db` database in read-only mode. It does
not write to or modify your Messages database.

## Local Analytics Cache

Message Ledger creates a local analytics cache on your Mac. The cache stores
derived facts and metadata such as counts, dates, participant labels, message
lengths, emoji/reaction counts, shared item categories, and app user-state.

Message Ledger does not persist raw message bodies, subjects, attributed-body
strings, attachment filenames, attachment URLs, or raw Messages database tables
as exportable app data.

## Contacts

Contacts access is optional. If you allow Contacts access, Message Ledger uses
local contact information to improve participant display names and grouping.
Contacts records are not sent to a developer server.

If you deny Contacts access, Message Ledger remains usable with identifiers and
fallback labels.

## iCloud Sync

Message Ledger can optionally use iCloud to sync app user-state rules and
settings through your Apple account. Synced user-state is limited to items such
as hidden-contact rules, person/group merge rules, and sync settings metadata.

iCloud sync does not include message bodies, analytics cache contents, Contacts
records, diagnostics reports, or selected-summary exports.

## Diagnostics And Exports

Diagnostics and selected-summary exports are user-initiated. Diagnostics reports
include app/cache status and redact user-specific path components in copied or
saved reports. Selected-summary exports contain aggregate summary fields only.

Message Ledger does not use advertising, tracking, or third-party analytics
SDKs.

## Data Deletion

You can reset the local analytics cache from the app. Cache reset removes
imported Messages analytics and cached contact resolution while preserving
user-state settings such as hidden contacts and merge rules where applicable.

You can also remove the app and its local Application Support data from your Mac
using normal macOS file-management tools.

## Support

For help, see the [support page](../support/).
