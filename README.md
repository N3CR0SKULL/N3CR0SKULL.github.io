![cooltext419873221794762](https://user-images.githubusercontent.com/105949773/191843846-d7819cda-fb8b-4800-84f0-ee05438b4d98.png)

![cooltext419873040709470](https://user-images.githubusercontent.com/105949773/191843308-765b6758-d995-4f89-a7be-d4388dfcc248.png)

##Configuración de pines de relay DPDT
Generalmente tiene ocho pines. La salida de pines predeterminada del relay DPDT varía según el MODELO. Aquí estamos tomando el dispositivo HK19F-12V como modelo. La salida de pines de HK19F se muestra arriba. Para la configuración de pines de diferentes modelos de relay, consulte su hoja de datos.
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-7btt{border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ffme{background-color:#FFF;border-color:inherit;color:#303030;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-7btt">Número de PIN</th>
    <th class="tg-c3ow">Nombre del pin</th>
    <th class="tg-c3ow">Descripción</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">1</td>
    <td class="tg-0pky">BOBINA1</td>
    <td class="tg-0pky">Extraído de un lado de la bobina</td>
  </tr>
  <tr>
    <td class="tg-c3ow">8</td>
    <td class="tg-0pky">BOBINA2</td>
    <td class="tg-0pky">Extraído del otro lado de la bobina</td>
  </tr>
  <tr>
    <td class="tg-fymr">Conexiones de Polo 1</td>
  </tr>
  <tr>
    <td class="tg-fymr">2</td>
    <td class="tg-0pky">C1</td>
    <td class="tg-0pky">Terminal común de POLE1</td>
  </tr>
  <tr>
    <td class="tg-fymr">3</td>
    <td class="tg-0pky">NC1</td>
    <td class="tg-0pky">Terminal normalmente cerrado de POLE1</td>
  </tr>
  <tr>
    <td class="tg-fymr">4</td>
    <td class="tg-0pky">N/A 1</td>
    <td class="tg-ffme">Terminal normalmente abierta de POLE1</td>
  </tr>
  <tr>
    <td class="tg-fymr">CONEXIONES DE POLO2</td>
  </tr>
  <tr>
    <td class="tg-0pky">7</td>
    <td class="tg-0pky">C2</td>
    <td class="tg-0pky">Terminal común de POLE1</td>
  </tr>
  <tr>
    <td class="tg-0pky">6</td>
    <td class="tg-0pky">NC2</td>
    <td class="tg-0pky">Terminal normalmente cerrado de POLE2</td>
  </tr>
  <tr>
    <td class="tg-0pky">5</td>
    <td class="tg-0pky">N/A 2</td>
    <td class="tg-ffme">Terminal normalmente abierta de POLE2</td>
  </tr>
</tbody>
</table>

**Características y especificaciones**

Similar a la CONFIGURACIÓN DE PIN, el DPDT relay presenta cambios según el MODELO. Aquí estamos considerando HK19F como un modelo de relay estándar.
-Voltaje de la BOBINA del relay para encender: 12V.
-Corriente máxima permitida a través de cada pin POLE: 1A.
-Tiempo de funcionamiento (Tiempo que tarda cada POLO en moverse a la segunda posición después de encender la BOBINA): 6 ms.
-Tiempo de liberación (Tiempo que tarda cada POLO en volver a la posición inicial después de retirar la energía de la BOBINA): 4 ms.
-Carga máxima que puede manejar el relay: 60 vatios.
