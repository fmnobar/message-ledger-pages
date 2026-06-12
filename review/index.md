---
title: Message Ledger App Review Sample Data
permalink: /review/
---

# Message Ledger App Review Sample Data

Apple App Review can use this synthetic sample package to review Message Ledger
without access to a real local Messages history.

[Download MessageLedger-AppReview-SampleData.zip](MessageLedger-AppReview-SampleData.zip)

The package includes:

- `Messages/chat.db`, a synthetic Messages database for Message Ledger review.
- `Contacts/message-ledger-demo-contacts.vcf`, an optional fictional Contacts
  vCard with generated portrait photos.
- `README.txt`, setup instructions and sample coverage details.

## Review Setup

1. Download and unzip the sample package.
2. Launch Message Ledger.
3. When Message Ledger asks for a Messages folder, choose the unzipped
   `Messages` folder that contains `chat.db`.
4. Allow Message Ledger to build its local analytics cache.
5. Optional: import `Contacts/message-ledger-demo-contacts.vcf` into Contacts and
   allow Contacts access in Message Ledger to see fictional names and portraits.
6. Use Refresh or Rebuild Cache in Message Ledger if the import needs to be run
   again.

The sample data is fully synthetic and contains no real Messages, Contacts,
phone numbers, email domains, or personal user data.
