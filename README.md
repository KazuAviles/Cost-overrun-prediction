# Cost_overrun_prediction

Este es el desarrollo de un proyecto de practica personal, utilizando datos sintéticos.
Descripción del Proyecto:

Proyecto: Predicción de sobrecostos en proyectos de construcción
Objetivo del proyecto:
Predecir si un proyecto de construcción tendrá sobrecostos utilizando datos históricos de proyectos similares.

Pregunta típica:
¿Qué factores contribuyen más a los sobrecostos en los proyectos y cómo podemos anticipar esto antes de que ocurran?

## Descripción de los datos 
Definir el problema:

Los sobrecostos son un problema común en el sector de construcción. Este proyecto busca predecir si un proyecto está en riesgo de sobrecostos usando técnicas de machine learning.
Obtención de datos:

Usa un dataset ficticio o genera datos sintéticos que incluyan columnas como:
- `project_id` — ID del proyecto;
- `estimated_cost` — costo estimado del proyecto;
- `actual_cost` — costo real del proyecto;
- `duration_estimated` — duración estimada en meses.
- `duration_actual` — Duración real en meses.
- `team_size` — Tamaño del equipo.
- `region` — Región del proyecto.
- `material_availability` — Disponibilidad de materiales (0 o 1).
- `complexity` — Complejidad del proyecto (baja, media, alta).
- `has_issues` — Problemas identificados durante la ejecución (0 o 1).
- `over_budget` — Variable objetivo (1 si el costo real supera al estimado, 0 en caso contrario).