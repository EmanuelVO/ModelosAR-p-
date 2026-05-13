# ModelosAR-p-

1. Considera la información histórica diaria de precios para la empresa Walt Disney Company (cuya sigla bursátil es “DIS”) contenida en el sitio de Yahoo finance (http://finance.yahoo.com) para el periodo que va del 1 de Enero del 2023 al 31 de Marzo del 2023. Los modelos auto-regresivos AR(p).

2. Determina mediante la gráfica de Auto-Correlación Parcial y los estadísticos de Akaike y Bayesiano cuál sería el modelo auto-regresivo más adecuado para ajustar dicha serie de datos. Justifica claramente su respuesta mediante una base de entrenamiento del 70% de los datos.

<img width="505" height="380" alt="image" src="https://github.com/user-attachments/assets/d216bdbf-09b5-41cf-a661-3e2304488b48" />

Podemos observar los picos significativos hasta los rezagos 1-2. Después de ese punto, los valores caen dentro del intervalo de confianza (≈ 0). 

En este grafico el menor valor se observa en el orden 1. 

<img width="508" height="377" alt="image" src="https://github.com/user-attachments/assets/a620c5ee-f844-4818-87c3-098ea7e8e541" />

También en este grafico el menor valor se observa en el orden 1. En conclusión, el modelo AR(1) es el mejor para esta serie de datos. 

<img width="509" height="381" alt="image" src="https://github.com/user-attachments/assets/a51167ee-e18c-4252-bdd3-18aa4d64e3cc" />

3. Pronostica los precios diarios por acción para el mes de Abril del 2023, tanto de manera puntual como mediante un intervalo de confianza del 90%, a partir del resultado obtenido en el punto anterior, p.

4. Responde ¿Qué tan exactos cree usted que serán sus predicciones? Justifique mediante el uso de indicadores de bondad de ajuste.

De acuerdo con el rmse y el mape, el pronóstico se equivoca aproximadamente en ±5.86 unidades (dólares) y un 5.91% de las veces por lo que los resultados se pueden considerar bastante exactos.

5. Grafica los resultados del punto anterior,  distinguiendo claramente por colores cada grupo de datos empleados en su análisis.

<img width="985" height="268" alt="image" src="https://github.com/user-attachments/assets/7c2ab198-10e1-4ee8-9b95-584226998d76" />
