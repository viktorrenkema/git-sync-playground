---
description: >-
  All the GitBook features, updates, improvements and fixes we released in 2022
  and earlier
hidden: false
---

# heading-1 2022 and earlier product updates

{% updates format="full" %}
{% update date="2022-12-15" %}

## heading-2 Editor improvements, and more

We've worked on GitBook's overall editor experience, improving reliability, copy/paste from multiple sources and speedy shortcuts.

### heading-3 Copy/Paste from Google Docs

Copying and pasting content from Google Docs into GitBook is now faster and more reliable, maintaining the formatting and structure of content created in Google Docs. Headings, lists, and more save their formatting as you paste them in GitBook.

<figure><img src=".gitbook/assets/CleanShot 2023-01-25 at 14.58.44.gif" alt=""><figcaption><p>Copy and paste headers, lists, and more between Google Docs and GitBook</p></figcaption></figure>

- Copy/pasting from Google Docs will maintain the formatting.

### heading-3 Copy/Paste from VS Code

Copying and pasting content from VS Code will now automatically paste as a code block, auto-formatting and styling your code in it's detected language.&#x20;

<figure><img src=".gitbook/assets/CleanShot 2023-01-25 at 15.09.19.gif" alt=""><figcaption><p>Copy and paste code from VS Code into GitBook</p></figcaption></figure>

- Code pasting from VSCode should now be more reliable.
- Pasted code in GitBook will automatically paste as a code block.

### heading-3 Copy/Paste from Google Sheets and Excel

Copy and pasting content from Google Sheets and Excel now automatically creates a table for you and maintains the position of each cell, row, and column. It's also easier to work with tables.

<figure><img src=".gitbook/assets/CleanShot 2023-01-26 at 10.40.52.gif" alt=""><figcaption><p>Copy and paste entire spreadsheets into GitBook</p></figcaption></figure>

- Copy/paste from Excel will automatically paste as a table
- Make it possible to select an entire table from its border.

### heading-3 Inline palette in the editor

Adding inline images, links, emojis and others is now easier with our **inline palette**. It can be triggered by hitting `/` in the editor.

<figure><img src=".gitbook/assets/CleanShot 2023-01-26 at 10.46.18.gif" alt=""><figcaption><p>Easily add images, emojis and page links to your text</p></figcaption></figure>

- Add inline controls shortcut `/`&#x20;
- Add page linking to the inline palette&#x20;

We've also made improvements to the following:&#x20;

- Dropping a file on the Editor should now be more reliable.
- Improved performance and image loading.

### heading-3 Fixed

Below is a list of bug fixes also included in this release:

- Fix an issue where we were not correctly calculating diffs and conflicts for text with marks.
- Fix Edit button not responding after first click.
- Fix an issue where cyclic OpenAPI schemas wouldn't generate any examples.
- Fixed an issue where unsaved content would not be shown in diff view.
- Fix re-ordering and hiding of table columns.
- Fix diff and merge of documents with images or links.
- Fix an issue where the embed would fail if the returned icon did not contain a protocol.
  {% endupdate %}

{% update date="2022-11-30" %}

## heading-2 Annotations, footnotes, and more

We’ve added more ways to provide contextual information for your visitors, as well as improvements to expandable blocks and several bug fixes.

### heading-3 New

- You can now add inline text annotations! Easily provide useful secondary information with content blocks that expand upon clicking. It’s a handy way to provide additional context without breaking a reader’s train of thought.&#x20;

<figure><img src=".gitbook/assets/CleanShot 2023-01-12 at 10.59.22.gif" alt=""><figcaption><p>Here’s how you add annotations to your content</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption><p>And here’s what it looks like to your visitors</p></figcaption></figure>

- We’ve also added support for footnotes in Markdown, which are imported into GitBook as inline annotations.
- Expandable blocks now have an anchor link you can copy and paste. Additionally, we now expand a block automatically when the page is accessed. This allows you to quickly direct visitors to a specific part of your documentation.

<figure><img src=".gitbook/assets/CleanShot 2022-11-30 at 11.33.11.gif" alt=""><figcaption></figcaption></figure>

### heading-3 Improvements

- Better handling of errors in calls to our API, specifically when listing spaces.

### heading-3 Fixed

- Fix an issue where heading anchors were `undefined` when target immediately after they were created.
- You can now use drag and drop to move a space to a collection that is nested inside another collection.
- When using the inline palette, it should now have the focus return to the editor after closing it.
- Fix pasting tables for certain websites.
- Fix an issue where duplicated characters are sometimes inserted when typing in code blocks.
- Fix page outlines that were too big, now they should be scrollable for viewing the entire list.
- Fix an issue where focus would be trapped in a popover when selecting math equations.
- Fix an issue where diff view would incorrectly show that text had changed if the number of words in the paragraph had changed.
  {% endupdate %}
  {% endupdates %}
