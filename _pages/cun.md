from cv.md
# Publications
# ======
#  <ul>{% for post in site.publications %}
#    {% include archive-single-cv.html %}
#  {% endfor %}</ul>
  
# Talks
# ======
#   <ul>{% for post in site.talks %}
#     {% include archive-single-talk-cv.html %}
#   {% endfor %}</ul>
   
#  Teaching
#  ======
#    <ul>{% for post in site.teaching %}
#      {% include archive-single-cv.html %}
#    {% endfor %}</ul>


---
layout: compress
---

{% include base_path %}

<!doctype html>
<html lang="{{ site.locale | slice: 0,2 }}" class="no-js">
  <head>
    {% include head.html %}
    {% include head/custom.html %}
  </head>

  <body>

    {% include browser-upgrade.html %}
    {% include masthead.html %}

    {{ content }}

    <div class="page__footer">
      <footer>
        {% include footer/custom.html %}
        {% include footer.html %}
      </footer>
    </div>

    {% include scripts.html %}

  </body>
</html>