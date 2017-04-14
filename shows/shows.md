---
layout: page
title: Shows
subtitle: We Will Never Be a Band
permalink: /shows/
comments: false
author_footer: false
---

{% for show in site.data.shows %}
### {{ show.title }}
{{ show.caption }}
{% include youtube.html video=show.youtube %}
{% endfor %}
