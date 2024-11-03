# Apresentação Tênis

{% if build == "slides" %}

<!-- BUILDING THE SLIDES -->

```{toctree}
:maxdepth: 2
:caption: Apresentação Tênis

./requisitos

```

{% else %}


<!-- BUILDING THE PAGES -->

```{include} ./requisitos.md
```

{% endif %}
