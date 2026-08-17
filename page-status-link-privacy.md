---
layout: page
title: Page Status Link for Confluence Privacy Policy
permalink: /page-status-link-privacy/
---

Last updated: 17 August 2026

This policy describes the current technical data handling of Page Status Link for Confluence.

## Data handling

Page Status Link uses the viewer's Confluence permission context to read:

- `read:page:confluence` to obtain the selected page's current metadata, including its title and link;
- `read:confluence-content.summary` to obtain the selected page's current content status.

The app:

- does not write to Confluence;
- uses no Forge Storage;
- has no remote backend or external datastore;
- performs no external network egress;
- uses no analytics, tracking or advertising; and
- does not operate an app-managed customer database.

The selected page reference is stored by Atlassian as macro configuration. Page metadata and status are read at render time in the viewer's permission context. The app does not receive or store the page body through an external service.

## Licensing

The app is distributed as a Paid via Atlassian Marketplace app. Atlassian manages Marketplace licensing. Production access requires an active licence; development and custom environments are used for testing.

## Contact

For privacy questions, email [caffeineandcashflowsupport@gmail.com](mailto:caffeineandcashflowsupport@gmail.com). For product help, see [Support]({{ '/support/' | relative_url }}).

This technical policy does not claim GDPR, ISO, SOC, HIPAA or PCI certification, and it is not a formal legal opinion.
