# Análisis de la Turistificación en Madrid mediante Clustering

Este repositorio contiene el código y los datos utilizados en el proyecto de análisis de la turistificación en Madrid. El objetivo principal es identificar patrones de concentración de alojamientos turísticos y evaluar su impacto en el mercado inmobiliario local utilizando técnicas de clustering.

## Estructura del Proyecto

```
.
├── touristification_clustering.ipynb
├── consolidacion_datos_airbnb.ipynb
├── data
│   ├── airbnb_madrid_2024_con_trimestre.csv
│   ├── distritos_madrid_habitantes.csv
│   ├── idealista_precios_alquiler_m2.csv
│   ├── madrid_distritos_superficie_km2.csv
│   ├── 2024-03-22.csv
│   ├── 2024-06-15.csv
│   ├── 2024-09-11.csv
│   ├── 2024-12-12.csv
├── README.md
```

## Descripción de Archivos

### **Notebook Principal:**
- **`touristification_clustering.ipynb`**: Notebook principal que realiza el análisis de clustering para identificar zonas con mayor presión turística en Madrid.

### **Notebook de Consolidación de Datos Airbnb:**
- **`consolidacion_datos_airbnb.ipynb`**: Notebook que consolida y limpia los datos provenientes de distintas fuentes para generar el dataset unificado utilizado en el análisis. Este notebook carga y combina los archivos `2024-03-22.csv`, `2024-06-15.csv`, `2024-09-11.csv`, y `2024-12-12.csv` junto con los datos de Idealista y de habitantes por distrito.

### **Datos de Entrada:** (ubicados en la carpeta `/data`)
- **`airbnb_madrid_2024_con_trimestre.csv`**: Datos de propiedades completas de Airbnb en Madrid con información del trimestre.
- **`distritos_madrid_habitantes.csv`**: Información sobre el número de habitantes por distrito en Madrid.
- **`idealista_precios_alquiler_m2.csv`**: Datos de precios de alquiler por metro cuadrado según Idealista.
- **`madrid_distritos_superficie_km2.csv`**: Superficie en km² de cada distrito en Madrid.
- **`2024-03-22.csv`, `2024-06-15.csv`, `2024-09-11.csv`, `2024-12-12.csv`**: Archivos temporales que contienen registros detallados de Airbnb en fechas específicas de 2024.

## Instalación y Requisitos

La forma más fácil de ejecutar este proyecto es utilizando **Google Colab**. No es necesario instalar dependencias adicionales. 

## Uso del Notebook Principal

1. Abre el notebook `touristification_clustering.ipynb` en Google Colab o Jupyter Notebook.
2. Carga los datasets proporcionados en la carpeta `/data`.
3. Ejecuta cada celda del notebook siguiendo las instrucciones para:
   - Limpiar los datos.
   - Generar visualizaciones geoespaciales.
   - Aplicar algoritmos de clustering (K-Means y GMM).
   - Interpretar los resultados en el contexto de la turistificación en Madrid.

## Resultados
El análisis se centra en:
- Identificar zonas de alta densidad turística.
- Evaluar la relación entre los precios del alquiler y la concentración de alojamientos turísticos.
- Identificar patrones geoespaciales que reflejen el impacto del turismo en la estructura socioeconómica de Madrid.

## Contribución
Las contribuciones son bienvenidas. Si deseas colaborar, por favor sigue estos pasos:
1. Realiza un fork del repositorio.
2. Crea una rama (`git checkout -b nueva-funcionalidad`).
3. Realiza tus cambios y haz un commit (`git commit -m "Agrego nueva funcionalidad"`).
4. Haz push a la rama (`git push origin nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para obtener más detalles.

## Contacto
Si tienes alguna pregunta o sugerencia, no dudes en contactarme a través de [tu correo] o abrir un issue en este repositorio.


