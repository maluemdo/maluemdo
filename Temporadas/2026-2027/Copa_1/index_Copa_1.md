---
layout: default
active_season: "26-27_copa_1"
---

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
  <img src="../../../images/2025-2026/Copa/cuadro4.png" alt="cuadro4" onerror="this.style.display='none'"/>
  <img src="../../../images/2025-2026/Copa/cuadro5.png" alt="cuadro5" onerror="this.style.display='none'"/>
</div>-->


# RESULTADOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2025-2026/Copa/cuadro5.png" alt="cuadro5" onerror="this.style.display='none'"/>
  <img src="../../../images/2025-2026/Copa/cuadro4.png" alt="cuadro4" onerror="this.style.display='none'"/>
  <img src="../../../images/2025-2026/Copa/cuadro3.png" alt="cuadro3" onerror="this.style.display='none'"/>
  <img src="../../../images/2025-2026/Copa/cuadro2.png" alt="cuadro2" onerror="this.style.display='none'"/>
  <img src="../../../images/2025-2026/Copa/cuadro1.png" alt="cuadro1" onerror="this.style.display='none'"/>
</div>
