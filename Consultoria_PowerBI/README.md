# Limpieza y Visualización de Datos con Power BI | Consultoría

Este proyecto aborda la limpieza, transformación y visualización de datos en un contexto empresarial simulado, utilizando **Power Query y Power BI**.

A partir de un conjunto de datos ficticio con errores e inconsistencias intencionadas, se desarrolla un proceso de depuración para obtener información estructurada y fiable. Posteriormente, los datos tratados se utilizan para construir un **dashboard interactivo** que facilita el análisis de la actividad y el rendimiento de una empresa de consultoría.

---

## <code>01 /</code> ARCHIVOS DEL PROYECTO

<div align="left">

<table>
<tr>
<td width="35%" bgcolor="#263B53">
<strong>ARCHIVO</strong>
</td>
<td width="65%" bgcolor="#263B53">
<strong>DESCRIPCIÓN</strong>
</td>
</tr>
<tr>
<td>
<strong><code>datos_sucios.xlsx</code></strong>
<br/>
</td>
<td>
Conjunto de datos original generado mediante IA, con errores e inconsistencias introducidos intencionadamente para practicar técnicas de limpieza y transformación.
</td>
</tr>
<tr>
<td>
<strong><code>datos_limpios_dashboard.pbix</code></strong>
<br/>
</td>
<td>
Archivo que contiene los datos depurados, las transformaciones realizadas mediante Power Query y el dashboard interactivo.
</td>
</tr>
</table>

</div>

---

## <code>02 /</code> PROCESO DE LIMPIEZA Y TRANSFORMACIÓN

El tratamiento de los datos se realizó mediante **Power Query**, aplicando diferentes operaciones para mejorar su calidad, consistencia y fiabilidad.

**Principales operaciones realizadas:**

- **Corrección de tipos de datos:** revisión y conversión de campos de fechas y valores numéricos.
- **Normalización de registros:** unificación de nombres de clientes, consultores, ciudades y países.
- **Eliminación de duplicados:** detección y eliminación de registros repetidos.
- **Validación de valores:** eliminación de valores negativos no válidos en horas y tarifas.
- **Revisión de cálculos:** recálculo de la facturación para garantizar la coherencia de los importes en euros.
- **Estandarización de formatos:** unificación de mayúsculas, minúsculas y traducciones de términos.
- **Filtrado de registros inválidos:** eliminación de observaciones que no cumplían los criterios de calidad establecidos.

### Resultados de la limpieza

<div align="left">

<table>
<tr>
<td bgcolor="#263B53" align="center">
<strong>REGISTROS INICIALES</strong>
</td>
<td bgcolor="#263B53" align="center">
<strong>REGISTROS FINALES</strong>
</td>
<td bgcolor="#263B53" align="center">
<strong>REGISTROS ELIMINADOS</strong>
</td>
<td bgcolor="#263B53" align="center">
<strong>REDUCCIÓN</strong>
</td>
</tr>
<tr>
<td align="center">
<strong>1.200</strong>
</td>
<td align="center">
<strong>894</strong>
</td>
<td align="center">
<strong>306</strong>
</td>
<td align="center">
<strong>25,5 %</strong>
</td>
</tr>
</table>

</div>

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

© 2026 Eva Pérez García. Todos los derechos reservados sobre los elementos originales de este proyecto.

El trabajo original desarrollado incluye, entre otros elementos, las reglas y configuraciones de limpieza, las transformaciones de datos, los cálculos y medidas creados, el diseño del dashboard, las visualizaciones originales y la documentación.

**Sin autorización previa y por escrito del titular de los derechos, no se autoriza:**

- La reproducción o copia de los elementos originales del proyecto.
- La reutilización de las transformaciones, medidas, cálculos o soluciones desarrolladas.
- La adaptación, modificación, redistribución o publicación de los elementos
