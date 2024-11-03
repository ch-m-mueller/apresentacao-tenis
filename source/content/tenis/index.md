{% if build == "slides" %}

<!-- BUILDING THE SLIDES -->

```{toctree}
:maxdepth: 2
:caption: Apresentação Tênis

./requisitos
./tipos-de-campo

```

{% else %}


<!-- BUILDING THE PAGES -->

```{include} ./requisitos.md
```

```{include} ./tipos-de-campo.md
```

{% endif %}
