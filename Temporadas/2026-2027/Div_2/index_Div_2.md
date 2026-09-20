---
layout: default
---

<table style="border: inset 0pt; width: 100%;">
  <tr style="text-align: left; border: inset 0pt">
    <td style="text-align: left; border: inset 0pt; width: 50%;">
      <!-- AQUÍ SE PINTARÁ EL DESPLEGABLE -->
      <div id="contenedor-desplegable"></div>
    </td>
    <td style="text-align: right; border: inset 0pt; width: 50%;">
      <a href="../../../Temporadas/2026-2027/Div_2/equipaciones_2026-2027.html">Equipaciones 3ª Div Futbol 7 25-26</a>
    </td>
  </tr>
</table>
<br>

# CLASIFICACIÓN

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/clasificacion.png" alt="clasificacion" onerror="this.style.display='none'"/>
</div>
<a href="../../../Temporadas/2026-2027/Div_2/goleadores_2026-2027.html">Goleadores</a>

# PRÓX.PARTIDOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/proxjornada1.png" alt="proxjornada1" onerror="this.style.display='none'"/>
  <!-- NOTA: Aquí puedes volver a pegar el resto de tus imágenes de proxjornada si lo deseas -->
  <img src="../../../images/2026-2027/Div_2/proxjornada26.png" alt="proxjornada26" onerror="this.style.display='none'"/>
</div>

# RESULTADOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/jornada26.png" alt="jornada26" onerror="this.style.display='none'"/>
  <!-- NOTA: Aquí puedes volver a pegar el resto de tus imágenes de jornadas si lo deseas -->
  <img src="../../../images/2026-2027/Div_2/jornada1.png" alt="jornada1" onerror="this.style.display='none'"/>
</div>

<!-- EL SCRIPT REESCRITO PARA QUE JEKYLL NO LO BORRE -->
<script type="text/javascript">
window.addEventListener('load', function() {
    var nombreRepositorio = "maluemdo"; 
    var temporadas =; 

    var contenedor = document.getElementById('contenedor-desplegable');
    if (!contenedor) return;

    var html = '<select onchange="if(this.value) window.location.href=this.value;" style="padding: 6px; font-size: 14px; color: black; background-color: white; border: 1px solid #ccc;">';
    html += '<option value="">-- Selecciona Temporada --</option>';

    var baseRaiz = '/' + nombreRepositorio + '/Temporadas/';

    temporadas.forEach(function(anio) {
        var labelAnio = String(anio).slice(-2) + '-' + String(anio + 1).slice(-2);
        var carpetaAnio = anio + '-' + (anio + 1);

        // Generar Divisiones (1 a 4)
        for (var div = 1; div <= 4; div++) {
            var ruta = baseRaiz + carpetaAnio + '/Div_' + div + '/index_Div_' + div + '.html';
            var texto = labelAnio + ' ' + div + 'ª Div';
            html += '<option value="' + ruta + '">' + texto + '</option>';
        }

        // Generar Copa
        var rutaCopa = baseRaiz + carpetaAnio + '/Copa/index_Copa.html';
        var textoCopa = labelAnio + ' Copa';
        html += '<option value="' + rutaCopa + '">' + textoCopa + '</option>';
    });

    html += '</select>';
    contenedor.innerHTML = html;
});
</script>
