# Welcome

## Commit, Push etc.
Hopefully this has worked.

[Test Content Article](/content/20211014_Test_Content_1.md)
This is some text talking about the test article

[Test Content Article](/content/20211005_Test_Content_1.md)
This is some text talking about the test article

{% for file in site.content %}
{% if file.extname == ".md" %}
[{{ file.basename }}]({{site.baseurl}}/{{file.basename}}.html)
{% endif %}
{% endfor %}