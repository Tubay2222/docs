{% if enterpriseServerVersions contains currentVersion and currentVersion ver_lt "enterprise-server@2.21" %}
{% note %}

**Nota:** Los Manifiestos de las {% data variables.product.prodname_github_app %}s se encuentran actualmente disponibles para que los desarrolladores los previsualicen. Para acceder a esta API durante el periodo de vista previa, debes proporcionar un [tipo de medios](/rest/overview/media-types) personalizado en el encabezado de `Accept`:

```
application/vnd.github.fury-preview+json
```

{% endnote %}
{% endif %}
