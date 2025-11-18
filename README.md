# Proyecto-Final-
Proyecto herramientas de programacion 
Pontificia Universidad Javeriana - Facultad de Ciencias Economicas y Administrativas 

# Descripcion del Proyecto
Este repositorio contiene el análisis exploratorio de datos realizado para comprender la evolución global de la adopción de vehículos eléctricos (EV) entre 2010 y 2021. El trabajo incluye la carga, limpieza, filtrado, visualización e interpretación de datos históricos provenientes de la International Energy Agency (IEA).  Usamos Python en Google Colab, aplicando librerias como pandas y matplotlib para estructurar y analizar el dataset, y para comprender patrpnes entre regiones, teconologiaa (BEV y PHEV) y participacion en el mercado 

# Objetivo del Estudio 
Analizar cómo ha evolucionado la adopción de vehículos eléctricos en distintas regiones del mundo y determinar qué factores explican las diferencias entre mercados avanzados y rezagados.

# Preguntas de Análisis
 	•	¿Cómo ha cambiado la participación de mercado de los EV entre 2010 y 2021?
	•	¿Qué regiones muestran mayor crecimiento en ventas y stock?
	•	¿Cómo se comportan las tecnologías BEV y PHEV a lo largo del tiempo?
	•	¿Existen brechas claras entre países desarrollados y emergentes?
	•	¿Qué patrones globales se identifican a partir de los datos?

# Hipótesis 
1. La adopción de EV aumenta de manera sostenida a nivel global.
2.	Las regiones con políticas públicas fuertes muestran un crecimiento más acelerado.
3.	Los PHEV dominan las primeras etapas, pero los BEV crecen más rápido en años recientes.
4.	Las diferencias regionales pueden visualizarse claramente mediante gráficos.

# Estructura del Repositorio 

Documentos
  Documento/Entrega proyecto.pdf - Informe completo del análisis, hallazgos y visualizaciones.
	•	dataset_IEA.csv (opcional si decides incluirlo) – Dataset histórico de la IEA.

Scripts 
  •	analisis_ev.ipynb
Contiene:
	•	Carga e inspección del dataset
	•	Limpieza y filtrado
	•	Creación de subconjuntos (región, año, powertrain)
	•	Cálculo de ventas, participaciones y crecimientos
	•	Visualizaciones con matplotlib
	•	Interpretación de tendencias BEV vs PHEV

# Metodologia 
Las etapas principales del análisis fueron:

1. Carga e inspección de datos

Uso de pandas para revisar estructura, tipos de variables y valores faltantes.
Se identificaron columnas como Region, Year, Parameter, Powertrain, Value, Units

2. Limpieza
	•	Filtrado por parámetros relevantes:
	•	EV sales
	•	EV sales share
	•	EV stock
	•	Filtrado por tecnologías: BEV y PHEV
	•	Creación de subconjuntos por región y por año.

3. Cálculos
	•	Totales por año
	•	Evolución porcentual
	•	Comparación regional
	•	Cambios tecnológicos BEV/PHEV

4. Visualización

Gráficos con matplotlib donde se evidencian diferencias claras entre regiones líderes (Europa, China) y regiones con crecimiento lento (LatAm).

5. Interpretación

Confirmación o rechazo de hipótesis basado en tendencias de comportamiento.

# Hallazgos Principales 

1. Crecimiento global sostenido

La participación de EV pasa de 0.024% (2010) a 0.93% (2014), marcando un crecimiento acelerado.

2. Diferencias muy marcadas entre regiones

Europa y China muestran alto dinamismo; América Latina avanza lentamente debido a infraestructura limitada e incentivos débiles.

 3. Cambio tecnológico
	•	PHEV → más adoptados al inicio
	•	BEV → crecimiento más pronunciado en años recientes

4. Brechas visibles en los gráficos

Las visualizaciones evidencian que contexto económico, políticas y tecnología influyen fuertemente en la adopción.

# Autores 
1. Camilo Franco
2. Isabella Cristancho
3. Angie Quiroga
4. Cristobal Herrera
5. Paula Peñuela

Profesor: Daniel Duque Lozano

