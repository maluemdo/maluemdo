---
layout: default
active_season: "25-26_copa"
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

<table style=" border: inset 0pt">
  <tr style="text-align: left; border: inset 0pt">
    <td style="text-align: left; border: inset 0pt">
      <select onchange="window.location.href=this.value">
        {% for option in site.data.seasons %}
          <option value="{{ option.url | relative_url }}" {% if page.active_season == option.id %}selected{% endif %}>
            {{ option.name }}
          </option>
        {% endfor %}
      </select>
    </td>
  </tr>
</table>
<br>

<!--# PARTIDOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro4.png" alt="cuadro4" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro5.png" alt="cuadro5" onerror="this.style.display='none'"/>
</div>-->


# RESULTADOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro5.png" alt="cuadro5" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro4.png" alt="cuadro4" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro3.png" alt="cuadro3" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro2.png" alt="cuadro2" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/cuadro1.png" alt="cuadro1" onerror="this.style.display='none'"/>
</div>
