# Proyecto de Inflación Mensual
## Objetivo
Este proyecto tiene como objetivo analizar la evolución de la inflación mensual en Argentina desde enero de 2017 hasta julio de 2023, utilizando datos del Instituto Nacional de Estadística y Censos (INDEC).

## Datos
Los datos utilizados provienen de la página web del INDEC, donde se puede descargar el archivo Excel con la serie histórica de la inflación mensual por rubros y regiones.

Para este proyecto, se seleccionó la segunda hoja del archivo, que contiene la inflación mensual general para todo el país. Se realizó un preprocesamiento de los datos para quedarse solo con la fila del total general y eliminar la primera columna. Luego, se invirtió el dataset de manera que la fecha se volviera el índice y se renombró la columna como “Inflación”.

## Librerías
- **Pandas**: Esta es una librería de Python que proporciona estructuras de datos y herramientas de análisis de datos flexibles y eficientes. Se utiliza en este proyecto para manipular los datos de inflación y crear el DataFrame que se utiliza para el análisis.

- **Matplotlib**: Esta es una librería de Python para la creación de gráficos estáticos, animados e interactivos. Se utiliza en este proyecto para visualizar la evolución de la inflación mensual.

- **Seaborn**: Esta es una librería de visualización de datos de Python basada en Matplotlib. Proporciona una interfaz de alto nivel para dibujar gráficos estadísticos atractivos e informativos. Se utiliza en este proyecto para mejorar la estética de los gráficos de Matplotlib.

## Aprendizajes
Preprocesamiento de datos: Aprenderás cómo limpiar y preparar los datos para el análisis. Esto incluye la eliminación de filas y columnas innecesarias, la reordenación de los datos y la configuración de los índices del DataFrame.

- **Análisis de datos**: Aprenderás cómo analizar los datos para obtener información. Esto incluye la comprensión de la inflación mensual y cómo se acumula con el tiempo.

- **Visualización de datos**: Aprenderás cómo crear gráficos de línea para visualizar la evolución de la inflación mensual. También aprenderás cómo personalizar estos gráficos para mejorar su legibilidad, incluyendo la configuración de los ticks del eje X, la aplicación de un formato porcentual al eje Y, y la adición de títulos y etiquetas.

## Análisis
Se realizó un análisis exploratorio de los datos, utilizando la librería seaborn para generar gráficos de línea que muestren la evolución de la inflación mensual no acumulada y acumulada.

Se observó que la inflación es bastante volátil, aunque en los últimos meses se incrementó con más rapidez previo a las elecciones. Se aprecia también que la inflación acumulada crece de forma exponencial, lo que indica que el poder adquisitivo de la moneda se deteriora cada vez más.

## Visualización
Se generaron dos gráficos de línea, uno para la inflación mensual no acumulada y otro para la inflación acumulada. Se configuraron los ticks del eje X para mostrar cada 3 meses y se aplicó un formato porcentual al eje Y. Se agregaron títulos, etiquetas y una grilla para mejorar la legibilidad de los gráficos. Se guardaron los gráficos en formato jpg.

