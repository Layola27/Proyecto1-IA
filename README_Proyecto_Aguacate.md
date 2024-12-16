# Análisis del Conjunto de Datos de Precios de Aguacate

## Descripción del Proyecto
✨✨✨ Este proyecto explora el mercado del aguacate en los Estados Unidos utilizando datos históricos obtenidos de Kaggle. El objetivo principal es identificar tendencias, analizar patrones estacionales y regionales, y comprender la evolución de los precios y volúmenes de venta. Además, se busca preparar el conjunto de datos para posibles aplicaciones en modelado predictivo y aprendizaje automático. ✨✨✨

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

# Filtrar los outliers fuera del rango [Q1 - 1.5 * IQR, Q3 + 1.5 * IQR]
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

