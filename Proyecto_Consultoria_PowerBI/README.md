# Consultoría | Limpieza y Visualización de Datos con Power BI

Este proyecto aborda la limpieza, transformación y visualización de datos en un contexto empresarial simulado, utilizando **Power Query y Power BI**.

A partir de un conjunto de datos ficticio con errores e inconsistencias intencionadas, se desarrolla un proceso de depuración para obtener información estructurada y fiable. Posteriormente, los datos tratados se utilizan para construir un **dashboard interactivo** que facilita el análisis de la actividad y el rendimiento de una empresa de consultoría.

---

## <code>01 /</code> ARCHIVOS DEL PROYECTO

**`datos_sucios.xlsx`**

<sub>ARCHIVO ORIGINAL · EXCEL · 1.200 REGISTROS</sub>

Conjunto de datos generado mediante IA, con errores e inconsistencias introducidos intencionadamente para practicar técnicas de limpieza y transformación.

**`datos_limpios_dashboard.pbix`**

<sub>ARCHIVO FINAL · POWER BI</sub>

Archivo que contiene los datos depurados, las transformaciones realizadas mediante Power Query y el dashboard interactivo.

---

## <code>02 /</code> PROCESO DE LIMPIEZA Y TRANSFORMACIÓN

El tratamiento de los datos se realizó mediante **Power Query**, aplicando diferentes operaciones para mejorar su calidad, consistencia y fiabilidad.

Principales operaciones realizadas:

- **Corrección de tipos de datos:** revisión y conversión de campos de fechas y valores numéricos.
- **Normalización de registros:** unificación de nombres de clientes, consultores, ciudades y países.
- **Eliminación de duplicados:** detección y eliminación de registros repetidos.
- **Validación de valores:** eliminación de valores negativos no válidos en horas y tarifas.
- **Revisión de cálculos:** recálculo de la facturación para garantizar la coherencia de los importes en euros.
- **Estandarización de formatos:** unificación de mayúsculas, minúsculas y traducciones de términos.
- **Filtrado de registros inválidos:** eliminación de observaciones que no cumplían los criterios de calidad establecidos.

### Resultados de la limpieza

- **Registros iniciales:** 1.200
- **Registros finales:** 894
- **Registros eliminados:** 306
- **Reducción del volumen de datos:** 25,5 %

La depuración permitió obtener un conjunto de datos más consistente, mejorando su calidad y utilidad para el análisis posterior.

---

## <code>03 /</code> DASHBOARD DE POWER BI

A partir de los datos depurados, se desarrolló un dashboard interactivo en Power BI para analizar diferentes dimensiones de la actividad de la consultora.

**Indicadores clave (KPI)**
- Total de horas trabajadas.
- Tarifa media.
- Facturación total.

**Análisis y visualizaciones**
- Distribución de la actividad por sector, rol profesional y cliente.
- Evolución temporal de la facturación por año y mes.

**Interactividad**
- Filtros por ciudad.
- Segmentación por sector.
- Filtrado por rol profesional.

El dashboard permite consultar los principales indicadores y analizar patrones de actividad mediante una interfaz visual e interactiva.

---

## <code>04 /</code> HERRAMIENTAS Y TECNOLOGÍAS

- **Microsoft Excel:** almacenamiento y consulta del conjunto de datos original.
- **Power Query:** limpieza, transformación y normalización de datos.
- **Power BI:** modelado, análisis y desarrollo del dashboard interactivo.
- **Inteligencia Artificial:** generación del conjunto de datos ficticio inicial.

---

## <code>05 /</code> CONSIDERACIONES SOBRE LOS DATOS

El conjunto de datos inicial fue generado mediante inteligencia artificial con fines exclusivamente formativos y contiene registros simulados y errores introducidos intencionadamente.

La limpieza, las transformaciones, las reglas de depuración, los cálculos y el diseño del dashboard fueron desarrollados manualmente para poner en práctica conocimientos de calidad de datos, Power Query y Power BI.

Los resultados corresponden a un escenario empresarial ficticio y no representan información real de una empresa.

---

## <code>06 /</code> DERECHOS DE AUTOR Y CONDICIONES DE USO

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
