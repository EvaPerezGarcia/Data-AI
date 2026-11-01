# Consultoría | Limpieza y Visualización de Datos con Power BI

## Descripción del proyecto

Este proyecto consiste en la limpieza, transformación y visualización de datos en un contexto empresarial simulado, utilizando **Power Query y Power BI**.

A partir de un conjunto de datos ficticio con errores e inconsistencias intencionadas, se desarrolla un proceso de preparación y depuración de la información para obtener una fuente de datos estructurada y fiable. Posteriormente, los datos tratados se utilizan para construir un **dashboard interactivo** que facilita el análisis de la actividad y el rendimiento de una empresa de consultoría.

El objetivo es reproducir un flujo de trabajo habitual en proyectos de análisis de datos: desde la identificación y corrección de problemas de calidad hasta la presentación visual de indicadores relevantes para la toma de decisiones.

---

## 01 / Archivos del proyecto

| Archivo | Descripción |
|---|---|
| `datos_sucios.xlsx` | Conjunto de datos original generado mediante IA, con aproximadamente 1.200 registros y errores intencionados. |
| `datos_limpios_dashboard.pbix` | Archivo de Power BI con los datos depurados, las transformaciones realizadas y el dashboard interactivo. |

---

## 02 / Proceso de limpieza y transformación

El tratamiento de los datos se realizó mediante **Power Query**, aplicando diferentes técnicas para mejorar su calidad, consistencia y fiabilidad.

Principales operaciones realizadas:

- **Corrección de tipos de datos:** revisión y conversión de campos de fechas y valores numéricos.
- **Normalización de registros:** unificación de nombres de clientes, consultores, ciudades y países.
- **Depuración de datos:** eliminación de registros duplicados y valores negativos no válidos en horas y tarifas.
- **Revisión de cálculos:** recálculo de la facturación para garantizar la coherencia de los importes en euros.
- **Estandarización de formatos:** unificación de mayúsculas, minúsculas y traducciones de términos.
- **Filtrado de registros inválidos:** eliminación de observaciones que no cumplían los criterios de calidad establecidos.

### Resultados de la limpieza

<sub>COMPARATIVA DEL PROCESO DE DEPURACIÓN</sub>

| Indicador | Resultado |
|---|---:|
| Registros iniciales | 1.200 |
| Registros finales | 894 |
| Registros eliminados | 306 |
| Reducción del volumen de datos | 25,5 % |

La depuración permitió obtener un conjunto de datos más consistente, eliminando registros problemáticos y mejorando su utilidad para el análisis posterior.

---

## 03 / Dashboard de Power BI

A partir de los datos depurados, se desarrolló un dashboard interactivo en Power BI para analizar diferentes dimensiones de la actividad de la consultora.

**Indicadores y visualizaciones principales:**

- **Indicadores clave (KPI):** total de horas trabajadas, tarifa media y facturación total.
- **Análisis por categorías:** distribución de la actividad según sector, rol profesional y cliente.
- **Evolución temporal:** seguimiento de la facturación por año y mes.
- **Segmentación interactiva:** filtros por ciudad, sector y rol para explorar diferentes perspectivas de los datos.

El dashboard permite consultar los principales indicadores y analizar patrones de actividad mediante una interfaz visual e interactiva.

---

## 04 / Herramientas y tecnologías

| Herramienta | Aplicación |
|---|---|
| **Microsoft Excel** | Almacenamiento y consulta del conjunto de datos original. |
| **Power Query** | Limpieza, transformación y normalización de datos. |
| **Power BI** | Modelado, análisis y desarrollo del dashboard interactivo. |
| **Inteligencia Artificial** | Generación del conjunto de datos ficticio inicial. |

---

## 05 / Consideraciones sobre los datos

El conjunto de datos inicial fue generado mediante inteligencia artificial con fines exclusivamente formativos y contiene registros simulados y errores introducidos intencionadamente.

La limpieza, las transformaciones, las reglas de depuración, los cálculos y el diseño del dashboard fueron desarrollados manualmente para poner en práctica conocimientos de calidad de datos, Power Query y Power BI.

Por tanto, los resultados obtenidos corresponden a un escenario empresarial ficticio y no representan información real de una empresa.

---

## 06 / Derechos de autor y condiciones de uso

© 2026. Todos los derechos reservados sobre los elementos originales de este proyecto.

El trabajo original desarrollado incluye, entre otros elementos, las reglas y configuraciones de limpieza, las transformaciones de datos, los cálculos y medidas creados, el diseño del dashboard, las visualizaciones originales y la documentación.

**Sin autorización previa y por escrito del titular de los derechos, no se autoriza:**

- La reproducción o copia de los elementos originales del proyecto.
- La reutilización de las transformaciones, medidas, cálculos o soluciones desarrolladas.
- La adaptación, modificación, redistribución o publicación de los elementos originales.
- La incorporación del dashboard, sus diseños o componentes originales a otros proyectos.
- La explotación comercial o profesional de los elementos originales sin la autorización correspondiente.

La publicación de este repositorio en GitHub tiene fines informativos y de consulta. No implica la concesión de una licencia para reutilizar los elementos originales del proyecto.

Los datos simulados generados mediante IA y las herramientas, tecnologías y materiales de terceros quedan sujetos a sus respectivas condiciones de uso y derechos aplicables. Esta declaración no pretende atribuir derechos exclusivos sobre materiales ajenos ni sobre funcionalidades propias de las herramientas utilizadas.

Todos los derechos que correspondan sobre los elementos originales del proyecto quedan reservados.
