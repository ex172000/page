---
layout: default
title: Posts
---

## Posts

{% for post_file in site.static_files %}
  {% if post_file.path contains '/posts/' and post_file.extname == '.md' %}
- [{{ post_file.basename | replace: '_', ' ' | replace: '-', ' ' | capitalize }}]({{ post_file.path | remove: '.md' }})
  {% endif %}
{% endfor %}

### Technical Articles

- [Viewstamped Replication Revisited: Determinism, Throughput, and Practical Distributed Systems]({{ site.baseurl }}/posts/viewstamped_replication)
