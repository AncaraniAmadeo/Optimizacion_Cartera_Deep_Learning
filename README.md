# Optimización de Cartera Financiera mediante Aprendizaje Profundo

## Autor: Amadeo Gustavo Ancarani
### Director: Jorge Linde Díaz

## Máster Universitario en Ciencia de Datos (2021-2022)

El presente Trabajo Fin de Máster (TFM) tiene por objetivo final la implementación de una optimización de carteras de activos financieros mediante la utilización de algoritmos de aprendizaje profundo.

A modo simplificado es posible describir al proceso por las siguientes etapas:
•	En el desarrollo del trabajo se seleccionan, a través de una red neuronal (definición central en el aprendizaje profundo), 5 acciones que cumplan con ciertos 
requisitos.

•	Luego, se capta la información de los últimos 300 períodos de las acciones seleccionadas para estimar los rendimientos de los próximos 5 períodos a través de una segunda red neuronal con una arquitectura diseñada para optimizar las predicciones secuenciales.

•	Con estos rendimientos estimados, se obtienen los pesos relativos de cada acción en la cartera para los próximos 5 períodos a través de una tercera red neuronal.

•	El usuario de estas arquitecturas solo deberá ejecutar este código implementado cada vez que quiera obtener la distribución óptima de la proporción a mantener de cada acción en la cartera optimizada. Debe ser mencionado que como mínimo, se debe mantener dicha distribución al menos 5 períodos, salvo cambios abruptos en el mercado, para lograr un mejor rendimiento general.

## ESTRUCTURA 

Tras la introducción, en el segundo capítulo se desarrolla el bloque teórico ya que se introducen aspectos financieros como lo son: la inversión en activos y los métodos clásicos de optimización de carteras. Paso siguiente se busca describir temas más técnicos como la Inteligencia Artificial y el Aprendizaje Profundo, ampliando en este punto, se presentan las diferentes arquitecturas de Redes Neuronales implementadas para lograr el objetivo del trabajo.

En el tercer capítulo se presentan las herramientas informáticas utilizadas en este Trabajo Fin de Máster, a saber: Google Colab, Keras, GitHub y la manera con la cual fueron obtenidas las bases de datos sobre las que se entrenaron y validaron los distintos modelos desarrollados.

En el cuarto capítulo se explican las decisiones tomadas para formar la estructura de cada modelo y el proceso seguido para el desarrollo de este proyecto aclarando algunos puntos, cómo por ejemplo los criterios de validación y bondad del modelo. Además, se justifican distintas decisiones de programación.

En el quinto capítulo se presentan los resultados más relevantes del trabajo: modelos entrenados junto a sus métricas de validación y enlaces y explicación de las distintas aplicaciones planteadas.

Finalmente, en el sexto capítulo se establecen las conclusiones de este trabajo y algunas ideas de mejora que el autor espera poder aplicar en un futuro con el fin de lograr una aplicación plenamente funcional.
 
