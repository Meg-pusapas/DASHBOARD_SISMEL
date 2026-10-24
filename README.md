# Observatorio del Mercado Laboral y Salud Mental en Colombia (2015–2026)

Este proyecto despliega una plataforma analítica e interactiva basada en **30.932 registros oficiales de Medicina Legal (INMLCF)** y microdatos de la **Gran Encuesta Integrada de Hogares (GEIH - DANE)** para 23 ciudades de Colombia entre 2015 y 2026.

## 🚀 Despliegue en Vercel

### Opción 1: Mediante la CLI de Vercel
1. Instala Vercel CLI: `npm i -g vercel`
2. Ejecuta `vercel` en la carpeta raíz del proyecto.
3. Sigue las instrucciones en pantalla.

### Opción 2: Vinculando con GitHub
1. Crea un repositorio en GitHub y sube los archivos de este directorio (`index.html`, `package.json`, `vercel.json`, `README.md`).
2. Entra a [Vercel](https://vercel.com) e importa tu repositorio.
3. Vercel detectará la configuración estática (`@vercel/static`) y desplegará la web automáticamente con un dominio gratis `.vercel.app`.

## 📊 Módulos Incluidos en el Dashboard (`index.html`)

1. **Mapa de Calor Interactivo (Leaflet.heat):** Visualiza la concentración absoluta y la incidencia relativa de suicidios por razones económicas y laborales por departamento y ciudad.
2. **Serie Temporal 2015–2026 (12 Años):** Gráfico combinado con doble eje Y que superpone la evolución del empleo, desempleo, precarización y formalidad con la curva anual de suicidios.
3. **Módulo de Clasificación de Riesgo de Salud Mental (Machine Learning):** Modelo predictivo supervisado (AUC-ROC 0.70) basado en perfilamiento de vulnerabilidad.
4. **Matriz de Agrupación Territorial (Clustering K-Means + PCA):** Clasificación en 3 clústeres socio-laborales para las 23 principales ciudades del país.
5. **Matriz Ejecutiva Completa:** Tabla navegable e interactiva con filtrado en tiempo real.
