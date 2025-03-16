# 🌐 Análisis de Influencias Sociodemográficas en la Felicidad


## ✨ Descripción

Este proyecto analiza la relación entre los datos de felicidad de los países y sus características socio-demográficas. Se utilizan datos de la API **REST Countries**, el **World Happiness Report** y un **TopoJSON** para explorar correlaciones y visualizar los hallazgos en **Power BI**.

## 🔧 Tecnologías Utilizadas

- **Python** 👨‍💻 (Pandas, Seaborn, Matplotlib) para el preprocesamiento y análisis.
- **Power BI** 📊 para la visualización de datos.
- **Excel** 📄 para almacenar los datasets.

### 📚 Fuentes de Datos

- 🌍 **[REST Countries API](https://restcountries.com/)** (Datos socio-demográficos de países)
- 😃 **[World Happiness Report](https://worldhappiness.report/)** (Índices de felicidad por país)
- 🗺 **[TopoJSON - Mapa Coroplético](https://github.com/subyfly/topojson/blob/master/world-countries.json)** (Mapa mundial para visualización en Power BI)

---

## 🚀 Funcionalidades

- ✔️ Consumo de la API **REST Countries** para obtener datos de los países
- ✔️ Integración con datos de felicidad del **World Happiness Report**  
- ✔️ Análisis de correlación entre variables socio-demográficas y felicidad
- ✔️ Visualización interactiva en **Power BI** con mapas y gráficos  
- ✔️ Uso de **Python (Pandas, Seaborn, Matplotlib)** para preprocesamiento y análisis  

---

## 📊 Visualización del Proyecto

Aquí se muestra una vista previa del análisis realizado en Power BI:

![Dashboard Power BI](https://github.com/user-attachments/assets/896c7a08-9a12-4c41-9ffb-caa4672105d7)

---

## 🛠 Instalación y Uso

1. **Clona este repositorio**:  
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   cd tu-repo
2. **Instalar Dependencias en Python:**  
   ```bash
   pip install pandas matplotlib seaborn openpyxl
3. **Ejecutar el Script de Correlación**
   ```bash
   python preprocessing/correlacion.py
4. **Abrir Power BI y Cargar Happiness-and-Sociodemographic-Dashboard.pbix**
   
- Navegar a la carpeta visualizacion/
- Abrir proyecto.pbix en Power BI Desktop
- Explorar los gráficos y mapas interactivos
