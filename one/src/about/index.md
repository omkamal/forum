---
title: "About us"
bannerContent: "This is a little paragraph about the company."
---
{% include "includes/banner.html" %}

## Eleventy
It can use any markdown, since we're in a markdown page. Like [an anchor](https://packtpub.com) or **bold text**.
* Or an unordered list
* With some items

{% for i in items %}
1. {{i.name}} have {{i.age}}
{% endfor %}


