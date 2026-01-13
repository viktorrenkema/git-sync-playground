---
description: A full rundown of our latest releases, improvements and fixes in GitBook
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Product updates

{% updates format="full" %}
{% update date="2026-01-05" %}

## New Year improvements and bug fixes :tada:

Happy new year! We’re kicking off the new year with some small but mighty improvements and fixes that the team shipped since the last update in December. Stay tuned for more releases soon!

### Improvements

- When you navigate through previous revisions of a space using the [version history](https://app.gitbook.com/s/NkEGS7hzeqa35sMXQZ4X/creating-content/version-control), you’ll now automatically land on the first page that contains changes, saving you time navigating to the pages you need.
- You can now add [file blocks](https://app.gitbook.com/s/NkEGS7hzeqa35sMXQZ4X/creating-content/blocks/insert-files) within [expandable blocks](https://app.gitbook.com/s/NkEGS7hzeqa35sMXQZ4X/creating-content/blocks/expandable), giving you more options to add content to your page.

### Fixes

- Fixed a bug that could occur if a page was deleted at the same time as being queued to be indexed.
- Fixed an issue that meant GitBook Agent would sometimes throw up an error when parsing a stream of valid Markdown.
- Fixed several visual bugs:
  - Diff icons used the wrong white values and colors, so were hard to see in dark mode — now they’re more legible and look great.
  - Restored the breadcrumb in the version history.
  - Diff icons weren’t showing tooltips when viewing a revision in space history.
  - Improved the contrast of green text and red text in diff view.
- Fixed a bug that meant returning to a space from an old space revision would continue showing diff highlighting.
- Fixed a crash that could result in a crash when joining a new organization.
  {% endupdate %}
  {% endupdates %}
