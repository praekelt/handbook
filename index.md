---
layout: bootstrap
---

<div class="container-fluid">
  {% for post in site.posts %}
  <div class="row">
    <div class="col-lg-6 col-lg-offset-3">
      {{post.content}}
    </div>
  </div>
  {% endfor %}
</div>

