{% if build == "slides" %}

<!-- BUILDING THE SLIDES -->

```{toctree}
:maxdepth: 2
:caption: Apresentação Tênis

./inicio
./requisitos
./tipos-de-campo
./golpes

```

{% else %}


<!-- BUILDING THE PAGES -->

```{include} ./inicio.md
```

```{include} ./requisitos.md
```

```{include} ./tipos-de-campo.md
```

```{include} ./golpes.md
```

{% endif %}
