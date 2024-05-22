
## Metricas Glass Matrix


Estructura de archivos: 
 - Cada archivo tpX.json, contiene la métrica correspondiente a X en el documento de TPA.
 - El formato de cada archivo es:
   1. Descripción de la métrica.
   2. JSON de la metrica ejecutable en  https://github.com/Antoniiosc7/tp-tester
   3. Query GitHub GraphQL API.

También está el archivo general que contiene todos los tps y sus garantias (TPA.json).

Las querys de Github GraphQL API, se pueden ejecutar en https://developer.github.com/v4/explorer/