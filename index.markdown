---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
---
---

Welcome to My Home Page

{% assign date = '2022-02-20T08:15:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}
