# 📊 Dashboard de Ventas | Sales Dashboard  

### 🎯 Objetivo  
El propósito de este proyecto es **analizar el rendimiento de las ventas de una empresa ficticia** mediante un **dashboard interactivo en Excel**, permitiendo identificar patrones, productos más vendidos, clientes clave y evolución temporal de las ganancias.  
Analyze the sales performance of a fictitious company through an **interactive Excel dashboard**, identifying patterns, best-selling products, key customers, and profit evolution.  

Este proyecto forma parte de mi **portafolio profesional** y busca demostrar habilidades en:  
- Excel Data Analysis | Análisis de datos en Excel  
- ETL with Power Query | ETL con Power Query  
- Data Modeling with Power Pivot | Modelado de datos con Power Pivot  
- Advanced Calculations with DAX | Cálculos avanzados con DAX  
- Business Dashboard Design | Diseño de dashboards comerciales  

---

### 🔎 Descripción del Proyecto  | Project Description  
El proyecto sigue un flujo de trabajo completo:  

1. **ETL con Power Query | ETL with Power Query**  
   - Extracción, limpieza, estandarización y unión de datos desde múltiples tablas.  
   - Creation of calculated columns (e.g., *Delivery Duration*).  
   - Carga del dataset consolidado en Power Pivot / Loaded into Power Pivot.  

2. **Modelado en Power Pivot**  
   - Creación de relaciones entre tablas / Building relationships between tables.  
   - Implementación de tabla calendario para análisis temporal / Calendar table for time analysis.  

3. **Medidas DAX creadas**  
   - `Importe Bruto | Gross Amount` = Cantidad × Precio Unitario | Quantity × Unit Price  
   - `Discount Value` = Importe Bruto × % Descuento | Gross Amount × % Discount  
   - `Total Sales` = Importe Bruto – Discount Value  
   - `Profit` = Total Sales – COGS  
   - `Margen % | Margin %` = Profit / Total Sales  
   - `Average Delivery Duration`
     
4. **Dashboard Final**  
   - **KPIs**: Total Orders, Total Sales, Total Profit, Average Delivery Duration  
   - **Segmentadores / Slicers **: Year, Category, Product Name  
   - **Visualizaciones / Visuals **:  
     - Ventas Totales por Mes | Total Sales by Month (line chart)  
     - Ventas por Región | Sales by Region (bar chart)  
     - Top 5 Productos más vendidos | Top 5 Best-Selling Products (horizontal bar, units)  
     - Top 5 Clientes | Top 5 Customers (horizontal bar)  
     - Evolución Ventas vs Profit | Sales vs Profit Evolution (combo chart)  
     - Ventas por Categoría | Sales by Category (pie chart)
     - 
---

### 📸 Vista Previa  
![Dashboard Preview](assets/dashboard-preview.png)  

---

### 📂 Fuentes de Datos | Data Sources  
- **t-ventas**: detalle de cada pedido, con fechas, cantidades, precios y descuentos.  
- **t-producto**: catálogo de productos con información de categoría.  
- **t-clientes**: información de clientes.  
- **t-ubicación**: regiones y localizaciones asociadas a los pedidos.  

> Los datos utilizados son ficticios y creados únicamente con fines educativos | Fictitious data for educational purposes.    

---

### 🚀 Cómo Usarlo  | How to Use  
1. Descarga el archivo Excel desde este repositorio  | Download the Excel file  
2. Abre el archivo en **Excel con Power Pivot habilitado** |  Open in **Excel with Power Pivot enabled**   
3. Explora el dashboard usando los **segmentadores interactivos** (año, categoría, producto) | Explore with the **interactive slicers**    

---

### 🛠️ Skills aplicadas  
- Power Query (ETL)  
- Power Pivot (modelado de datos)  
- DAX (medidas y cálculos avanzados)  
- Diseño de dashboards en Excel  
- Análisis de ventas y KPIs  

---
