![cooltext419873221794762](https://user-images.githubusercontent.com/105949773/191843846-d7819cda-fb8b-4800-84f0-ee05438b4d98.png)

![cooltext419873040709470](https://user-images.githubusercontent.com/105949773/191843308-765b6758-d995-4f89-a7be-d4388dfcc248.png)

## Configuración de pines de relay DPDT

![descarga](https://user-images.githubusercontent.com/105949773/191850615-2d1b0bc3-b211-4337-9683-1a842a316555.jpg)

Generalmente tiene ocho pines. La salida de pines predeterminada del relay DPDT varía según el MODELO. Aquí estamos tomando el dispositivo HK19F-12V como modelo. La 
salida de pines de HK19F se muestra arriba. Para la configuración de pines de diferentes modelos de relay, consulte su hoja de datos.

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

![Cool Text - Bipolar Stepper Motor 419875295518691](https://user-images.githubusercontent.com/105949773/191849343-cd5600a2-a83d-47b9-b904-28e1388c8aef.png)

Los motores paso a paso se utilizan generalmente en una variedad de aplicaciones en las que se desea un control de posición preciso y no se justifica el costo o la 
complejidad de un sistema de control de retroalimentación. Aquí hay algunas aplicaciones donde los motores paso a paso se encuentran a menudo:

-Impresoras

-Maquinas CNC

-Impresoras 3D/máquinas de creación de prototipos (por ejemplo, RepRap)

-Cortadoras láser

-Máquinas de recoger y colocar

-Actuadores lineales

-Unidades de disco duro

### Ejemplo

 **Motor paso a paso: bipolar, 200 pasos/rev, 28 × 45 mm, 4,5 V, 0,67 A/fase**

![0J2282 600x480](https://user-images.githubusercontent.com/105949773/191850187-5adb2e5b-175e-4a59-9b32-840049211129.jpg)

Este motor paso a paso bipolar híbrido tiene un ángulo de paso de 1,8° (200 pasos/revolución). Cada fase consume 670 mA a 4,5 V, lo que permite un par de retención de
950 g-cm (13 oz-in). El motor tiene cuatro cables codificados por colores que terminan con conductores pelados: negro y verde se conectan a una bobina; rojo y azul se
conectan entre sí. 

### Especificaciones:

-Tamaño: 28 mm cuadrados × 45 mm, sin incluir el eje (NEMA 11)

-Peso: 140 g (5 onzas)

-Diámetro del eje: 5 mm “D”

-Pasos por revolución: 200

-Clasificación actual: 670 mA por bobina

-Tensión nominal: 4,5 V

-Resistencia: 6,8 Ω por bobina

-Par de sujeción: 950 g-cm (13 oz-in)

-Inductancia: 4,9 mH por bobina

-Longitud de la correa: 30 cm (12″)

-Eje de salida soportado por dos rodamientos de bolas
