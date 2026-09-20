---
layout: default
active_season: "26-27_div2"
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

## Equipaciones {{ div_texto }} Futbol 7 {{ temp_corto }}

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/equipaciones1.png" alt="equipaciones1" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/equipaciones2.png" alt="equipaciones2" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/equipaciones3.png" alt="equipaciones3" onerror="this.style.display='none'"/>
</div>
<a href="../../../Temporadas/{{ temporada }}/{{ division }}/index_{{ division }}.html">Atras</a>
