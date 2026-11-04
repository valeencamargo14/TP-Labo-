# TP Grupal – Gasto en fichajes y rendimiento en la Premier League

Trabajo Práctico Grupal · Laboratorio de Métodos Cuantitativos Aplicados a la Gestión
Tecnicatura Universitaria en Gestión y Análisis de Datos en Organizaciones · FCE UBA · 2C 2026

## Pregunta de investigación

¿Cuál es la relación entre el gasto neto en fichajes y la posición final en la tabla de la Premier League, y cómo cambió esa relación entre las temporadas 2005-06 y 2025-26?

**Respuesta resumida:** el gasto neto se asocia de forma positiva pero imperfecta con la posición final. En ambas temporadas, 2 de los 4 clubes que más gastaron terminaron en el Top 4, y la brecha promedio entre el puesto de gasto y el puesto en la tabla pasó de 4,1 a 5,3 puestos (frente a 6,7 esperables por azar). El vínculo se aflojó levemente, sin evidencia de un cambio de paradigma.

## Integrantes

| Nombre y apellido | N° de registro | Usuario de GitHub |
|---|---|---|
| Valentino Camargo | 921481 | valeencamargo14 |
| Pedro Bautista Semo Orsi | 921656 | Pedro-Semo |
| Martín Ezequiel Raber | 921594 | Tinchoraber |
| Emilio Ezequiel Waisman | 921466 | emiwaisman |
| Francisco Tomas Beronich | 922255 | beronichfrancisco |

## Contenido del repositorio

| Carpeta / archivo | Contenido |
|---|---|
| `Notebook/TP_Labo.ipynb` | Notebook de análisis en Python (Google Colab), ejecutado. |
| `Datasets/` | Los dos datasets en CSV (posiciones y gastos, 2005-06 a 2025-26). |
| `Graficos/` | Gráficos exportados desde el notebook en formato PNG. |
| `Informe/` | Informe académico en PDF y link al proyecto de Overleaf (LaTeX). |

## Datos

Datasets de elaboración propia, construidos mediante *web scraping* de Transfermarkt. Cada archivo tiene 420 filas (20 clubes × 21 temporadas) y los montos están en millones de euros corrientes.

- Gastos por temporada: Transfermarkt (https://www.transfermarkt.com.ar/premier-league/einnahmenausgaben/wettbewerb/GB1)
- Tabla de posiciones de cada temporada: Transfermarkt (https://www.transfermarkt.com/premier-league/tabelle/wettbewerb/GB1/)

## Cómo reproducir el análisis

1. Abrir el notebook en Google Colab: [Notebook/TP_Labo.ipynb](https://colab.research.google.com/github/valeencamargo14/TP-Labo-/blob/main/Notebook/TP_Labo.ipynb)
2. Ejecutar todas las celdas en orden (**Entorno de ejecución → Ejecutar todas**).

No hace falta descargar nada: el notebook lee los CSV directamente desde la carpeta `Datasets/` de este repositorio.

## Entrega

Viernes 6 de noviembre de 2026.
