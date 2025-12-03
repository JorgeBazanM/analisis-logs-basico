# analisis-logs-basico
Python para buscar anomalías e IPs en logs de eventos. Fundamentos de Análisis Forense

# Proyecto: Análisis de Logs Básico para Detección de Anomalías

Este repositorio contiene un script simple en Python para simular la tarea de un Analista SOC de Nivel 1.

## Habilidades Demostradas:
* **Análisis Forense:** Identificación de patrones y artefactos en logs de muestra.
* **Scripting (Python):** Uso básico de Python para automatizar tareas de búsqueda (ej. búsqueda de códigos de error o IPs específicas).
* **Fundamentos SIEM:** Entendimiento del formato de los logs de eventos y cómo se procesan.

## Contenido:
1.  `log_muestra.txt`: Archivo de texto con logs de ejemplo.
2.  `analizador.py`: Script de Python para parsear el log.

## Proceso:
El script lee el archivo `log_muestra.txt` y genera un informe de las IPs que intentaron acceder más de 10 veces en un periodo de tiempo, simulando un ataque de fuerza bruta.
