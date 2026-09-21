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
    <td style="text-align: left; border: inset 0pt">
      <a href="../../../Temporadas/{{ temporada }}/{{ division }}/equipaciones_{{ temporada }}.html">Equipaciones {{ div_texto }} Futbol 7 {{ temp_corto }}</a>
    </td>
  </tr>
</table>
<br>

# CLASIFICACIÓN

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/clasificacion.png" alt="clasificacion" onerror="this.style.display='none'"/>
</div>
<a href="../../../Temporadas/{{ temporada }}/{{ division }}/goleadores_{{ temporada }}.html">Goleadores</a>

# PRÓX.PARTIDOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada1.png" alt="proxjornada1" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada2.png" alt="proxjornada2" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada3.png" alt="proxjornada3" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada4.png" alt="proxjornada4" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada5.png" alt="proxjornada5" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada6.png" alt="proxjornada6" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada7.png" alt="proxjornada7" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada8.png" alt="proxjornada8" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada9.png" alt="proxjornada9" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada10.png" alt="proxjornada10" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada11.png" alt="proxjornada11" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada12.png" alt="proxjornada12" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada13.png" alt="proxjornada13" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada14.png" alt="proxjornada14" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada15.png" alt="proxjornada15" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada16.png" alt="proxjornada16" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada17.png" alt="proxjornada17" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada18.png" alt="proxjornada18" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada19.png" alt="proxjornada19" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada20.png" alt="proxjornada20" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada21.png" alt="proxjornada21" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada22.png" alt="proxjornada22" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada23.png" alt="proxjornada23" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada24.png" alt="proxjornada24" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada25.png" alt="proxjornada25" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/proxjornada26.png" alt="proxjornada26" onerror="this.style.display='none'"/>
</div>

# RESULTADOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada26.png" alt="jornada26" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada25.png" alt="jornada25" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada24.png" alt="jornada24" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada23.png" alt="jornada23" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada22.png" alt="jornada22" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada21.png" alt="jornada21" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada20.png" alt="jornada20" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada19.png" alt="jornada19" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada18.png" alt="jornada18" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada17.png" alt="jornada17" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada16.png" alt="jornada16" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada15.png" alt="jornada15" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada14.png" alt="jornada14" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada13.png" alt="jornada13" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada12.png" alt="jornada12" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada11.png" alt="jornada11" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada10.png" alt="jornada10" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada9.png" alt="jornada9" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada8.png" alt="jornada8" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada7.png" alt="jornada7" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada6.png" alt="jornada6" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada5.png" alt="jornada5" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada4.png" alt="jornada4" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada3.png" alt="jornada3" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada2.png" alt="jornada2" onerror="this.style.display='none'"/>
  <img src="../../../images/{{ temporada }}/{{ division }}/jornada1.png" alt="jornada1" onerror="this.style.display='none'"/>
</div>
