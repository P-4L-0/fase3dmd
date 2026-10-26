# Proyecto Inteligencia de Negocios - NYC 311

Implementación de una solución de Business Intelligence para analizar las quejas ciudadanas de la línea 311 de Nueva York mediante modelado dimensional y minería de datos.

## Archivos del Repositorio

*   **`fase2_dmd_nyc311_ejecutado.ipynb`**: Notebook de Python con el modelo K-Means y las instrucciones de exportación a CSV integradas. *(Nota: La variable `RUN_GRID_SEARCH` está configurada en `False` para ejecutar directamente el modelo final).*
*   **`/Cubo_SSAS`**: Proyecto multidimensional actualizado
*   **`Dashboard_NYC311.pbix`**: Tablero interactivo en Power BI con análisis geoespacial y evaluación por clústeres.
*   `Datos_y_Conclusiones.pdf`: Documento que detalla exclusivamente el análisis de los datos extraídos y los hallazgos finales del proyecto de Business Intelligence

## Instrucciones de Integración

1. **Generación de Clústeres:** Ejecuta el notebook `.ipynb` incluido para generar y descargar automáticamente el archivo `ResultadosKMeans.csv`.
2. **Importación a SQL Server:** Importa el archivo `ResultadosKMeans.csv` a tu base de datos en SQL Server como una nueva tabla.
3. **Visualización en Power BI:** Abre el archivo `.pbix`. Los datos del cubo de SSAS y la tabla de clústeres en SQL ya están vinculados.


<img width="877" height="500" alt="image" src="https://github.com/user-attachments/assets/6c8a0f5c-9e88-484e-bd69-005453470a89" />
