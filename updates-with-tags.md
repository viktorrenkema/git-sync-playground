---
description: Updates block with tagged entries
---

# updates with tags

{% updates format="full" %}
{% update date="2026-02-26" tags="new,beta" %}
## Tagged update entry

This update has the **New** and **Beta** tags attached. Both should be visible on the update entry in GitBook.
{% endupdate %}

{% update date="2026-02-20" tags="experimental" %}
## Experimental feature update

This update has only the **Experimental** tag. It should display the 🧪 emoji.
{% endupdate %}

{% update date="2026-02-15" tags="nieuwe-tag" %}
## Mixed tags update

This update combines **Deprecated** (⚠️) and **Stable** (check-circle icon) tags on a single entry.
{% endupdate %}
{% endupdates %}
