---
layout: page
title: Page Status Link for Confluence
permalink: /page-status-link/
---

Page Status Link for Confluence adds an inline macro that links to a permitted Confluence page and shows its current content status.

## Use Page Status Link

1. Edit a Confluence page.
2. Insert **Page Status Link**.
3. Paste or choose a page URL from the same Confluence site.
4. Save the macro configuration.
5. Publish or update the page.
6. The macro displays the linked page title and current content status.

If the linked page has no assigned content status, the macro displays **No status**.

## Limitations

- The target must be a page on the same Confluence site.
- Viewers must have permission to view the target page.
- The app reads page metadata and content-state information only; it does not edit pages.
- A deleted, inaccessible, invalid, or unexpected target is shown as unavailable.
- An active Marketplace licence is required in production.

For help, see [Support]({{ '/support/' | relative_url }}). For data handling, read the [Page Status Link privacy policy]({{ '/page-status-link-privacy/' | relative_url }}).
