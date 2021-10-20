# Welcome

## Commit, Push etc.
Hopefully this has worked.

[Test Content Article](/content/20211014_Test_Content_1.md)
This is some text talking about the test article

[Test Content Article](/content/20211005_Test_Content_1.md)
This is some text talking about the test article

{% for stuff in site.stuff %}
  <h2>
    <a href="{{ stuff.url }}">
      {{ stuff.title }}
    </a>
  </h2>
  <p>{{ stuff.content | markdownify }}</p>
{% endfor %}