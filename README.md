# 🌍 Análisis Geoespacial de Emisiones de CO2 en Ecuador

## 🌍 ¿Qué hace esta aplicación?

Esta herramienta interactiva permite visualizar y analizar posibles **zonas de riesgo ambiental en Ecuador** en función de las **emisiones de dióxido de carbono (CO₂)**.

A través de un mapa interactivo, cualquier persona puede seleccionar una ubicación y definir un área (en forma de círculo o cuadrado) para observar:

- Las provincias dentro de esa área.
- Los niveles de riesgo asociados a las emisiones de CO₂.
- Un resumen visual con calor y marcadores de las zonas detectadas.
- Los valores totales de CO₂ estimados para esa región.

## ⚙️ ¿Cómo funciona?

- La app utiliza datos geográficos en un archivo Excel con coordenadas y niveles de riesgo.
- Convierte automáticamente las coordenadas al formato correcto.
- Permite al usuario elegir una ubicación manualmente mediante latitud y longitud.
- Usa filtros espaciales para analizar solo la zona seleccionada.
- Muestra resultados en un mapa y permite exportarlos en formato `.csv`.

## 📦 ¿Qué tecnologías utiliza?

- [Streamlit](https://streamlit.io): Para la interfaz web interactiva.
- [Folium](https://python-visualization.github.io/folium/): Para generar mapas con capas de calor y marcadores.
- [Pandas](https://pandas.pydata.org): Para manejar los datos.
- [OpenStreetMap](https://www.openstreetmap.org): Como base de los mapas.

## 📥 ¿Qué salida proporciona?

- Mapa interactivo con:
  - Zonas coloreadas por área de análisis.
  - Capa de calor según la concentración de puntos.
  - Marcadores con información detallada por ubicación.
- Resumen con:
  - Total de emisiones de CO₂ en la zona analizada.
  - Cantidad de ubicaciones detectadas.
  - Top 5 zonas de mayor riesgo.
- Opción para descargar los resultados como archivo `.csv`.

## 🎯 ¿Para quién es útil?

Esta aplicación es útil para:

- Ciudadanos interesados en temas ambientales.
- Tomadores de decisiones en políticas de sostenibilidad.
- Investigadores que desean explorar los datos geoespaciales de emisiones.
- Estudiantes que quieran aprender sobre visualización interactiva de datos.

---

> Desarrollado por: [Giovanni Solano Porras](https://github.com/porrasgp)
