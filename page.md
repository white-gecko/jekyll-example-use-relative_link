---
layout: default
---

Some page ({{ page.url }})

- [index: {% relative_link index.html %}]({% relative_link index.html %})
- [archive: {% relative_link archive.html %}]({% relative_link archive.html %})
- [page: {% relative_link page.md %}]({% relative_link page.md %})
- [about: {% relative_link about/you.html %}]({% relative_link about/you.html %})
- [post: {% relative_link _posts/2000-01-01-new-year.md %}]({% relative_link _posts/2000-01-01-new-year.md %})
