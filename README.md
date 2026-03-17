# Dashboard de Conversión Ecommerce

Análisis interactivo del funnel de conversión de un canal ecommerce fashion, con segmentación por canal de adquisición y dispositivo.

**Demo en vivo → [ver dashboard](https://castanobelen.github.io/ecommerce-conversion-dashboard)**

---

## Contexto

En ecommerce fashion, entender *dónde* y *por qué* los usuarios abandonan el proceso de compra es clave para tomar decisiones de inversión en UX, campañas y catálogo. Este proyecto simula el análisis que realizo semanalmente sobre el canal digital, con datos representativos del comportamiento real de usuarios en retail fashion argentino.

---

## ¿Qué muestra el dashboard?

**KPIs principales**
- Sesiones, tasa de conversión, ticket promedio, revenue y abandono de carrito

**Funnel de conversión completo**
- Sesión → Vista de producto → Add to cart → Checkout → Compra
- Visualización de drop-off en cada etapa

**Segmentación interactiva**
- Por canal: Orgánico, Paid Search, Social, Email, Directo
- Por dispositivo: Mobile, Desktop, Tablet

**Análisis de revenue por canal**
- Distribución de ingresos con gráfico de donut interactivo

**Performance por categoría**
- Top 5 categorías por revenue, unidades y CVR

**Drop-off por canal**
- Comparación de abandono en cada etapa del funnel según canal de adquisición

---

## Stack

| Herramienta | Uso |
|---|---|
| HTML / CSS / JavaScript | Dashboard interactivo |
| Chart.js | Visualizaciones (línea, barras, donut) |
| SQL (simulado) | Lógica de extracción y agregación de datos |
| GA4 | Fuente de referencia para métricas y comportamiento |

---

## Insights clave del análisis

- **Email** es el canal con mayor CVR (5,1%) y ticket promedio más alto — audiencia de alta intención.
- **Social** tiene el mayor volumen de abandono de carrito (74,2%) — oportunidad de mejora en landing y checkout.
- **Mobile** concentra el mayor tráfico pero la menor conversión — gap de experiencia móvil a optimizar.
- En eventos comerciales, el CVR se duplica respecto a días normales (0,9% → 1,8%).

---
## Estructura del proyecto

    ecommerce-conversion-dashboard/
    │
    ├── index.html          # Dashboard completo (single file)
    └── README.md
    
## Cómo usar

1. Clonar o descargar el repo
2. Abrir `index.html` en cualquier navegador
3. Usar los filtros de canal y dispositivo para explorar los datos

---

## Contacto

**María Belén Castaño**
[linkedin.com/in/belencastaño](https://linkedin.com/in/belencastaño) · castanobelen@gmail.com
