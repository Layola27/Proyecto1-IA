# Análisis del Conjunto de Datos de Precios de Aguacate

## Descripción del Proyecto
✨✨✨ Este proyecto explora el mercado del aguacate en los Estados Unidos utilizando datos históricos. El objetivo principal es identificar tendencias, analizar patrones estacionales y regionales, y comprender la evolución de los precios y volúmenes de venta. Además, se busca preparar el conjunto de datos para posibles aplicaciones en modelado predictivo y aprendizaje automático. ✨✨✨

## Características del Proyecto
El proyecto está diseñado para:
- Realizar un análisis exploratorio de datos (EDA) para limpiar y preparar los datos.
- Identificar tendencias de precios y volúmenes de ventas a lo largo del tiempo.
- Comparar las diferencias entre tipos de aguacate (convencionales y orgánicos) y regiones geográficas.
- Visualizar resultados clave a través de gráficas y tablas.
- Proveer código reutilizable en Python para la generación de análisis y gráficas.

## Datos Utilizados
✨✨✨ El conjunto de datos incluye las siguientes columnas clave: ✨✨✨
- **Date**: Fecha de la observación.
- **AveragePrice**: Precio promedio de un aguacate por unidad.
- **Total Volume**: Volumen total de aguacates vendidos.
- **Type**: Tipo de aguacate (convencional u orgánico).
- **Region**: Región donde se registró la observación.
- Otras columnas relacionadas con subcategorías de volúmen de ventas y números de bolsas.

## Flujo del Proyecto
1. **Carga y Limpieza de Datos**: Se procesan los datos para manejar valores nulos, duplicados y formatos inconsistentes.
2. **Exploración Inicial**: Gráficas básicas para identificar patrones generales.
3. **Análisis Temporal**: Estudio de precios promedio y volúmenes a lo largo del tiempo, con especial énfasis en estacionalidad.
4. **Análisis Regional**: Comparación de patrones entre regiones de EE. UU.
5. **Análisis Comparativo**: Evaluación de diferencias entre tipos de aguacates.
6. **Visualizaciones Avanzadas**: Generación de gráficas para comunicar hallazgos clave.

## Tecnologías y Librerías Utilizadas
✨✨✨ - **Python**: Lenguaje principal para el desarrollo del proyecto.
- **Pandas**: Manejo y transformación de datos.
- **Matplotlib y Seaborn**: Visualización de datos.
- **Statsmodels**: Análisis de series temporales.
- **Jupyter/Google Colab**: Entorno de desarrollo interactivo. ✨✨✨

## Resultados Esperados
✨✨✨ El proyecto genera: ✨✨✨
- Gráficas claras y detalladas que ilustran tendencias clave.
- Resúmenes analíticos de precios, volúmenes y diferencias entre regiones.
- Datos limpios y listos para aplicación en modelos predictivos.

## Contribuciones
✨✨✨ Este proyecto está abierto a contribuciones. Si tienes ideas o mejoras, siéntete libre de crear un pull request o reportar problemas. ✨✨✨

## Licencia
✨✨✨ Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más información. ✨✨✨

## Contacto
✨✨✨ Si tienes preguntas o sugerencias, no dudes en contactarme a través de glayolacvs@gmail.com. ✨✨✨


## Graficos
Analisis de series temporales: 
#1.1
Grafico deTendencia de los precios del aguacate 
![image](https://github.com/user-attachments/assets/f47d28d4-c397-4a02-b212-64674724340d)

Grafico deTendencia de los precios del aguacate usando regresión lineal simple.
![image](https://github.com/user-attachments/assets/90778019-76bc-49fe-bcc4-3d3ff4a7cec8)

Grafico evolución del volumen total en los aguacates ogránicos:
![image](https://github.com/user-attachments/assets/93c2d503-9810-4a35-8b71-32252d76c835)

Grafico evolución del volumen total en los aguacates convecionales:
![image](https://github.com/user-attachments/assets/b0b6949f-05e6-4385-9673-64c09a80ca97)

#Relación entre los gráficos
Precio y Volumen:

El incremento en los precios promedio (Gráfico 1) podría explicarse parcialmente por el aumento de la demanda de aguacates, especialmente los orgánicos (Gráfico 2). Esto indica una tendencia de consumo hacia productos más saludables y premium.
Los picos y caídas en los precios coinciden con fluctuaciones en los volúmenes de ventas, evidenciando la relación entre oferta y demanda.
Orgánicos vs. Convencionales:

El volumen de ventas orgánico (Gráfico 2) muestra un crecimiento constante, lo que sugiere una preferencia creciente de los consumidores hacia los aguacates orgánicos.
En contraste, las ventas de aguacates convencionales (Gráfico 3) son más irregulares, aunque aún dominan en volumen total.
Conclusión Global:

Los datos sugieren una transición en la preferencia del mercado: los aguacates orgánicos están ganando participación, lo que impacta en los precios generales al aumentar la demanda.
El mercado de aguacates presenta una tendencia de crecimiento, tanto en precios como en volumen, con un énfasis notable en productos orgánicos.

#1.2
Precio promedio en regiones con cohortes geograficas (situación geográfica):
-Costa Este
![image](https://github.com/user-attachments/assets/aeb95d15-02cf-441a-850a-059722f51d8f)
-Costa Oeste
![image](https://github.com/user-attachments/assets/71bd7ec6-125b-4cec-acfd-710da301d9ad)
-Sur
![image](https://github.com/user-attachments/assets/6b7b191c-012d-4c02-aae5-616f06841382)
-Centro/Norte
![image](https://github.com/user-attachments/assets/7f08dc64-fd9a-45d5-a1a0-e38d96a557b6)

Costa Este:

Alta variabilidad en los precios, especialmente en Albany, Philadelphia y New York, posiblemente por fluctuaciones en oferta y demanda.
Picos significativos hacia finales de 2017 y principios de 2018, probablemente por estacionalidad o cambios en la oferta.
Costa Oeste:

Comportamiento más estable en regiones como California, Los Ángeles y San Francisco, reflejando un mercado más consolidado.
Estacionalidad marcada, con aumentos hacia finales de cada año, indicando un patrón cíclico predecible.
Sur:

Grandes fluctuaciones, con aumentos pronunciados hacia finales de 2017 y caídas en 2018, posiblemente ligadas a la oferta y demanda.
Picos y caídas extremos, vinculados a factores como la temporada de cosecha o problemas de suministro local.
Centro/Norte:

Menor volatilidad, con precios más estables en regiones como Chicago, Indianapolis y Detroit.
Leves fluctuaciones, probablemente influenciadas por el clima o factores de transporte.
Conclusiones generales:

Variabilidad geográfica: Las regiones del sur y la costa este son más volátiles, mientras que la costa oeste y el centro/norte presentan mayor estabilidad.
Estacionalidad: Todas las regiones muestran patrones cíclicos, con picos hacia finales de año, influenciados por la oferta y demanda estacional.
Impacto de la localización: Regiones con mercados consolidados (como California) tienen menos volatilidad, mientras que mercados más pequeños (como Albany) presentan mayor variabilidad, posiblemente por problemas de transporte y menor disponibilidad.

Precio promedio en regiones con cohortes geograficas (tamaño región):

Grandes Ciudades: 
![image](https://github.com/user-attachments/assets/02ee3c9a-3fdc-456c-94c1-c8818121ce90)

Ciudades Medianas: 
![image](https://github.com/user-attachments/assets/faa0aa0d-8a2d-46a4-b17a-d4620138ad7e)

Ciudades Pequeñas:
![image](https://github.com/user-attachments/assets/92427de8-d45c-447a-9ece-29b8037a7fb2)

Resumen del análisis de precios por tamaño de ciudades:

Grandes ciudades (New York, Los Angeles, Chicago, Houston, Dallas):

Tendencia estable: Menos volatilidad en comparación con regiones pequeñas o medianas.
Estacionalidad clara: Incrementos hacia finales de 2017 seguidos de caídas en 2018, posiblemente debido a alta demanda o fluctuaciones en la oferta.
Mercados consolidados: Ciudades como Chicago y Los Angeles reflejan precios más estables y predecibles.
Ciudades medianamente grandes (Seattle, Phoenix, Detroit, Cleveland):

Mayor fluctuación que las grandes ciudades, con picos y caídas más abruptos, especialmente en 2017.
Comportamiento menos predecible, con estacionalidad menos evidente.
Mercados moderadamente consolidados, afectados por factores externos.
Ciudades pequeñas (Albany, Boise, BuffaloRochester, Las Vegas, Columbus):

Alta volatilidad en los precios debido a mercados menos consolidados y mayor sensibilidad a factores externos como clima o oferta local.
Picos extremos, seguidos de caídas drásticas.
Mayor sensibilidad a cambios en la oferta y demanda, reflejando mercados más vulnerables.
Comparativa y conclusiones:

Estabilidad vs. volatilidad:
Grandes ciudades presentan precios más estables, indicando mercados bien establecidos.
Ciudades medianas y pequeñas muestran mayor volatilidad, con mercados más influenciados por factores locales o externos.
Tendencia general: Todas las ciudades registraron un aumento en los precios hacia finales de 2017, posiblemente por factores globales o nacionales.
Conclusión final:
Grandes ciudades: Más estabilidad y previsibilidad.
Ciudades medianas: Moderada volatilidad, mercados menos predecibles.
Ciudades pequeñas: Máxima volatilidad, influenciadas por mercados locales más débiles.

#1.4
Tendencias de venta de aguacates Con outliers:

![image](https://github.com/user-attachments/assets/e61ba441-eb2d-4633-b82b-fc84ae876a93)

Tendencias de venta de aguacates Sin outliers: 

![image](https://github.com/user-attachments/assets/277ab081-35ed-465d-ac5c-6a845df4a974)

Umbral y Eliminación de Outliers:
En el código, el umbral se define como 3 desviaciones estándar.

Esto significa que cualquier valor de Total Volume que esté más allá de 3 desviaciones estándar por encima o por debajo de la media se considera un outlier (valor atípico).

#1.5
Analisis de cambios en precion anuales de aguacates:

![image](https://github.com/user-attachments/assets/7fc98854-3482-40e7-95bf-be58c2b62f4e)

Primeros tres meses de cada año:

![image](https://github.com/user-attachments/assets/b0fd9a24-cf8d-4a3d-9707-f956cc907396)

Usando regresión Lineal: 

![image](https://github.com/user-attachments/assets/a7e1bc5a-fc30-429f-a979-ee01f9b76ac5)

Error Absoluto Medio (MAE): 0.0552
Interpretación del MAE: Bajo Error Absoluto:

Un MAE de 0.0552 significa que, en promedio, la diferencia entre los valores reales y las predicciones es de aproximadamente 0.055 dólares (5.52 centavos). Este nivel de error es insignificante en el contexto de los precios promedio de aguacates, que oscilan entre 1.2 y 1.5 dólares. Consistencia con Datos Reales:

Este bajo error valida que las estimaciones para los meses faltantes de 2018 (abril a diciembre) son consistentes con los patrones históricos.

#2.1
Distribución del Volumen de ventas por región (Top 10 sin TotalUS):
![image](https://github.com/user-attachments/assets/0eef2df8-de27-4f8c-9642-19d601d3cf92)

California domina el mercado de aguacates tanto en volumen total como en la variabilidad de las ventas, lo que refuerza su posición como el principal estado productor y consumidor de aguacates en EE. UU. El Oeste y otras regiones urbanas también reflejan un mercado fuerte, con alta demanda y volúmenes consistentes. Regiones menos densamente pobladas, como Plains, muestran un mercado más pequeño, posiblemente debido a factores como menor acceso, demanda o disponibilidad. Variabilidad en las ventas: Algunas regiones muestran fluctuaciones más amplias, lo que podría ser un área interesante para investigar patrones estacionales o eventos que impactan la oferta/demanda.

Posibles Factores de Influencia Producción Local: Las regiones con alta producción, como California, tienden a tener mayores volúmenes debido a su proximidad a los mercados locales. Demanda del Mercado: Las regiones como el Oeste y Southeast, con grandes centros urbanos, reflejan una alta demanda constante de aguacates. Acceso a los Productos: Regiones más alejadas de los centros de producción, como Plains, tienen menores volúmenes debido a la logística y posibles costos elevados.

#2.2
Comparación de precios promedio de Aguacates entre Años:
![image](https://github.com/user-attachments/assets/afb43186-b4d8-46de-a35f-00dfd2ce27c3)

Comparación sin outliers
![image](https://github.com/user-attachments/assets/dc3ecf1f-90ff-40a5-ae62-0aa3a66eae1a)

Q1 = data['AveragePrice'].quantile(0.25)
Q3 = data['AveragePrice'].quantile(0.75)
IQR = Q3 - Q1

Filtrar los outliers fuera del rango [Q1 - 1.5 * IQR, Q3 + 1.5 * IQR] IQR =Rango Intercuartilico(=Diferencia Q3 y Q1)
filtered_data = data[(data['AveragePrice'] >= (Q1 - 1.5 * IQR)) & (data['AveragePrice'] <= (Q3 + 1.5 * IQR))]

Conclusión y Gráfico:
Al eliminar los outliers:

El gráfico de boxplot (diagrama de caja) muestra los precios promedio de aguacates entre años de forma más clara y representativa.
Se eliminan valores extremos que podrían "engañar" visualmente al hacer parecer que los datos son más dispersos de lo que realmente son.
En el gráfico resultante:

Se puede ver cómo cambian los precios promedio año tras año.
La eliminación de outliers permite comparar los datos de forma justa y precisa, enfocándose solo en los precios típicos y descartando valores anormales.

Grafica de tendencia de precios con regresión polinómica de grado 3:
![image](https://github.com/user-attachments/assets/0ac66e44-dd9e-42e8-89cb-52443f926768)

Esta gráfica muestra la tendencia de precios promedio mensuales con datos históricos y predicciones mejoradas para los meses faltantes:

Datos históricos (línea azul): Representan los precios promedio registrados hasta el mes 12.
Predicciones mejoradas (línea naranja): Se extienden desde el mes 13 en adelante, calculadas con una función sinusoidal ajustada a los datos históricos para capturar la estacionalidad.
Inicio de predicciones (línea roja punteada): Marca la transición entre los datos históricos y las predicciones.
La gráfica combina una transformación polinómica y un ajuste estacional sinusoidal para modelar y predecir con mayor precisión las fluctuaciones cíclicas de los precios.

#2.3
Distribución del Volumen total de ventas
![image](https://github.com/user-attachments/assets/2cd69f35-edb4-4bd4-8389-e67614f9d247)

Conclusiones La distribución de ventas es altamente asimétrica: Volúmenes pequeños predominan en la mayoría de los registros. Hay valores atípicos (outliers) en los volúmenes más altos, lo cual afecta la media. La mediana es un mejor indicador del volumen típico, ya que no está afectada por los valores extremos. Este análisis sugiere que las ventas de aguacates están dominadas por muchas transacciones pequeñas, con pocas pero significativas ventas grandes. Si deseas analizar más a fondo:

Podríamos segmentar por región o tipo de aguacate. Analizar los valores extremos en detalle.

#2.4
Comparación de ventas por tipo de bolsa:
![image](https://github.com/user-attachments/assets/4f2fe28e-7540-43cd-8f34-82e6d1e21423)
Comparación de ventas por tipo de bolsa y tipo de aguacate:
![image](https://github.com/user-attachments/assets/5eb69922-07e4-45b3-9ccc-f54d99b38840)

Dominio de los Aguacates Convencionales:

Las ventas de aguacates convencionales superan por un amplio margen a las de aguacates orgánicos. Representan casi la totalidad del volumen de ventas, con un total superior a 3 mil millones de unidades. Distribución por Tipo de Bolsa:

Small Bags: Son el tipo de bolsa más vendido, especialmente para los aguacates convencionales, con un volumen cercano a los 3 mil millones. También son el tipo dominante en aguacates orgánicos, aunque con un volumen significativamente menor. Large Bags: Representan la segunda opción más vendida, con aproximadamente 900 millones de unidades para los aguacates convencionales. Las ventas en orgánicos son aún menores, pero existen en proporción relativa. XLarge Bags: Tienen una participación mínima en ambos tipos de aguacates. La demanda para este formato es prácticamente insignificante en comparación con las otras dos opciones. Comparación entre Convencionales y Orgánicos:

Convencionales: Representan la mayor proporción de ventas en todas las categorías de bolsas. Orgánicos: Aunque existen, sus volúmenes son muy bajos y se concentran principalmente en Small Bags.

#3.5
Relación entre precio promedio y volumen total de ventas:
![image](https://github.com/user-attachments/assets/83592bd9-cb28-4705-a95f-1f12cb9dad0e)

Análisis del Output Mejorado

Relación No Lineal Entre Precio Promedio y Volumen de Ventas La tendencia no lineal representada por la curva roja muestra una relación decreciente entre el Precio Promedio (AveragePrice) y el Volumen Total de Ventas. Este ajuste captura mejor la naturaleza de los datos, destacando que: A medida que aumenta el precio, el volumen de ventas tiende a disminuir significativamente. Sin embargo, la pendiente de la curva es más pronunciada al inicio (precios bajos), lo que indica una alta sensibilidad de la demanda en rangos de precios bajos. A precios más altos (mayores a 2.0), el volumen se estabiliza cerca de cero, indicando que la demanda cae a niveles muy bajos.
Mejoras en el Gráfico La inclusión de una regresión no lineal proporciona una representación más realista de la relación. El ajuste polinómico logra capturar la caída progresiva del volumen a medida que aumenta el precio promedio. La nube de puntos sigue mostrando alta dispersión en precios bajos, lo cual podría estar influenciado por: Segmentación del mercado: Diferentes regiones o tipos de aguacates responden de manera desigual a los cambios en precio. Temporada: La estacionalidad puede impactar el comportamiento del consumidor en precios bajos.

#4.1
Grafico precio promedio y volumen total: 
![image](https://github.com/user-attachments/assets/d0534ce5-346d-4a84-b880-8ce3b5befe56)

Relación Inversa:

La relación negativa entre precios promedios y volumen total suavizado sugiere que mayores niveles de oferta (más volumen de ventas) tienden a presionar los precios a la baja, posiblemente debido a un aumento en la disponibilidad. Picos Importantes:

Volumen más alto: Ocurre en 2017-Q3. Precio promedio más alto: Alrededor de 2017-Q4, coincidiendo con una caída en el volumen total. Suavización de Datos:

La técnica de promedio móvil ayuda a eliminar ruido, facilitando la identificación de patrones en los datos.

Gráfico por region: 
![image](https://github.com/user-attachments/assets/9812d0d8-0b55-4954-96ad-8f31ccee5ef1)

La región Northeast mantiene precios promedio superiores en la mayoría de los trimestres, con un pico notable en 2017 Q3. California experimenta un aumento en los precios en 2017 Q3, coincidiendo con una caída en volúmenes (posible escasez de oferta o demanda elevada). West y SouthCentral muestran precios más bajos y estables, reflejando posiblemente un mercado más competitivo. Análisis:

Las diferencias en los precios promedio pueden estar relacionadas con: Elasticidad precio-demanda en cada región. Costos logísticos y oferta disponible localmente. Es interesante notar que los picos de precios no siempre coinciden con una caída drástica en ventas, lo que sugiere una demanda inelástica en algunas regiones.

Grafico de elasticidad: 
![image](https://github.com/user-attachments/assets/2a68a71c-fac8-4dd5-9bcf-f2184f8ad5cf)

Elasticidad y Precios: El primer gráfico mide la sensibilidad de la demanda al precio, mientras que el segundo gráfico muestra las tendencias de precios promedio a lo largo del tiempo por región.
Regiones con alta elasticidad negativa (como Northeast) tienen precios más altos en el segundo gráfico, lo cual respalda la teoría de que estas regiones son más sensibles a los aumentos de precio.
Regiones con elasticidad positiva o baja (GreatLakes y Plains) muestran una menor respuesta de la demanda a variaciones en el precio.


#4.5
Evolución de retención de ventas:
![image](https://github.com/user-attachments/assets/41f432ef-688d-4398-b940-4e1daef3407b)

Tasa de Retención (%) (línea azul):

Se observan fluctuaciones significativas en la tasa de retención.
Algunos periodos muestran picos muy pronunciados (160.9% en 2016-Q4) y valles mínimos (71.2% en 2017-Q3).
Tendencia Suavizada (línea roja punteada):

Utiliza una media móvil de 3 periodos para eliminar ruido y mostrar la tendencia general.
La tendencia suavizada permite identificar una caída general entre 2015 y 2016, seguida de una recuperación moderada a partir de finales de 2016.
Puntos Destacados:

Pico Máximo (160.9%): Ocurre en 2016-Q4, posiblemente relacionado con un aumento temporal en las ventas.
Valle Mínimo (71.2%): En 2017-Q3, indicando una caída drástica en la retención.

#5.1
Matriz de correlación entre variables númericas:
![image](https://github.com/user-attachments/assets/2df5217b-4f39-448e-8409-7612dda1e863)

Relaciones más Significativas Total Volume y 4046, 4225, 4770, Total Bags:

Total Volume tiene altas correlaciones positivas con las demás variables (4046: 0.98, 4225: 0.97, 4770: 0.87, Total Bags: 0.96). Interpretación: Dado que Total Volume es el volumen total vendido, no es sorprendente que esté directamente relacionado con el volumen de aguacates en cada categoría de tamaño. AveragePrice y las demás variables:

La correlación de AveragePrice con otras variables es débil y negativa: Total Volume: -0.19 4046: -0.21 4225: -0.17 4770: -0.18 Total Bags: -0.18 Interpretación: El precio promedio (AveragePrice) tiene una ligera correlación inversa con las ventas en volumen y tamaño. Es posible que cuando el volumen de ventas aumenta, el precio disminuye debido a una mayor oferta. Relación entre las categorías de tamaño (4046, 4225, 4770) y Total Bags:

4046, 4225, 4770 tienen correlaciones positivas fuertes con Total Bags (0.93, 0.91 y 0.79 respectivamente). Interpretación: Total Bags es la suma de bolsas pequeñas, grandes y extra grandes, por lo que estas relaciones son esperadas y significativas. Correlación con year:

year tiene correlaciones muy cercanas a 0 con todas las demás variables. Interpretación: No parece haber una tendencia clara de las variables numéricas con respecto al tiempo.

5.2
Analisis de dispersión PRECIO PROMEDIO - VOLUMEN TOTAL:
![image](https://github.com/user-attachments/assets/7b2ce1b8-a30c-4bc9-9ed7-a9feb9e87b04)

Descripción del Gráfico El gráfico muestra:

Datos en dispersión: Representan la relación entre el precio promedio (AveragePrice) y el volumen total (Total Volume). Líneas de ajuste: Regresión lineal (en rojo): Representa una relación lineal entre las variables. Regresión polinómica de grado 2 (en verde): Captura posibles curvaturas y relaciones no lineales.

Observaciones Clave Tendencia General:
Existe una relación negativa entre AveragePrice y Total Volume, es decir, a medida que el precio promedio disminuye, el volumen total de ventas tiende a aumentar. Esto coincide con la ley de oferta y demanda: precios más bajos impulsan mayores ventas. Ajuste Lineal vs. Polinómico:

La línea de regresión lineal muestra una pendiente negativa constante que refleja la tendencia general decreciente. La línea de regresión polinómica (grado 2) presenta una ligera curvatura que sugiere una relación no lineal, capturando mejor la variabilidad de los datos en comparación con la línea recta. Sin embargo, la curvatura es suave, lo que sugiere que un modelo lineal puede ser suficiente para describir esta relación. Dispersiones:

Los puntos de dispersión muestran una distribución dispersa, lo cual indica que aunque existe una tendencia general, la correlación entre AveragePrice y Total Volume es débil. Esto se alinea con la baja correlación (≈ -0.19) observada anteriormente en la matriz de correlación.

#5.3 

![image](https://github.com/user-attachments/assets/175bbde4-2590-4db1-99ec-65842b4de8d9)

El gráfico muestra:

Valores Reales (línea naranja) vs Regresión Lineal Mejorada (línea verde punteada). Las predicciones están ajustadas trimestralmente con tres modelos: Regresión Lineal: RMSE = 58,971,977.17, R² = 0.73. Polinómico Grado 2: RMSE = 77,564,358.96, R² = 0.37. Polinómico Grado 3: RMSE = 78,947,227.69, R² = 0.35. Análisis del Resultado: Regresión Lineal:

Tiene el mejor rendimiento con R² = 0.73, mostrando un ajuste adecuado al patrón de los datos reales. El error RMSE es bajo comparado con los modelos polinómicos. Modelos Polinómicos (Grado 2 y 3):

Aunque intentan capturar la no linealidad, introducen mayor error (RMSE) y tienen peores valores R². Se observa que el grado polinómico introduce sobreajuste, ya que los modelos no logran generalizar. Conclusión: La Regresión Lineal Mejorada es la opción óptima para este conjunto de datos, ya que proporciona el mejor equilibrio entre ajuste y error.

#5.5

Regresión lineal vs polinómica:
![image](https://github.com/user-attachments/assets/43d89470-8675-4cfa-813f-d0c9b89e0bc7)


Regresión Lineal vs Polinómica
![image](https://github.com/user-attachments/assets/a309eb2d-cfec-466f-a858-33086709e63e)

En la primera gráfica, la regresión lineal y polinómica mostraban un rendimiento deficiente. El R² (coeficiente de determinación) era bajo, lo que indica que el modelo no explicaba adecuadamente la variabilidad de los datos. Los valores predichos no se ajustaban a las fluctuaciones de los datos reales, especialmente en picos y caídas. Mejoras Aplicadas:

Incorporación de Variables Adicionales: Se añadieron AveragePrice y ventas por tipo de bolsa (Small Bags, Large Bags) para enriquecer el modelo y capturar mejor los factores influyentes en las ventas. Segmentación Temporal: Se pasó de datos anuales (freq='Y') a datos trimestrales (freq='Q'), lo que permitió capturar con mayor precisión las fluctuaciones periódicas. Eliminación de Outliers: Se identificaron y eliminaron valores atípicos que distorsionaban el ajuste de los modelos. Ajuste del Modelo Polinómico: Se utilizó un grado 2 de polinomio para evitar sobreajuste y se aplicó validación cruzada para evaluar la estabilidad del modelo. Análisis de la Segunda Gráfica Ajuste Mejorado:

La regresión polinómica de grado 2 ahora presenta un R² de 0.75, lo que significa que el modelo explica el 75% de la variabilidad de los datos reales. La regresión lineal también ha mejorado su ajuste, alcanzando un R² de 0.72, lo que sugiere que ambos modelos son útiles. Reducción de Errores:

El RMSE (error cuadrático medio) ha disminuido en ambos modelos, lo que indica una mejora en la precisión de las predicciones.

#5.6,5.7
Total Volume, 4046, 4225, 4770, y Total Bags

Primer resultado:

![image](https://github.com/user-attachments/assets/9625537a-d1de-47fd-a58f-ad7837f75bae)

Resultado conseguido:

![image](https://github.com/user-attachments/assets/dc52cc56-b21a-4acb-baee-3a9bb2dd602a)

Resumen del Resultado Intercepto: 1.6113

Representa el valor estimado de AveragePrice cuando todas las variables independientes (4046, 4225, 4770, Total Bags) son 0. Coeficientes:

4046: -0.000001 4225: -0.000000 4770: -0.000012 Total Bags: -0.000001 Métricas del Modelo:

RMSE (Root Mean Squared Error): 0.3272 Mide el error medio cuadrático entre las predicciones del modelo y los valores reales. Este valor indica que existe una dispersión moderada entre los valores predichos y los reales. R² (Coeficiente de Determinación): 0.2209 El modelo solo explica aproximadamente el 22.1% de la variabilidad en AveragePrice. Es un valor bajo, lo que sugiere que las variables utilizadas no son muy predictivas del precio promedio. Interpretación de los Coeficientes Los coeficientes de las variables indican la relación lineal entre cada variable independiente y la variable dependiente AveragePrice:

Variable 4046:

Coeficiente: -0.000001 Interpretación: A medida que el volumen de aguacates 4046 (pequeños) aumenta en una unidad, AveragePrice disminuye en 0.000001 unidades, manteniendo las demás variables constantes. Impacto: Prácticamente insignificante debido al tamaño del coeficiente. Variable 4225:

Coeficiente: -0.000000 Interpretación: Sin impacto relevante sobre AveragePrice. Variable 4770:

Coeficiente: -0.000012 Interpretación: A medida que el volumen de aguacates 4770 (extra grandes) aumenta en una unidad, AveragePrice disminuye en 0.000012 unidades. Impacto: Aunque el valor es más significativo comparado con las otras variables, sigue siendo muy pequeño. Variable Total Bags:

Coeficiente: -0.000001 Interpretación: Aumentos en el volumen de bolsas totales están asociados con una ligera disminución en AveragePrice. Impacto: Insignificante.

#5.8
AveragePrice, Total Volume, 4046, 4225, y 4770.

Comparación de modelos lineal y polinomico:

Primer resultado:
![image](https://github.com/user-attachments/assets/54607d0c-5617-492a-9ab2-907c42fc0c7f)

Resultado final:

![image](https://github.com/user-attachments/assets/4fc9288a-c332-49f6-9f59-ad570b9161b4)

Análisis del Resultado

Descripción del Gráfico El gráfico muestra una comparación de los modelos de regresión lineal y polinómica (grado 2) para predecir AveragePrice a partir de las variables Total Volume, 4046, 4225 y 4770. Ejes: Eje X: Valores reales de AveragePrice. Eje Y: Valores predichos de AveragePrice. Línea ideal (en negro punteada): Representa una predicción perfecta, donde los valores reales y predichos coinciden exactamente. Puntos de Predicción: Azul: Modelo de regresión lineal. Naranja: Modelo de regresión polinómica (grado 2).
Evaluación de Métricas Regresión Lineal:
RMSE: 0.3301 → Indica el error promedio en las predicciones. R²: 0.1323 → Muy bajo, muestra que el modelo lineal explica solo un 13.23% de la variabilidad en AveragePrice. Validación Cruzada R²: 0.1456 → Consistencia baja en la validación cruzada. Regresión Polinómica (Grado 2):

RMSE: 0.3237 → Ligeramente menor que el modelo lineal, indicando una mejora en la precisión. R²: 0.1658 → Mejor que el modelo lineal (16.58%), pero aún bajo, indicando que la relación no es capturada completamente. Validación Cruzada R²: 0.1813 → Mejor desempeño en validación cruzada, indicando que el modelo generaliza un poco mejor.

Interpretación del Gráfico Distribución de Puntos:
Ambos modelos tienen una concentración de predicciones alrededor de valores fijos (entre 1.4 y 1.6) en el eje Y, lo que sugiere que los modelos subestiman o sobreestiman en ciertos rangos de valores reales. La regresión polinómica (naranja) captura ligeras curvaturas, pero aún no muestra una mejora significativa sobre la regresión lineal. Desviación de la Línea Ideal:

La mayoría de los puntos predichos se alejan considerablemente de la línea ideal. Esto indica que ningún modelo está logrando ajustarse bien a los valores reales. Mejora con la Regresión Polinómica:

La regresión polinómica logra una leve mejora en RMSE y R² en comparación con la regresión lineal, pero la diferencia sigue siendo pequeña.

#5.9
Total Volume, AveragePrice, y Total Bags

Analisis de la influencia de total volume y total bags en average price: 

![image](https://github.com/user-attachments/assets/ce67a53e-7981-451d-9305-23ca3829e668)

Analisis de la influencia de total volume y total bags en average price:

![image](https://github.com/user-attachments/assets/ecfd04f6-e0c9-4ec6-bfe6-6bd557b7a5b2)

#5.10
AveragePrice, 4046, 4225, 4770, y Total Volume

Grafico de valores predichos para el Average Price: 

![Uploading image.png…]()

