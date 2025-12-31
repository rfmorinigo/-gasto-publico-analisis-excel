# Descripción del dataset

El dataset utilizado contiene información sobre el gasto público consolidado, desagregado por funciones del Estado y distribuido a lo largo del tiempo.

Los datos permiten analizar cómo se asignan los recursos públicos entre distintas áreas (educación, salud, seguridad, servicios sociales, etc.) y cómo evoluciona dicho gasto a lo largo de los años.

---

## Estructura de los datos

Cada registro del dataset representa un valor de gasto asociado a:

- **Año**: período temporal de referencia.
- **Función**: área o función del Estado a la que se destina el gasto.
- **Valor de gasto**: monto asociado a dicha función en el período correspondiente.

El dataset incluye tanto un agregado general del gasto como la desagregación por funciones específicas.

---

## Transformaciones realizadas

Durante el proceso de análisis se realizaron las siguientes tareas:

- Normalización de fechas y extracción del año.
- Limpieza y estandarización de nombres de funciones.
- Eliminación de valores nulos o inconsistentes.
- Reorganización de los datos para facilitar el análisis temporal y comparativo.
- Construcción de tablas agregadas y pivotadas para visualización.

---

## Uso en el proyecto

Este dataset fue utilizado como base para:

- Analizar la evolución del gasto público a lo largo del tiempo.
- Comparar el gasto entre distintas funciones del Estado.
- Construir visualizaciones orientadas a la exploración y comprensión de tendencias.

---

## Fuente

Datos públicos oficiales provenientes de un portal gubernamental de datos abiertos.

