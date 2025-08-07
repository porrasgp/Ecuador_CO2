# 🌍 Análisis Geoespacial de Emisiones de CO2 en Ecuador

![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)

Aplicación interactiva para visualizar y analizar emisiones de CO₂ por provincia en Ecuador mediante técnicas geoespaciales.

## 🔍 Funcionalidades principales

### 🗺️ Visualización interactiva
- **Mapa dual con capas combinadas**:
  - Heatmap de densidad de emisiones
  - Clústeres de marcadores con detalles específicos
- **Sistemas de coordenadas**:
  - Conversión automática DMS → Decimal
  - Referenciación precisa de ubicaciones

### 📐 Herramientas de análisis
```python
# Código de ejemplo para selección de área
shape_type = st.radio("Tipo de Área:", ["Cuadrado", "Círculo"])
size_param = st.slider("Tamaño del área (km):", 1, 1000, 10)
