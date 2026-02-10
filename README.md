# 📊 Análisis Exploratorio de Datos Bancarios 📊

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completado-success)

Este proyecto contiene un análisis exploratorio completo de datos bancarios y campañas de marketing realizadas entre 2012-2014, demostrando técnicas de limpieza, integración y visualización de datos con Python.

---

## 🗻 Estructura del Proyecto

```
├── analysis/          # Análisis exploratorio final y visualizaciones
├── dev/              # Notebooks de desarrollo y pruebas
├── info/             # Documentación adicional y recursos
├── raw_data/         # Datos originales sin procesar
│   ├── bank_data.csv
│   └── customer-details.xlsx (hojas: 2012, 2013, 2014)
└── README.md         # Este archivo
```

---

## 📋 Descripción del Proyecto

El proyecto analiza datos de una campaña de marketing bancario con el objetivo de:

- **Integrar múltiples fuentes de datos** (CSV + Excel con 3 hojas)
- **Limpiar y transformar** información inconsistente
- **Calcular KPIs clave** del negocio bancario
- **Visualizar patrones** en los datos de clientes
- **Generar insights** sobre el comportamiento de los clientes

### Datos Procesados

- **43,000 clientes únicos**
- **Período**: 2012-2014
- **Variables**: 22 columnas incluyendo datos demográficos, económicos y de campaña

---

## 🔧 Tecnologías Utilizadas

- **Python 3.13**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Operaciones numéricas
- **Matplotlib** - Visualizaciones estáticas
- **Seaborn** - Gráficos estadísticos avanzados
- **openpyxl** - Lectura de archivos Excel

---

## 🚀 Cómo Ejecutar el Proyecto

### Requisitos Previos

```bash
# Instalar Python 3.13 o superior
# Instalar las dependencias necesarias
pip install pandas numpy matplotlib seaborn openpyxl
```

### Ejecución

1. **Clonar o descargar** el repositorio
2. **Navegar** a la carpeta del proyecto
3. **Abrir** el notebook en `analysis/` o `dev/`
4. **Ejecutar** las celdas secuencialmente

```bash
# Opción 1: Jupyter Notebook
jupyter notebook

# Opción 2: JupyterLab
jupyter lab

# Opción 3: VS Code con extensión de Python
code .
```

---

## 📊 Hallazgos Principales

### KPIs Calculados

| Indicador | Valor |
|-----------|-------|
| **Capital Total** | 4,009,371,603 € |
| **Clientes Únicos** | 43,000 |
| **Ingreso Promedio** | 93,241.20 €/año |
| **Salud Económica** | -0.09 (economía estable) |
| **Volatilidad Laboral** | 2,040.63% (alta inestabilidad) |

### Insights Clave

✅ **Distribución homogénea** de ingresos entre niveles educativos  
✅ **2012**: Año con mayor captación de clientes (20,018 nuevos)  
✅ **2013**: Caída significativa del 55% en nuevas inscripciones  
✅ **2014**: Recuperación parcial con 14,064 nuevos clientes  
✅ **Sin duplicados** en la base de datos tras limpieza

---

## 🧹 Proceso de Limpieza

Durante el análisis se realizaron las siguientes transformaciones:

- ✔️ Conversión de fechas de formato español a datetime
- ✔️ Imputación de edades nulas con la media (35 años)
- ✔️ Clasificación de empleos vacíos como "Unemployed"
- ✔️ Conversión de variables booleanas (0/1 → yes/no)
- ✔️ Normalización de columnas numéricas con formato europeo
- ✔️ Concatenación vertical de datos 2012-2014
- ✔️ Eliminación de duplicados por ID

---

## 📈 Visualizaciones Incluidas

- 📊 Distribución de ingresos por tipo de empleo (Boxplot)
- 📉 Evolución temporal de nuevos clientes (Gráfico de barras)
- 🗺️ Análisis de correlaciones entre variables económicas
- 📋 Tablas comparativas de medias por grupos

---

## 📖 Próximos Pasos

Después de completar este análisis exploratorio, los siguientes pasos incluyen:

- 🔮 **Modelado predictivo** para estimar probabilidad de suscripción
- 🎯 **Segmentación de clientes** usando clustering (K-Means)
- 📊 **Dashboard interactivo** con Plotly o Streamlit

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor:

1. Haz un **fork** del repositorio
2. Crea una **rama** para tu feature (`git checkout -b feature/ImplementThis`)
3. **Commit** tus cambios (`git commit -m 'Deberías implementar esto!'`)
4. **Push** a la rama (`git push origin feature/ImplementThis`)
5. Abre un **Pull Request**

---

## 📝 Licencia

Este proyecto es de uso educativo y está disponible para fines de aprendizaje.

---

## 👨‍💻 Autor

**Óscar Casanova Herrera**

[![GitHub](https://img.shields.io/badge/GitHub-OscarCasahe-181717?logo=github)](https://github.com/OscarCasahe)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0077B5?logo=linkedin)](https://linkedin.com/in/tu-perfil)

---

## 📧 Contacto

Si tienes preguntas o sugerencias sobre este proyecto, no dudes en contactarme:

- **GitHub**: [@OscarCasahe](https://github.com/OscarCasahe)

---

<div align="center">

**⭐ Si este proyecto te resultó útil, considera darle una estrella ⭐**

*Desarrollado por Óscar Casanova*

</div>