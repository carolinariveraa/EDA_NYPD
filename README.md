# EDA_NYPD

## Índice

1. [Descripción](#descripcion-del-proyecto)

3. [Dashboard Resumen](#)
4. [Análisis](#)
5. [Conclusiones](#conclusion)


## 1.  Descripción del proyecto y objetivo

Este proyecto tiene como objetivo analizar y reconocer patrones en la tasa de criminalidad en el distrito de Nueva York. 


### 2. Dashboard resumen 

En el Dashboard se observa un resumén de los datos obtenidos del NYPD en relación con variables de interés que podrían afectar al aumento de número de delitos.

![dashboard](./pics/dash.png)

## 3. Análisis 

Podría haber una variedad de razones por las cuales algunos distritos tuvieron tasas de arresto más altas que otros. Podría ser debido a factores como la densidad de población, el estatus socioeconómico, la presencia de diferentes negocios o industrias, o el desempeño de la aplicación de la ley local.

<details>
  <summary>Mapa de arrestos por distrito</summary>
  <br>

![dashboard](./pics/map.png)
</details>

<details>
  <summary>Precio de alquiler y venta por distrito</summary>
  <br>

A partir del grafico se observa que para todos los distritos se cumple que la relación entre el precio de venta de casas y la cantidad de arrestos es inversamente proporcional. Sin embargo, Manhattan rompe la regla.

<br>

![dashboard](./pics/house.png)
</details>

<details>
  <summary>Índice de empleabilidad por distrito</summary>
  <br>

  En esta hoja filtrando por el año se puede ver la tasa de empleabilidad, con esta comparativa se determina si la variable de empleo es relevante para el aumento de crimenes por distrito.
  Debido a la pandemia hubo un aumento de despidos en 2020 y aumentó la tasa de desempleabilidad esto produjó que el número de crimenes reportados fuese mayor respecto a 2019. 

  <br>

![dashboard](./pics/employ.png)
</details>

## 4. Conclusiones

 Los distritos con mayor densidad de población, como el Bronx y Brooklyn, tienden a tener un mayor número de arrestos. Además, existe una correlación inversa entre el precio de las viviendas y la tasa de arrestos en los distritos. A medida que aumenta el precio de las viviendas, tiende a disminuir la tasa de arrestos. Sin embargo, Manhattan parece ser una excepción a esta tendencia, posiblemente debido a áreas turísticas o concentración de negocios.

La tasa de empleo puede ser un factor relevante en el aumento de los delitos. Durante la pandemia, se observó un aumento en la tasa de desempleo, lo que coincidió con un aumento en el número de arrestos reportados. Esto sugiere que la falta de empleo y las dificultades económicas pueden contribuir al aumento de la criminalidad.