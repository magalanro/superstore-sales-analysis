# 📊 Análisis de Ventas Superstore

> Un análisis de datos de ventas profesional y completo, desarrollado para demostrar
> habilidades en analítica de datos e inteligencia de negocio a potenciales clientes.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-green?logo=pandas)
![Licencia](https://img.shields.io/badge/Licencia-MIT-yellow)
![Estado](https://img.shields.io/badge/Estado-Completo-brightgreen)

🌐 **Idioma / Language:** [English](README.md) | Español

---

## 📌 Descripción del Proyecto

Este proyecto analiza **4 años de datos de transacciones retail** (2014–2017)
de un supermercado ficticio estadounidense. El análisis abarca tendencias de ingresos,
rentabilidad por producto y región, el impacto de los descuentos y
los patrones estacionales de ventas.

El objetivo es doble:
1. **Para propietarios de negocios** — ofrecer insights claros y accionables en un lenguaje
   sencillo que impulse mejores decisiones.
2. **Para el portfolio de analítica de datos** — demostrar un flujo de trabajo completo y
   profesional desde los datos en bruto hasta las recomendaciones de negocio.

---

## 🔑 Conclusiones Principales

- 💻 **Tecnología es la categoría estrella** — genera los mayores ingresos
  y los mejores márgenes de beneficio. Expandir esta categoría es la oportunidad
  de crecimiento más clara.

- 🚨 **Los descuentos superiores al 30% generan pérdidas** — los pedidos con descuentos
  por encima del 30% generan pérdidas netas de media. Limitar los descuentos al 20% es
  la acción de mayor impacto que puede tomar el negocio.

- 📅 **El Q4 es siempre la temporada pico** — noviembre y diciembre impulsan
  consistentemente el mayor volumen de ventas cada año, lo que hace esencial
  la planificación anticipada de inventario y el marketing enfocado en Q4.

- 🗺️ **La región Oeste supera a todas las demás** — no solo en ingresos, sino
  también en margen de beneficio. La región Central tiene un rendimiento inferior
  y necesita una revisión de su política de descuentos y su mix de productos.

---

## 🛠️ Tecnologías Utilizadas

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| Python | 3.10+ | Lenguaje de programación principal |
| Pandas | 2.0+ | Manipulación y análisis de datos |
| Matplotlib | 3.7+ | Librería base de visualización |
| Seaborn | 0.12+ | Visualizaciones estadísticas |
| OpenPyXL | 3.1+ | Exportación a Excel |
| Jupyter Notebook | 7.0+ | Entorno de desarrollo interactivo |

---

## 📁 Estructura del Proyecto
```
superstore-sales-analysis/
│
├── 📓 superstore_analysis.ipynb          # Notebook principal de análisis
├── 📄 README.md                          # Versión en inglés
├── 📊 Sample - Superstore.csv            # Dataset (descargar desde Kaggle)
│
├── 📈 charts/                            # Visualizaciones exportadas
│   ├── chart1_category_performance.png
│   ├── chart2_top10_products.png
│   ├── chart3_monthly_trend.png
│   ├── chart4_region_performance.png
│   ├── chart5_profitability_heatmap.png
│   ├── chart6_discount_analysis.png
│   └── chart7_yearly_growth.png
│
└── 📋 superstore_analysis_summary.xlsx   # Informe Excel exportado
```
---

## 🚀 Cómo Ejecutar el Proyecto

### Paso 1: Clonar el repositorio
```bash
git clone https://github.com/magalanro/superstore-sales-analysis.git
cd superstore-sales-analysis
```

### Paso 2: Crear un entorno virtual (recomendado)
```bash
python -m venv venv

# En Windows:
venv\Scripts\activate

# En macOS/Linux:
source venv/bin/activate
```

### Paso 3: Instalar las librerías necesarias
```bash
pip install pandas matplotlib seaborn openpyxl jupyter notebook
```

O instalar desde el archivo de requisitos:
```bash
pip install -r requirements.txt
```

### Paso 4: Descargar el dataset
1. Ve a [Kaggle — Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
2. Descarga `Sample - Superstore.csv`
3. Colócalo en la carpeta raíz del proyecto

### Paso 5: Lanzar el notebook
```bash
jupyter notebook superstore_analysis.ipynb
```

### Paso 6: Ejecutar todas las celdas
En Jupyter: **Kernel → Restart & Run All**

El notebook generará automáticamente los 7 gráficos y el informe Excel.

---

## 📊 Visualizaciones Incluidas

| # | Gráfico | Pregunta de Negocio Respondida |
|---|---------|-------------------------------|
| 1 | Ingresos y Beneficio por Categoría | ¿Qué categoría de producto es más valiosa? |
| 2 | Top 10 Productos por Ingresos | ¿Qué productos específicos impulsan el negocio? |
| 3 | Tendencia Mensual de Ventas | ¿Cuándo alcanzan su pico las ventas? |
| 4 | Ventas vs. Beneficio por Región | ¿Qué regiones son más y menos rentables? |
| 5 | Mapa de Calor de Rentabilidad | ¿Dónde exactamente ganamos o perdemos dinero? |
| 6 | Análisis del Impacto de Descuentos | ¿Están nuestros descuentos perjudicando la rentabilidad? |
| 7 | Crecimiento Año a Año | ¿Está el negocio creciendo de forma sostenible? |

---

## 💼 Qué Puede Aprender un Negocio de Este Análisis

Este tipo de análisis responde las preguntas que impulsan decisiones de negocio reales
— y es accesible para cualquier propietario, no solo para profesionales de datos.

### 1. Detener las pérdidas por malos descuentos
Muchos negocios aplican descuentos sin verificar si son rentables. Este análisis muestra
exactamente en qué nivel de descuento se deja de ganar dinero — y en este caso, cualquier
descuento por encima del 30% genera pérdidas activas. Este insight por sí solo podría
recuperar miles de euros al mes.

### 2. Invertir donde los márgenes son mejores
No todos los productos o regiones son iguales. Al identificar qué subcategorías y regiones
ofrecen el mejor retorno por cada euro vendido, un negocio puede redirigir la inversión en
inventario, el gasto en marketing y el foco del equipo de ventas hacia lo que realmente
hace crecer el beneficio — no solo los ingresos.

### 3. Planificar operaciones en torno a patrones estacionales predecibles
Cuando sabes que el Q4 siempre será tu pico, puedes prepararte: contratar personal de
temporada antes, reponer inventario en septiembre y lanzar campañas de marketing en octubre
en lugar de improvisar en diciembre. Los datos hacen tu calendario más predecible.

### 4. Medir lo que importa — el beneficio, no solo las ventas
Una trampa habitual para negocios en crecimiento es celebrar el aumento de ingresos
mientras los márgenes se reducen silenciosamente. Este análisis monitoriza ambos, para que
siempre sepas si el crecimiento es sostenible.

---

## 📬 Contacto

¿Interesado en un análisis similar para los datos de tu negocio?

**Marcos Galán Rodríguez**
📧 [magalanro@gmail.com](mailto:magalanro@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/marcos-galán-rodríguez-385825354)

Me especializo en convertir datos de negocio en bruto en insights claros y accionables
usando Python y visualización de datos. Disponible para proyectos freelance.

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT — consulta el archivo
[LICENSE](LICENSE) para más detalles.

---

## 🙏 Agradecimientos

- Dataset: [Superstore Dataset en Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) por Vivek Chavare
- Concepto original del dataset por los datos de muestra de Tableau
