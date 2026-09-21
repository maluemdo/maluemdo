---
layout: default
active_season: "25-26_Div3"
---

<!-- Extraemos automáticamente las constantes de seasons.yml según el active_season -->
{% for s in site.data.seasons %}
  {% if s.id == page.active_season %}
    {% assign temporada = s.temporada %}
    {% assign division = s.division %}
    {% assign temp_corto = s.temp_corto %}
    {% assign div_texto = s.div_texto%}
  {% endif %}
{% endfor %}

## Goleadores {{ div_texto }} Futbol 7 {{ temp_corto }}

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/goleadores.png" alt="goleadores" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/goleadores2.png" alt="goleadores2" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/goleadores3.png" alt="goleadores3" onerror="this.style.display='none'"/>
</div>
<a href="../../../Temporadas/{{ temporada }}/{{ division }}/index_{{ division }}.html">Atras</a>
