# Marquet

## 📋 Pre-requisitos

Este proyecto se ha realizado con una versión de Python 3.12, por lo que se recomienda usar esa versión, o superior. Versiones más antiguas pueden dar problemas de incompatibilidades o errores en el código.

Para poder ejecutar los jupyterNotebooks en el proyecto, es necesario tener las siguientes librerías en la instalación de Python (las versiones recomendadas son las utilizadas para el proyecto)



| librería | versión |
| - | - |
| pandas | 2.2.3 |
| numpy | 2.2.4 |
| seaborn | 0.13.2 |
| matplotlib | 3.10.0 |
| scipy | 1.15.2 |


# 📈 Digital Marketing Analysis

Análisis integral de campañas de marketing digital en el sector tecnológico, enfocado en evaluar su rendimiento, identificar patrones de comportamiento y optimizar estrategias futuras basadas en datos.

## 🎯 Objetivos

- Evaluar la efectividad de campañas en términos de ROI, ingresos y conversión.
- Detectar tendencias temporales, estacionales y por canal.
- Proporcionar recomendaciones accionables para mejorar resultados futuros.

## 🛠 Metodología

- Limpieza y procesamiento de datos reales de campañas.
- Análisis estadístico y visual exploratorio.
- Segmentación por audiencia, tipo de campaña y canal.
- Evaluación de KPIs clave: ingresos, ROI, conversión, presupuesto.

## 📊 Resultados

- Visualizaciones claras y comparativas.
- Clasificación de campañas de alto rendimiento.
- Insights prácticos basados en rendimiento temporal y estratégico.

## 🧹 Resumen de Limpieza de Datos

Proceso aplicado sobre un total inicial de **1,037 registros**:

| Criterio de limpieza                                     | Registros eliminados | Registros restantes |
|----------------------------------------------------------|-----------------------|----------------------|
| Nulos excesivos                                          | 5                     | 1,032                |
| `type` nulo (rellenado con "others")                     | 0                     | 1,032                |
| Presupuestos conflictivos                                | 3                     | 1,029                |
| `target_audience` conflictivo (rellenado por similitud)  | 0                     | 1,029                |
| `conversion_rate` conflictivo                            | 1                     | 1,028                |
| `revenue` conflictivo                                    | 2                     | 1,026                |
| Fechas (`start_date` / `end_date`) conflictivas          | 3                     | 1,023                |
| Outliers adicionales                                     | 0                     | 1,023                |
| Registros duplicados exactos                             | 18                    | 1,005                |
| Duplicidad por nombre de campaña                         | 1                     | 1,004                |

**Total eliminados:** 33 registros  
**Porcentaje eliminado:** 3.18%  
**Datos finales para el análisis:** **1,004 registros** (96.82% del total)

Para más detalles, consulta el [resultado de los analisis](.\\documents\\INFORME.md) del directorio /docs.





<img src="./img/upgrade_logo.jpg" alt="Description" width="50"> **Hub it all!**