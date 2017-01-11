# codemirror-bundle

A Symfony bundle providing CodeMirror CSS and JS files

```
{% include 'peerjCodeMirrorBundle::styles.html.twig' %}
{% include 'peerjCodeMirrorBundle::scripts.html.twig' %}
```

## Updating

When there is a new CodeMirror release, update `bower.json` if needed, run `bower update codemirror` to fetch the latest version of the CodeMirror files, commit them to this repository and create a new release.
