---
layout: base

---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<div class="wrapper">
 <main>
      {% if site.content %}
      <div class="content">
        {% include content.html %}
      </div>
      {% endif %}
    </main>
</div>