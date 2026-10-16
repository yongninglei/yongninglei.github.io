---
layout: clean
title: "Publications"
permalink: /publication/
redirect_from:
  - /publications/
  - /talks/
---

{% capture pubs %}{% include publications.md %}{% endcapture %}
{{ pubs | markdownify }}
