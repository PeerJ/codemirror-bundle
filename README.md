# codemirror-bundle

A Symfony bundle providing CodeMirror CSS and JS files

```
{% block stylesheets %}
    {{ parent() }}
    {% include 'peerjCodeMirrorBundle::styles.html.twig' %}
{% endblock %}

{% block javascripts %}
    {{ parent() }}
    {% include 'peerjCodeMirrorBundle::scripts.html.twig' %}
{% endblock %}
```
