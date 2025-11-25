Parkinsons Telemonitoring Dataset (Versión General)
Descripción general

Este conjunto de datos contiene información clínica y vocal recolectada a pacientes con enfermedad de Parkinson a lo largo del tiempo.
El objetivo principal es analizar y monitorear la progresión de los síntomas utilizando mediciones obtenidas de forma remota.

Contenido del dataset
Datos del paciente: identificación, edad, sexo y tiempo de seguimiento.
Mediciones clínicas: puntajes UPDRS (motor y total), que evalúan la severidad de los síntomas.
Características vocales: medidas numéricas extraídas de grabaciones de voz, relacionadas con estabilidad, amplitud y calidad vocal.

Tamaño
Registros: 5,875
Columnas: 19

Objetivo del dataset
Permite estudiar la evolución de la enfermedad y desarrollar modelos que predigan los puntajes UPDRS a partir de señales vocales, apoyando herramientas de telemedicina.

Limpieza aplicada
En el proceso de preparación del archivo:
Se estandarizaron los nombres de las columnas.
Se eliminaron duplicados.
Se ajustaron los tipos de datos.
Se revisaron valores atípicos básicos.

Breast Cancer Wisconsin Diagnostic (Versión General)
Descripción general
Este dataset incluye mediciones numéricas obtenidas de imágenes de tejido mamario mediante un procedimiento llamado Fine Needle Aspiration (FNA).
El objetivo es distinguir entre tumores malignos y benignos usando características celulares.

Contenido del dataset
Variable objetivo: diagnóstico (M = maligno, B = benigno).
Características numéricas: 30 mediciones sobre forma, textura, tamaño y geometría del núcleo celular.
Cada característica se presenta en tres versiones: promedio, error estándar y peor valor observado.

Tamaño
Registros: 569
Columnas: 31 (30 numéricas + diagnóstico)

Objetivo del dataset
Sirve para entrenar y evaluar modelos de clasificación orientados al diagnóstico temprano del cáncer de mama y para análisis de patrones celulares.

Limpieza aplicada
Se renombraron columnas para mantener consistencia.
Se eliminaron datos duplicados.
Se formateó la variable de diagnóstico.
Se verificó la presencia de valores fuera de rango.
