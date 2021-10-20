# Welcome

## Commit, Push etc.
Hopefully this has worked.

{% for stuff in site.stuff %}
  <h2>
    <a href="{{ stuff.url }}">
      {{ stuff.title }}
    </a>
  </h2>
  <p>{{ stuff.content | markdownify }}</p>
{% endfor %}