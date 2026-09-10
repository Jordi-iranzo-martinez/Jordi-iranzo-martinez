El [Índice de Calidad del Aire](https://www.miteco.gob.es/es/calidad-y-evaluacion-ambiental/temas/atmosfera-y-calidad-del-aire/visualizacion-datos-calidad-del-aire/ica.html) (ICA) es una herramienta de información pública a través de una representación cartográfica en tiempo real ([en la web](https://ica.miteco.es/), [Android](https://play.google.com/store/apps/details?id=es.gob.ica) e [iOS](https://apps.apple.com/es/app/ica-%C3%ADndice-de-calidad-del-aire/id6503063828)), que permite traducir las concentraciones medidas medias de cinco contaminantes atmosféricos en seis escalas de calidad del aire por colores. 

*Su elaboración se realiza en por la [Orden TEC/351/2019](https://www.boe.es/buscar/act.php?id=BOE-A-2019-4494), en cumplimiento del [artículo 28.9 del Real Decreto 102/2011](https://www.boe.es/buscar/act.php?id=BOE-A-2011-1645#a28), siguiendo el [Índice de Calidad del Aire Europeo](https://airindex.eea.europa.eu/AQI/index.html) (EAQI),*

Los contaminantes atmosféricos so cinco:

- **Partículas en suspensión de 10 micrómetros** (PM10)
- **Partículas en suspensión de 2,5 micrómetros** (PM2,5)
- **Ozono troposférico** (O₃)
- **Dióxido de nitrógeno** (NO₂)
- **Dióxido de azufre** (SO₂)

Para mejor representatividad, las estaciones de medida deberán de ser de diferentes tipos:

- **Tráfico**
- **Industriales**
- **De fondo** (en zonas rurales para la medición de los contaminantes secundarios). 

El índice refleja el impacto potencial de la calidad del aire sobre la salud. Por este motivo, se le asigna la peor categoría en términos de calidad del aire de cualquiera de los contaminantes que se tienen en consideración para su estimación (datos medidos o derivados del modelo CAMS).

A cada estación se le asigna la peor categoría en términos de calidad del aire de cualquiera de los contaminantes, a través de mediciones o modelización por satélite a través del [Servicio de Vigilancia de la Atmósfera de Copernicus](https://atmosphere.copernicus.eu/) (CAMS).

- Medidos
- Modelización (CAMS)

| Contaminantes | Períodos de medición | modelizació           |
| ------------- | -------------------- | --------------------- |
| PM10          | 24 horas             | Método de diferencia  |
| PM2,5         | 24 horas             | Método de diferencia  |
| O₃            | 8 horas              | Método multiplicativo |
| NO₂           | 1 hora               | Método de diferencia  |
| SO₂           | 1 hora               | Sin modelización      |

La corrección es la diferencia media entre los valores medidos previamente y el valor modelizado por CAMS para la misma hora durante al menos 3 de los 4 días anteriores)

*En los casos en los que una estación no disponga de datos para algunos contaminantes, el índice se calcula con datos de al menos uno de ellos contaminante (para no excluir estaciones). Si no existan valores medidos para la misma hora durante 3 de los 4 días anteriores se comunicará como “sin datos”.*

Las categorías: 

- **Buena** (verde): calidad del aire satisfactoria
- **Razonablemente buena** (azul): calidad del aire aceptable, la contaminación no amenaza la salud
- **Regular** (amarillo): probablemente no afecte a la población general pero puede suponer un riesgo moderado para los grupos de riesgo
- **Desfavorable** (naranja): toda la población puede experimentar efectos negativos, más serio en grupos de riesgo.
- **Muy desfavorable** (rojo): emergencia seria de salud pública general
- **Extremadamente desfavorable** (morado): emergencia grave de la salud pública general


![[Pasted image 20260814224608.png]]

![[Pasted image 20260730220147.png]]

*Los valores de todos los contaminantes de la tabla están expresados en μg/m3

Las concentraciones que superen el valor del máximo mostrado en la categoría “extremadamente desfavorable” no se tienen en cuenta para el cálculo del índice, ya que se consideran erróneos.

| Categoría                   | Población general                                                                                                                                | Grupos de riesgo y personas sensibles                                                                                                                                                                                                                                         |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Buena                       | Normalidad                                                                                                                                       | Normalidad                                                                                                                                                                                                                                                                    |
| Razonablemente buena        | Normalidad                                                                                                                                       | Normalidad                                                                                                                                                                                                                                                                    |
| Regular                     | Normalidad<br><br>Atención si hay síntomas (irritación de garganta, falta de aire, fatiga, palpitaciones...)                                     | Consideración de reducción de actividades prolongadas y enérgicas al aire libre<br><br>Plan de medicación para personas con asma o enfermedades respiratorias<br><br>Posibles palpitaciones, dificultad para respirar y fatiga inusual en personas con enfermedades cardíacas |
| Desfavorable                | Consideración de reducción de actividades prolongadas y enérgicas al aire libre (en especial si hay tos, falta de aire o irritación de garganta) | Consideración de reducción de actividades al aire libre (todas) (posponerlas o realizarlas en interiores).<br><br>Seguir el plan de tratamiento médico.                                                                                                                       |
| Muy desfavorable            | Reducción de actividades al aire libre (todas) (posponerlas o realizarlas en interiores)                                                         | Reducción de actividades al aire libre (todas) (posponerlas o realizarlas en interiores).<br><br>Seguimiento del plan de tratamiento médico                                                                                                                                   |
| Extremadamente desfavorable | Reducción de actividades al aire libre (todas) (posponerlas o realizarlas en interiores)<br><br>Protección adecuada para trabajos al aire libre  | Evitar la estancia prolongada.<br><br>Seguimiento del plan de tratamiento médico<br><br>Servicio de urgencias si la salud empeora                                                                                                                                             |

![[inca_leyenda.png]]


El índice de calidad del aire accesible a través de la página web del Ministerio de Transición Ecológica y Reto Demográfico utiliza datos provisionales y no validados y muestra por defecto la situación de la última hora disponible. Los usuarios pueden seleccionar para su visualización cualquier hora específica del histórico almacenado en el visor (con un mínimo de 48 horas).

El índice se calcula para todas las estaciones de medida con datos de al menos un contaminante, pero las estaciones que no tienen los datos de todos los contaminantes, se muestran con un círculo traslúcido. Los puntos negros del índice indican estaciones para las que no se han recibido datos.

Los datos calculados por modelización irán seguidos de un asterisco.

![[espana_indice-nacional-calidad-aire.png]]


