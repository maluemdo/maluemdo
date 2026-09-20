---
layout: default
---

<table style=" border: inset 0pt">
  <tr style="text-align: left; border: inset 0pt">
    <td style="text-align: left; border: inset 0pt">
        <div id="contenedor-desplegable"></div>
    </td>
    <td style="text-align: left; border: inset 0pt">
      <a href="../../../Temporadas/2026-2027/Div_2/equipaciones_2026-2027.html">Equipaciones 3ª Div Futbol 7 25-26</a>
    </td>
  </tr>
</table>

  <script>
  const temporadas =; 
  
  function generarMenuCompleto() {
      let html = `<select onchange="if(this.value) window.location.href=this.value;">`;
      html += `<option value="">-- Selecciona Temporada --</option>`;
  
      temporadas.forEach(anio => {
          const tempEtiqueta = `${String(anio).slice(-2)}-${String(anio + 1).slice(-2)}`;
          const tempCarpeta = `${anio}-${anio + 1}`;
  
          for (let div = 1; div <= 4; div++) {
              const ruta = `../../../Temporadas/${tempCarpeta}/Div_${div}/index_Div_${div}.html`;
              const texto = `${tempEtiqueta} ${div}ª Div`;
              html += `<option value="${ruta}">${texto}</option>`;
          }
  
          const rutaCopa = `../../../Temporadas/${tempCarpeta}/Copa/index_Copa.html`;
          const textoCopa = `${tempEtiqueta} Copa`;
          html += `<option value="${rutaCopa}">${textoCopa}</option>`;
      });
  
      html += `</select>`;
      document.getElementById('contenedor-desplegable').innerHTML = html;
  }
  
  // Esto se encarga de ejecutar el código e inyectar el menú en el <div> de arriba
  generarMenuCompleto();
  </script>
<br>

# CLASIFICACIÓN

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/clasificacion.png" alt="clasificacion" onerror="this.style.display='none'"/>
</div>
<a href="../../../Temporadas/2026-2027/Div_2/goleadores_2026-2027.html">Goleadores</a>


# PRÓX.PARTIDOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/proxjornada1.png" alt="proxjornada1" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada2.png" alt="proxjornada2" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada3.png" alt="proxjornada3" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada4.png" alt="proxjornada4" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada5.png" alt="proxjornada5" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada6.png" alt="proxjornada6" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada7.png" alt="proxjornada7" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada8.png" alt="proxjornada8" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada9.png" alt="proxjornada9" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada10.png" alt="proxjornada10" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada11.png" alt="proxjornada11" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada12.png" alt="proxjornada12" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada13.png" alt="proxjornada13" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada14.png" alt="proxjornada14" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada15.png" alt="proxjornada15" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada16.png" alt="proxjornada16" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada17.png" alt="proxjornada17" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada18.png" alt="proxjornada18" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada19.png" alt="proxjornada19" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada20.png" alt="proxjornada20" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada21.png" alt="proxjornada21" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada22.png" alt="proxjornada22" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada23.png" alt="proxjornada23" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada24.png" alt="proxjornada24" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada25.png" alt="proxjornada25" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/proxjornada26.png" alt="proxjornada26" onerror="this.style.display='none'"/>
</div>


# RESULTADOS

<div style="text-align: center;" data-proofer-ignore>
  <img src="../../../images/2026-2027/Div_2/jornada26.png" alt="jornada26" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada25.png" alt="jornada25" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada24.png" alt="jornada24" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada23.png" alt="jornada23" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada22.png" alt="jornada22" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada21.png" alt="jornada21" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada20.png" alt="jornada20" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada19.png" alt="jornada19" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada18.png" alt="jornada18" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada17.png" alt="jornada17" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada16.png" alt="jornada16" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada15.png" alt="jornada15" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada14.png" alt="jornada14" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada13.png" alt="jornada13" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada12.png" alt="jornada12" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada11.png" alt="jornada11" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada10.png" alt="jornada10" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada9.png" alt="jornada9" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada8.png" alt="jornada8" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada7.png" alt="jornada7" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada6.png" alt="jornada6" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada5.png" alt="jornada5" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada4.png" alt="jornada4" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada3.png" alt="jornada3" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada2.png" alt="jornada2" onerror="this.style.display='none'"/>
  <img src="../../../images/2026-2027/Div_2/jornada1.png" alt="jornada1" onerror="this.style.display='none'"/>
</div>
