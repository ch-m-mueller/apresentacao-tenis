{% if build == "slides" %}

<!-- BUILDING THE SLIDES -->

```{toctree}
:maxdepth: 2
:caption: Apresentação Ténis

./inicio
./requisitos
./tipos-de-campo
./golpes
./raquete

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

```{include} ./raquete.md
```


{% endif %}
