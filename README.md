# Análisis de Transacciones con Tarjeta de Crédito (2019–2020)
Este proyecto analiza la detección de patrones de fraude en contexto pandémico, utilizando Python y Google Colab.
## Dataset de Loan Default
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/kartik2112/fraud-detection/data?select=fraudTrain.csv)

El presente es un dataset sintético de transacciones realizadas con tarjeta de crédito durante el período 2019–2020, generado mediante simulación computacional y publicado en Kaggle. El dataset incluye tanto transacciones legítimas como fraudulentas.
## Tecnologías y librerías
Fueron utilizados los siguientes recursos: Python como código principal, y pandas, matplotlib, seaborn, numpy y os como herramientas.
## Instrucciones de uso
Abrir el archivo `Análisis_de_Transacciones_con_Tarjeta_de_Crédito_(2019–2020).ipynb` en Google Colab o Jupyter Notebook y ejecutar las celdas en orden.
## Clonar el repositorio
_Git clone_ https://github.com/vsanzi22/herramientasbasicas-sanzi-valeria
## Instalar librerias
pip install -r requirements.txt
## Resultados principales
El análisis de las transacciones con tarjeta de crédito durante el período 2019–2020 permitió identificar patrones claros que distinguen el comportamiento fraudulento del legítimo en tres dimensiones: temporal, económica y comercial.

Las transacciones fraudulentas representaron una proporción minoritaria pero constante del total, sin mostrar una correlación directa con el incremento del volumen general de transacciones. Llamativamente, el inicio de la pandemia de COVID-19 no generó una caída significativa en el volumen de transacciones legítimas, lo que sugiere una rápida adaptación al consumo digital.

El hallazgo más relevante del análisis surge de la combinación de los patrones horario y semanal: el momento de mayor vulnerabilidad se produce entre el viernes y el lunes durante la franja nocturna de 22hs a 3hs. Esta convergencia entre la menor operatividad de los equipos antifraude durante el fin de semana y la inactividad del titular de la tarjeta configura una ventana de exposición sistemática y predecible.

Como limitación del presente análisis cabe destacar que el dataset utilizado es de naturaleza sintética, por lo que los patrones identificados, si bien analíticamente válidos, no necesariamente reflejan la distribución real del fraude en el sistema financiero. Como posible extensión del trabajo, resultaría de interés aplicar modelos de clasificación supervisada para evaluar la capacidad predictiva de las variables analizadas.
## Autora
Sanzi, Valeria Alejandra.

 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue?logo=linkedin)](https://www.linkedin.com/in/valeria-sanzi/) 
