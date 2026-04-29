# 🎨 Inline blocks and colors

### 🧪 Git Sync color regression repro

Expected before/inside GitBook: each label should remain readable, with colored text on a lighter matching background.

If the bug is active after Git Sync round-trip, these cells may become solid color bars because `color:blue;background-color:blue` is interpreted as raw CSS instead of GitBook palette tokens.

| Status | Same-token text + background                                                    | Separate text/background marks                                                                                     |
| ------ | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Blue   | <mark style="color:blue;background-color:blue;">Default</mark>                  | <mark style="color:blue;">Default</mark> / <mark style="background-color:blue;">background</mark>                  |
| Green  | <mark style="color:green;background-color:green;">Supported</mark>              | <mark style="color:green;">Supported</mark> / <mark style="background-color:green;">background</mark>              |
| Orange | <mark style="color:orange;background-color:orange;">Not supported</mark>        | <mark style="color:orange;">Not supported</mark> / <mark style="background-color:orange;">background</mark>        |
| Purple | <mark style="color:purple;background-color:purple;">Customer integration</mark> | <mark style="color:purple;">Customer integration</mark> / <mark style="background-color:purple;">background</mark> |
| Cyan   | <mark style="color:cyan;background-color:cyan;">Experimental</mark>             | <mark style="color:cyan;">Experimental</mark> / <mark style="background-color:cyan;">background</mark>             |

#### Non-table control

These should help tell whether the table path makes it worse:

- <mark style="color:blue;background-color:blue;">Default</mark>
- <mark style="color:green;background-color:green;">Supported</mark>
- <mark style="color:orange;background-color:orange;">Not supported</mark>
- <mark style="color:purple;background-color:purple;">Customer integration</mark>
- <mark style="color:cyan;background-color:cyan;">Experimental</mark>

### 🎨 **Default colors**

Added this paragraph and pushed back to gitbook/hub

- <mark style="color:red;">red</mark> / <mark style="background-color:red;">background</mark> / <i class="fa-duck">:duck:</i>
- <mark style="color:pink;">pink</mark> / <mark style="background-color:pink;">background</mark> / <i class="fa-kiwi-bird">:kiwi-bird:</i>
- <mark style="color:violet;">violet</mark> / <mark style="background-color:violet;">background</mark> / <i class="fa-dog">:dog:</i>
- <mark style="color:purple;">purple</mark> / <mark style="background-color:purple;">background</mark> / <i class="fa-octopus">:octopus:</i>
- <mark style="color:blue;">blue</mark> / <mark style="background-color:blue;">background</mark> / <i class="fa-cat">:cat:</i>
- <mark style="color:cyan;">cyan</mark> / <mark style="background-color:cyan;">background</mark> / <i class="fa-horse">:horse:</i>
- <mark style="color:green;">green</mark> / <mark style="background-color:green;">background</mark> / <i class="fa-mouse-field">:mouse-field:</i>
- <mark style="color:yellow;">yellow</mark> / <mark style="background-color:yellow;">background</mark> / <i class="fa-fish-fins">:fish-fins:</i>
- <mark style="color:orange;">orange</mark> / <mark style="background-color:orange;">background</mark> / <i class="fa-butterfly">:butterfly:</i>

### 🌎 **Semantic site-customization colors**

- <mark style="color:$primary;">primary</mark> / <mark style="background-color:$primary;">primary</mark>
- <mark style="color:$info;">info</mark> / <mark style="background-color:$info;">info</mark>
- <mark style="color:$tint;">tint</mark> / <mark style="background-color:$tint;">tint</mark>
- <mark style="color:$success;">success</mark> / <mark style="background-color:$success;">success</mark>
- <mark style="color:$warning;">warning</mark> / <mark style="background-color:$warning;">warning</mark>
- <mark style="color:$danger;">danger</mark> / <mark style="background-color:$danger;">danger</mark>

trivial change

|                                                                                                                                          |                                                                                                                                            |                                                                                                                                                |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark style="color:red;">red</mark> / <mark style="background-color:red;">background</mark> / <i class="fa-duck">:duck:</i>              | <mark style="color:purple;">purple</mark> / <mark style="background-color:purple;">background</mark> / <i class="fa-octopus">:octopus:</i> | <mark style="color:yellow;">yellow</mark> / <mark style="background-color:yellow;">background</mark> / <i class="fa-fish-fins">:fish-fins:</i> |
| <mark style="color:pink;">pink</mark> / <mark style="background-color:pink;">background</mark> / <i class="fa-kiwi-bird">:kiwi-bird:</i> | <mark style="color:blue;">blue</mark> / <mark style="background-color:blue;">background</mark> / <i class="fa-cat">:cat:</i>               | <mark style="color:orange;">orange</mark> / <mark style="background-color:orange;">background</mark> / <i class="fa-butterfly">:butterfly:</i> |
| <mark style="color:violet;">violet</mark> / <mark style="background-color:violet;">background</mark> / <i class="fa-dog">:dog:</i>       | <mark style="color:cyan;">cyan</mark> / <mark style="background-color:cyan;">background</mark> / <i class="fa-horse">:horse:</i>           |                                                                                                                                                |
