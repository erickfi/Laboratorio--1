# Laboratorio--1
# Leyes de Kirchhoff
**Autores:** Figueroa Erick, León Jiphson, Viracucha William

# 1. Planteamiento del problema

En los dispositivos electrónicos podemos identificar principalmente dos factores esenciales dentro de su funcionamiento, la corriente y el voltaje, elementos que nos permiten analizar un circuito, al hablar de estos elementos nos estamos refiriendo a energía, y su análisis parte de la ley de la conservación de la energía, *la energía no se crea ni se destruye, se transforma.*

Un circuito es un sistema electrónico por el cuál fluye corriente y voltaje, elementos que dependen de como está armado el circuito, por este motivo, en un circuito, independientemente de los elementos que tenga, podemos distinguir nodos, punto de unión de dos o más elementos electrónicos, y mallas, parte del circuito que una intensidad recorre hasta volver al nodo del que salió.

Teniendo está noción básica aparecen las leyes de Kirchhoff, las cuáles nos permiten de forma analítica obtener los valores de las intensidades, corriente, y la caída de tensión, voltaje, en el circuito, pero, esto se realiza de forma ideal, es decir no se considera las posibles pérdidas de energía, las cuales pueden ser por varios factores como el material del que están hechos los elementos electrónicos del circuito.

Cabe de esperar que los valores medidos dentro de un laboratorio difieran de los analíticos, de esta manera surge la interrogante ¿En que medida varían los valores, analíticos y prácticos, de la caída de tensión y la intensidad de un circuito?, puesto que existen diversas unidades de medida para estas variables, se tomará como referencia las unidades del sistema internacional, siendo el voltio (V) para la caída de tensión y el amperio (A) para la intensidad, sin embargo, esta ultima dentro de electrónica es reducida a miliamperios (mA) ya que por lo general se trabaja con intensidades menores a 1 amperio.

Por otra parte, debemos tomar en cuenta el tipo de corriente a utilizar, puesto que la variación en su frecuencia es notoria los resultados pueden ser ambiguos, en vista que se trabajará con componentes electrónicos se utilizará una fuente de energía continua.

# 2. Objetivos

- Analizar y comparar los valores de caída de tensión e intensidad de un circuito obtenidos de forma analítica y por mediciones en un laboratorio.
- Explicar y demostrar experimentalmente la ley de Kirchhoff de voltajes y la ley de Kirchhoff de corrientes.
- Deducir y aplicar de forma práctica la relación entre leyes para el análisis de circuitos eléctricos.

# 3. Estado del Arte

Las recientes investigaciones que se han realizado acerca de las Leyes de Kirchhoff se han centrado en el ámbito experimental, industrial y educativo, están dirigidos a comprender la efectividad de su uso en la educación y a encontrar nuevas formas de enseñanza.
“Actividades experimentales para la enseñanza y aprendizaje del análisis de circuitos eléctricos”, de los autores José Serrano, Cesar Mora y Rubén Sánchez, realizado en el año 2016 y entregado en el año 2019, este se enfoca en los resultados didácticos que tiene la aplicación de métodos diferentes en la experimentación sobre las leyes de Kirchoff, esto en el aprendizaje de los estudiantes de ingeniería Mecatrónica de la Universidad Politécnica de Sinaloa.

“Modeling and Experiment of a V-Shaped Piezoelectric Energy Harvester” de Yue Zhao,Yi Qin,  Lei Guo,y Baoping Tang realizado en 2017, se enfoca en la aplicación de las leyes de Kirchoff en la piezoelectricidad, que es un generador a base de pulsaciones, esta investigación se realizó con experimentos en los laboratorios de trasmisión mecánica de  la Universidad Chongqing.

“Conducted electromagnetic interference: theoretical and experimental investigation” de Akram Gharbi y Othman Hasnaoui de 2017, es una investigación donde se analiza la interferencia electromagnética en conductores, en este se demuestra que se pueden aplicar las leyes de Kirchoff encontrar corrientes y voltajes en esta investigación, estos experimentos se realizaron en los laboratorios de la Universidad de Túnez. 

# 4. Marco Teórico

Un circuito eléctrico es la conexión de elementos electrónicos por el cuál circula una corriente, estos elementos se unen a través de sus terminales, y esta unión se conoce como nodo, de igual forma, esta conexión de elementos crea una ruta por el que circula la corriente, si la corriente circula de tal forma que regrese a su punto de partida se conoce como malla, por lo que podemos considerarlo como un circuito que forma una trayectoria cerrada.
En 1847 Gustav Kirchhoff postula dos leyes que permiten conocer de forma analítica los valores de la caída de tensión en los elementos del circuito, y la intensidad que circula por las trayectorias cerradas del mismo:

- Ley de Kirchhoff de Corrientes (LCK): *la suma de las corrientes que entran en un nodo, es igual a la suma de las corrientes que salen del mismo.* 
- Ley de Kirchhoff de Voltajes (LVK): La suma de las caídas de voltaje en una trayectoria cerrada, es igual a la suma de las elevaciones de voltaje en la misma.

Estas leyes se derivan fundamentalmente de otras dos leyes más generales, la Ley de Conservación de la Carga , y la Ley de Conservación de la Energía .
Ya que la matemática es el lenguaje de la naturaleza para expresarse, se debe cumplir en un circuito eléctrico las Leyes de Kirchhoff, independientemente del nodo o sentido en que se realicen las mediciones.

# 5. Diagramas
 - Circuito para análisis de Leyes de Kirchhoff
 
     ![](https://github.com/erickfi/Laboratorio--1/blob/master/img/diagrama-1.PNG)
     
 - Circuito realizado en tinkercad
 
 ![](https://github.com/erickfi/Laboratorio--1/blob/master/img/Leyes%20de%20kirchhoff-Tinkercad.png)
 
# 6. Tablas de Resultados
Tabla 1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito

|Variable|Valor calculado|Valor medido|
| ------------- | ------------- |-------------|
|V_R1   (V) |	2.054|	2.05|
|I_R1   (mA)	|2.054	|2.05|
|V_R2   (V)	|4.247	|4.25|				
|I_R2   (mA)	|1.089	|1.09|
|V_R3   (V)	|2.123	|2.12|
|I_R3   (mA)	|0.965	|0.96|
|V_R4   (V) 	|2.123|	2.12|
|I_R4   (mA) 	|0.965|	0.96|
|V_R5   (V)	|3.697	|3.7|
|I_R5   (mA)	|2.054	|2.05|

Tabla 2. Verificación de LVK

| Voltaje | Trayectoria   1 |        | Trayectoria 2 |        | Trayectoria 3 |        |
|---------|-----------------|--------|---------------|--------|---------------|--------|
|         | Calculado       | Medido | Calculado     | Medido | Calculado     | Medido |
| V_T   (V)  | 10              | 10     | 10            | 10     | 10            | 10     |
| V_R1  (V)  | -1.389          | -1.39  | -1.493        | -1.49  | 0             | 0      |
| V_R2  (V) | 0               | 0      | -5.823        | -5.82  | -4.698        | -4.7   |
| V_R3  (V) | -3.056          | -3.06  | 0             | 0      | -2.651        | -2.65  |
| V_R4  (V) | -3.056          | -3.06  | 0             | 0      | -2.651        | -2.65  |
| V_R5  (V) | -2.499          | -2.49  | -2.684        | -2.69  | 0             | 0      |
| ∑V    | 0               | 0      | 0             | 0      | 0             | 0      |

Tabla 3. Verificación LCK

| Corriente   | Nodo 1    |        | Nodo 2    |        | 
|-------------|-----------|--------|-----------|--------|
|             | Calculado | Medido | Calculado | Medido |
| I_R1   (mA) | 2.054     | 2.05   | 0         | 0      | 
| I_R2   (mA) | -1.089    | -1.09  | 1.089     | 1.9    | 
| I_R3   (mA) | -0.965    | 0.96   | 0.965     | 0.96   | 
| I_R4   (mA) | 0         | 0      | 0         | 0      | 
| I_R5   (mA) | 0         | 0      | -2.054    | -2.05  | 
| ∑I          | 0         | 0      | 0         | 0      | 

# 7. Conclusiones

- Luego de hacer las mediciones de las tres trayectorias cerradas, se comprueba que la sumatoria de las subidas de tensión es igual a las sumatorias de caída de tensión.
- En el nodo 1 y en el nodo 2 se comprueba que las corrientes que ingresan a un nodo son igual a las corrientes que salen del mismo, comprobando la LCK.
- Las leyes de Kirchhoff permiten conocer los valores de la intensidad y caída de tensión, sin embargo, es necesario usar la Ley de Ohm para relacionar ambas variables.
- Al usar las leyes de Kirchoff se obtiene un valor muy próximo al real, 2,05 frente a 2,054 debido a que materiales como las resistencias no entregan exactamente el valor que indica su código de color
# 8. Recomendaciones

 - Al realizar mediciones en el protoboard es necesario poner al multímetro en paralelo para medir caída de tensión y en serie para medir la intensidad, por este motivo no se debe conectar en la misma línea del protoboard para medir corrientes ya que estaría en paralelo, para ello conectamos un lado del multímetro al nodo y el otro al terminal del elemento que se encontrará en otra línea.
 
# 9. Cronograma

![](https://github.com/erickfi/Laboratorio--1/blob/master/img/Cronograma-Practica-1.PNG)

# 10. Bibliografía

- https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
- Gharbi, A., & Hasnaoui, O. (2017). Conducted electromagnetic interference: theoretical and experimental investigation. 
- https://electricidad.usal.es/Principal/Circuitos/Comentarios/Temas/LeyesKirchhoffYConservacion.pdf
- [5]	Zhao, Y., Qin, Y., Gou, L., & Tang, B. (2017). Modeling and Experiment of a V-Shaped Piezoelectric Energy Harvester. 

# 11. Anexos

- https://github.com/erickfi/Laboratorio--1/blob/master/Anexos/C%C3%A1lculos%20analiticos.pdf

