---
layout: default
active_season: "25-26_Div2"
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

# CLASIFICACIÓN

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/clasificacion.png" alt="clasificacion" onerror="this.style.display='none'"/>
</div>

# GOLEADORES

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/{{ temporada }}/{{ division }}/goleadores.png" alt="goleadores" onerror="this.style.display='none'"/>
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
