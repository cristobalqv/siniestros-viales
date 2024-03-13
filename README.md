# Siniestros Viales en C.A.B.A. (2016-2021)


## INTRODUCCIÓN
En este proyecto, se nos solicita llevar a cabo un proyecto de análisis de datos para poder reducir las víctimas fatales de siniestros viales en la Ciudad Autónoma de Buenos Aires. Se dispone de un conjunto de datos que abarca homicidios en siniestros viales ocurridos en C.A.B.A. entre 2016 y 2021, con hojas de datos y diccionarios que servirán como guía con el objetivo de desarrollar un MVP, siguiendo unas pautas establecidas.

## PROCEDIMIENTO

#### *EXTRACCIÓN, TRANSFORMACIÓN Y CARGA DE DATOS*
Se aplicaron técnicas de extracción, transformación y carga (ETL) para procesar y limpiar los conjuntos de datos proporcionados, con la finalidad de facilitar las etapas posteriores del análisis.
- Archivo: [1 ETL.ipynb](https://github.com/cristobalqv/siniestros-viales/blob/main/1%20ETL.ipynb "1 ETL")

#### *ANÁLISIS EXPLORATORIO DE DATOS (EDA)*

Constó de un primer acercamiento o visualización de forma gráfica de los datos, los cuales presentan ciertas tendencias en algunas de sus variables.
- Archivo: [2 EDA.ipynb](https://github.com/cristobalqv/siniestros-viales/blob/main/2%20EDA.ipynb "2 EDA.ipynb")

[![EDA1](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA1.png "EDA1")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA1.png "EDA1")

[![EDA 2](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA2.png "EDA 2")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA2.png "EDA 2")

[![EDA 3](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA3.png "EDA 3")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/EDA3.png "EDA 3")

#### *DASHBOARD*
Contiene datos interesantes y variables que deben ser tomadas en cuenta a la hora de generar políticas o campañas que vayan en pos de reducir el número de víctimas fatales de accidentes de tránsito y mejorar la seguridad vial en C.A.B.A.
- Archivo: [Proyecto 2.pbix](https://github.com/cristobalqv/siniestros-viales/blob/main/Proyecto%202.pbix "Proyecto 2.pbix")

[![Dashboard homicidios](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/dashboard%20homicidios.png "Dashboard homicidios")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/dashboard%20homicidios.png "Dashboard homicidios")

[![Dashboard victimas](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/dashboard%20victimas.png "Dashboard victimas")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/dashboard%20victimas.png "Dashboard victimas")

#### *KPIs (Indicador Clave de Rendimiento)*
KPI 1: reducción de la tasa de homicidios en un 10% en los últimos 6 meses en comparación con la tasa del semestre anterior

KPI 2: reducción en accidentes mortales de motocicleta en un 7% en el último año con respecto al año anterior
[![KPI 1 y 2](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/kpi%201%20y%202.png "KPI 1 y 2")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/kpi%201%20y%202.png "KPI 1 y 2")



KPI 3: Disminución de un 10% de cantidad homicidios en avenidas de 2020 a 2021
[![KPI 3](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/kpi%203.png "KPI 3")](https://github.com/cristobalqv/siniestros-viales/blob/main/imagenes/kpi%203.png "KPI 3")


Estos KPIs se crearon con la finalidad de cuantificar y potenciar la seguridad vial en C.A.B.A., suministrando métricas esenciales para evaluar la eficacia y el rendimiento de las acciones de prevención y seguridad adoptadas

## CONCLUSIONES

1. La mayor cantidad de acusados por siniestros corresponden a autos, locomoción colectiva y transporte de cargas. Los grupos más afectados son motociclistas y peatones. Sin embargo, no se puede dictaminar como responsables al primer grupo de la totalidad de sucesos (Se necesita una perspectiva completa).

3. Temporalmente, se puede evidenciar una tendencia a la disminución de accidentes el año 2020 y posterior aumento el 2021, atribuible al confinamiento por la pandemia COVID-19. Sin embargo, no hay una clara tendencia si se omite este evento.

5. Se pueden proponer 2 rangos etarios con tendencia a ser víctimas de estos siniestros: 18-40 años y mayores de 60 años (¿mayor imprudencia? ¿menor capacidad de reacción?). 

7. Mayor conciencia y responsabilidad vial sumado a mayor cantidad de fiscalizaciones.

9. No existe información sobre rango etario ni sexo de los acusados. Para mejorar la comprensión de estos siniestros y generar políticas al respecto, esta información también debiera ser registrada.

## FUENTE DE DATOS
https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales
