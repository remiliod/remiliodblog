---
date: "2026-05-25"
draft: false
excerpt: República Dominicana Mapeada- Una serie sobre mapas y Sistemas de Información Geográfica (SIG) para explorar RD.
subtitle: ""
title: 	Mapa de Interrupciones Eléctricas en República Dominicana (2021-2024) - ¿Por qué y dónde se va la luz?

weight: 3
---
Los apagones se han convertido en una preocupación creciente en la República Dominicana, especialmente en un contexto de eventos climáticos cada vez más frecuentes y severos. En el área de concesión de EDENORTE, el número de interrupciones del servicio eléctrico pasó de 56,970 en 2021 a 118,726 en 2024, un aumento de aproximadamente 108 % en cuatro años. Aunque este incremento no puede atribuirse exclusivamente al clima, coincide con un cambio estructural en la política energética del país, caracterizado por la reducción de los apagones financieros y una mayor capacidad del sistema para suplir la demanda eléctrica. En este contexto, los datos plantean preguntas inevitables: ¿cuáles son las causas principales de esta tendencia?, ¿cuál es su patrón estacional? y ¿qué territorios están absorbiendo el mayor impacto?

## Distribución Eléctrica en República Dominicana

La distribución eléctrica pública en la República Dominicana está a cargo de tres empresas distribuidoras estatales regionales, conocidas como Empresas Distribuidoras de Electricidad (EDEs): EDENORTE, EDESUR y EDEESTE.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 1-Lineas De Distribucion MT en Republica Dominicana.png">
</div>

**Figura 1 -** _Mapa de Líneas de Distribución de Media Tensión (MT) en RD_ **Fuente:** _Microgrid Research Group (PUCMM) con datos de las EDEs \[1\]._

EDENORTE es la empresa distribuidora pública de electricidad con el área de concesión más extensa del país, suministrando energía eléctrica a 14 provincias del Cibao (aproximadamente el 45 % del territorio nacional) y a algunos asentamientos rurales en los límites de las provincias de Monte Plata, Elías Piña y San José de Ocoa.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 2 - Area de concesion EDENORTE.png">
</div>

**Figura 2 -** _Mapa de área de concesión de EDENORTE (2026). Fuente: EDENORTE \[2\]_

## Principales causas de interrupciones eléctricas en EDENORTE (2021-2024)

Entre 2021 y 2024, EDENORTE acumuló 354,081 interrupciones del servicio eléctrico en sus circuitos. Sin embargo, no todos los apagones son iguales, su impacto varía según la duración, siendo "críticas" aquellas que superan las dos y ocho horas. Un corte que se prolonga más allá de dos horas impacta directamente la productividad y la calidad de vida. Pero cuando la interrupción supera las ocho horas, deja de ser únicamente un problema operativo y se convierte en uno social: servicios esenciales como hospitales, sistemas de agua y telecomunicaciones pueden verse comprometidos, y las personas que dependen de equipos médicos eléctricos quedan en una situación especialmente vulnerable\[3\]. En este contexto, del total de interrupciones registradas en el período analizado, 29,449 superaron las dos horas de duración y 2,194 se extendieron por más de ocho horas (ver Tabla 1).

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Tabla 1 - Resumen anual de interrupciones eléctricas según duración (totales, 2h y 8h).png">
</div>

**Tabla 1** - Resumen anual de interrupciones eléctricas según duración (totales, >2h y >8h)

Los datos muestran que un número reducido de causas explica la mayor parte de las interrupciones cada año. Llama la atención que los llamados "disparos desconocidos", fallas transitorias que duran apenas segundos o fracciones de segundo, representen el 36.4% de los eventos, mientras que las "causas desconocidas" aportan otro 7.8%. En conjunto, casi la mitad de las interrupciones queda sin una trazabilidad clara. Esto no solo plantea preguntas sobre la naturaleza técnica de las fallas, sino también sobre la calidad y precisión de los registros operativos. A ello se suman las interrupciones provocadas por árboles y ramas sobre la línea (4.4%) y por labores de poda preventiva, que indica una vulnerabilidad persistente del sistema frente a la vegetación, especialmente en temporadas de lluvia y viento (ver figura 3).

Esta observación coincide con la experiencia internacional de numerosas empresas distribuidoras de electricidad, que de manera consistente identifican la vegetación como una de las principales causas de interrupciones en sus sistemas de distribución \[4\] y uno de los componentes más significativos dentro de los presupuestos de operación y mantenimiento \[5\].

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 3 - Diez principales causas de interrupción en EDENORTE.png">
</div>

**Figura 3 -** Diez principales causas de interrupción en EDENORTE \[_el 58.8% de los eventos se concentró en las diez causas más frecuentes, mientras que el 41.2% restante se distribuyó entre 157 categorías de menor incidencia_\]. Fuente: Elaboración propia basada en ""Enhancing Climate Shock Vulnerability Assessment with Energy Reliability: A Comprehensive Case Study of the Dominican Republic"

Cuando se examinan las interrupciones prolongadas, el panorama cambia según la duración. En los cortes que superan las ocho horas, los árboles y ramas sobre la línea encabezan la lista (25%), seguidos por correcciones en conductores de fase (20.1%) y postes rotos (17.1%), lo que refleja una combinación de exposición ambiental y debilidades estructurales. En las interrupciones mayores a dos horas, la poda preventiva se convierte en la causa individual más relevante (22%), mientras que los eventos asociados los árboles y ramas sobre la línea continúan figurando entre los más frecuentes (8.3%) de los no programados.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 4 - Diez principales causas de interrupción del servicio  8h (izquierda) y 2h (derecha).png">
</div>

**Figura 4 -** Diez principales causas de interrupción del servicio > 8h (izquierda) y >2h (derecha). Fuente: "Enhancing Climate Shock Vulnerability Assessment with Energy Reliability: A Comprehensive Case Study of the Dominican Republic

## Patrón estacional de interrupciones eléctricas en EDENORTE (2021-2024)


Al analizar el patrón estacional de las interrupciones, se observa que los apagones no se distribuyen de manera uniforme a lo largo del año ni del día. Entre junio y noviembre, periodo que coincide con la temporada ciclónica, se registra una mayor concentración de eventos (ver figura 5). También se identifica un aumento notable de interrupciones entre las 11:00 de la mañana y la 1:00 de la tarde, horas que coinciden con los picos de demanda energética. En otras palabras, los momentos de mayor consumo son también momentos de mayor vulnerabilidad operativa por la posible sobrecarga de los alimentadores.

Al examinar con mayor detalle las causas dentro de ese intervalo, predominan los llamados "disparos desconocidos", que representan entre un 26% y un 35% de los eventos registrados en esas horas. Les siguen fallas asociadas a pérdidas de tensión en alimentadores de 12.5 kV y actividades programadas como obras, podas o interconexiones de proyectos. Esto sugiere que la combinación entre alta demanda, condiciones climáticas adversas y trabajos en la red crea un escenario propenso a interrupciones.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 5 - Estacionalidad de Interrupciones.png">
</div>


**Figura 5 -** Gráfico de contorno de la cantidad de interrupciones en función de la hora de inicio y el mes (EDENORTE). **Nota:** El eje horizontal (x) representa los meses del año, mientras que el eje vertical izquierdo (y) indica la hora del día (formato de 24 horas) en que comenzaron las interrupciones. La intensidad del color en el mapa de calor se relaciona con la frecuencia de las interrupciones, donde los tonos más oscuros indican un mayor número de eventos. El segundo eje vertical, ubicado a la derecha, ofrece una representación cuantitativa del número de interrupciones (frecuencia).


Los días con mayor número de interrupciones coincidieron con episodios de condiciones meteorológicas severas y eventos climáticos extremos. En 2021, el valor más alto se registró el 7 de agosto (n = 535), asociado a los fuertes vientos generados por una onda tropical, seguido del 3 de julio (n = 516) durante el paso del huracán Elsa. En 2022, el sistema experimentó su punto más crítico con el huracán Fiona, que tocó tierra el 19 de septiembre y provocó 1,818 interrupciones en un solo día (ver Figura 6).

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 6 - Frecuencia diaria de interrupciones eléctricas con anotaciones para eventos pico (2021-2022).png">
</div>


**Figura 6 -** Frecuencia diaria de interrupciones eléctricas con anotaciones para eventos pico (2021-2022) (EDENORTE). **Nota:** Los diagramas de caja adjuntos resumen la distribución estadística diaria de las interrupciones, evidenciando la presencia de valores atípicos extremos.


Para 2023, el mayor registro ocurrió el 6 de abril (n = 805), nuevamente bajo la influencia de una onda tropical con vientos intensos. En 2024, los niveles más elevados se observaron el 14 de agosto (n = 891), vinculados al huracán Ernesto, y el 30 de octubre (n = 843), durante el impacto del huracán Beryl.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 7 - Frecuencia diaria de interrupciones eléctricas con anotaciones para eventos pico (2023-2024) (EDENORTE.png">
</div>


**Figura 7 -** Frecuencia diaria de interrupciones eléctricas con anotaciones para eventos pico (2023-2024) (EDENORTE). **Nota:** Los diagramas de caja adjuntos resumen la distribución estadística diaria de las interrupciones, evidenciando la presencia de valores atípicos extremos.

## Distribución espacial de interrupciones - Índice de Frecuencia Promedio de Interrupciones del Sistema de EDENORTE (2021-2024)

Más allá de cuándo ocurren las interrupciones, también es importante entender dónde se concentran. No obstante, no todos los circuitos eléctricos son iguales: algunos son más largos y atienden a más personas que otros. Por eso, comparar sus indicadores sin tomar en cuenta estas diferencias no ofrece una visión completa de la realidad. Para entender mejor cómo y dónde ocurren las interrupciones, se realizó un análisis geográfico de los circuitos de distribución de EDENORTE utilizando el índice SAIFI. Este indicador mide cuántas veces, en promedio, los usuarios experimentan apagones debido a fallas en el sistema, maniobras operativas o problemas en los equipos eléctricos. Cuando el valor de SAIFI es alto esto puede reflejar debilidades en la infraestructura, dificultades en la gestión del sistema o retos para detectar fallas y restablecer el servicio con rapidez.

El mapa de la Figura 8 muestra cómo se distribuye el índice SAIFI en el territorio atendido por EDENORTE. Para su representación geográfica, los circuitos fueron mapeados siguiendo su recorrido y asociados a la unidad territorial mínima disponible, el subbarrio. Los valores de SAIFI se agrupan en distintos rangos de frecuencia de interrupciones, cada uno representado con un color diferente, lo que permite distinguir las áreas con mejor desempeño de aquellas donde las interrupciones son más frecuentes. El análisis muestra que varios alimentadores de media tensión e interruptores telecontrolados (ITC) ubicados en las provincias de María Trinidad Sánchez, Monseñor Nouel, Sánchez Ramírez y Hermanas Mirabal presentan las frecuencias más altas de SAIFI.

<div align="center">
    <img src="/blog/RD-mapped/MapaDeInterrupciones/Figura 8 - Indice Promedio de Interrupciones del Sistema (SAIFI) en EDENORTE (2021-2024).png">
</div>


**Figura 8 - Índice Promedio de Interrupciones del Sistema (SAIFI) en EDENORTE (2021-2024). Fuente:** "Enhancing Climate Shock Vulnerability Assessment with Energy Reliability: A Comprehensive Case Study of the Dominican Republic


Para conocer con mayor detalle el recorrido y el alcance de estos circuitos, el lector puede consultar la sección metodológica de la referencia \[6\]


## En palabras llanas

Los apagones no son inevitables. Son, en gran medida, el reflejo de decisiones de planificación, inversión y gestión que pueden tomarse mejor. **Un servicio eléctrico confiable es una de las marcas distintivas de una sociedad competitiva**. En un país cuya economía depende en gran medida del sector servicios, fortalecer la resiliencia del sistema eléctrico es una condición esencial para el desarrollo económico y el bienestar social. A partir de este análisis, tres prioridades resultan evidentes: mejorar la trazabilidad de las fallas para reducir la alta proporción de eventos clasificados como "causas desconocidas"; fortalecer la gestión preventiva de la vegetación en los circuitos con mayor frecuencia de interrupciones; y priorizar inversiones en los alimentadores con mayor índice de interrupciones (SAIFI), especialmente en aquellos que abastecen territorios más vulnerables.

Los datos de esta publicación se basan en el estudio titulado _"Enhancing Climate Shock Vulnerability Assessment with Energy Reliability: A Comprehensive Case Study of the Dominican Republic"\[6\]_, en el cual se integraron datos de fiabilidad energética, a través del Índice de Frecuencia Promedio de Interrupciones del Sistema (SAIFI) de EDENORTE, con el Índice de Vulnerabilidad ante Choques Climáticos (IVACC), un indicador que estima la vulnerabilidad de los hogares dominicanos frente a fenómenos climáticos. Esta integración permitió construir una medida compuesta que incorpora tanto la exposición social como la confiabilidad del suministro eléctrico, con el objetivo de identificar territorios donde la fragilidad energética y la vulnerabilidad climática convergen \[7\].


---

El autor es investigador en Resiliencia Enérgetica y Microrredes Eléctricas (PUCMM) y Especialista en Energía (Energía Journal).

- **Contacto:**  Resiliencia Energética y Microrredes (PUCMM)| [r.dejesus@ce.pucmm.edu.do](mailto:r.dejesus@ce.pucmm.edu.do)
 (PUCMM)| [https://microgrid.pucmm.edu.do/](https://microgrid.pucmm.edu.do/)
- **Energía Journal**  | energiajournalrd@gmail.com |  **Instagram:**  @energiajournal


**Recursos**

\[1\] R. E. De Jesús-Grullón, "Mapa de Líneas de Distribución de Media Tensión (MT) en RD- Cobertura regional y desafíos en la gestión | Blog." Accessed: Mar. 02, 2026. \[Online\]. Available: <https://remildejesus.xyz/blog/rd-mapped/lineasdedistribucion/>

\[2\] "MAPA DE CONCESIÓN DE EDENORTE - Edenorte Dominicana." Accessed: Mar. 02, 2026. \[Online\]. Available: <https://edenorte.com.do/historia/mapa-sectores_edenorte_mapa/>

\[3\] Listin Diario, "Investigación Pucmm revela necesidad de estudios avanzados en sistema eléctrico." Accessed: Mar. 03, 2026. \[Online\]. Available: <https://listindiario.com/la-republica/ciudad/20260225/investigacion-pucmm-revela-necesidad-estudios-avanzados-sistema-electrico_895442.html>

\[4\] M. Doostan, R. Sohrabi, and B. Chowdhury, "A data-driven approach for predicting vegetation-related outages in power distribution systems," _International Transactions on Electrical Energy Systems_, vol. 30, no. 1, p. e12154, Jan. 2020, doi: 10.1002/2050-7038.12154.

\[5\] P. J. Appelt and J. W. Goodfellow, "Research on how trees cause interruptions - applications to vegetation management," in _Rural Electric Power Conference, 2004_, IEEE, pp. C6-1-10. doi: 10.1109/REPCON.2004.1307064.

\[6\] R. E. De-Jesús-Grullón, R. O. Batista Jorge, O. A. López, and D. Nicodemo, "Enhancing Climate Shock Vulnerability Assessment with Energy Reliability: A Comprehensive Case Study of the Dominican Republic," StoryMap. Accessed: Mar. 03, 2026. \[Online\]. Available: <https://storymaps.arcgis.com/stories/26a2c1630ca2409c8c803805fa147340>

\[7\] R. E. De-Jesús-Grullón, R. O. Batista Jorge, O. A. López, and D. Nicodemo, "Enhancing Climate Shock Vulnerability Assessment with energy reliability: A comprehensive case study of the Dominican Republic," _International Journal of Disaster Risk Reduction_, vol. 136, p. 105994, Apr. 2026, doi: 10.1016/j.ijdrr.2026.105994.

\[8\] R. E. De-Jesús-Grullón, R. O. Batista Jorge, A. Espinal Serrata, J. E. Bueno Díaz, J. J. Pichardo Estévez, and N. F. Guerrero-Rodríguez, "Modeling and Simulation of Distribution Networks with High Renewable Penetration in Open-Source Software: QGIS and OpenDSS," _Energies (Basel)._, vol. 17, no. 12, p. 2925, Jun. 2024, doi: 10.3390/en17122925.

&nbsp;
