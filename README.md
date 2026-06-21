<div align="center">

# 📌 Visualización Interactiva de Información - Evolución en el Tiempo (Power BI)  

## 📖 Descripción

</div>

---

Este proyecto utiliza Power BI para visualizar la evolución de diferentes indicadores a lo largo del tiempo, permitiendo la exploración de tendencias en múltiples sectores.

## 🛠️ Funcionalidades  
- Análisis temporal de datos en Power BI.  
- Creación de dashboards interactivos.  
- Predicciones basadas en tendencias históricas.  
- Exportación de reportes en formatos accesibles.  

## 🚀 Tecnologías utilizadas  
- Power BI  
- SQL Server  
- DAX (Data Analysis Expressions)  
- Business Intelligence  

## ▶️ Cómo ejecutar el proyecto  
1. Abrir el archivo `.pbix` en Power BI Desktop.  
2. Conectar la base de datos en SQL Server o importar datasets en CSV/Excel.  
3. Aplicar filtros y explorar visualizaciones dinámicas.  
4. Publicar en Power BI Service si se requiere compartir online.  

## 📌 Autor  
👨‍💻 **Alejandro De Mendoza**

---

## Arquitectura

```mermaid
flowchart TD
    A[Fuentes de Datos] --> B[(SQL Server - Base de datos transaccional)]
    A --> C[(CSV / Excel - Datasets importados)]
    B & C --> D[Power BI Desktop - Archivo .pbix]
    D --> E[Modelo de Datos DAX - Medidas / Columnas calculadas]
    E --> F[Dashboard Interactivo - Evolucion en el tiempo]
    F --> G[Visualizaciones temporales - Tendencias historicas]
    F --> H[Predicciones basadas en tendencias]
    F --> I[Filtros y Segmentadores - Slicer por periodo / indicador]
    D --> J[Power BI Service - Publicacion y compartir online]
```

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
