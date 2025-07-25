![Banner del proyecto](https://github.com/elenacampos89/Challenge_Alura_Store/blob/main/banner.png)



# 📊 Análisis de Rendimiento - Alura Store

Este proyecto es parte del Challenge de Análisis de Datos de Alura LATAM. El objetivo principal es analizar los datos de ventas de las 4 tiendas del Sr. Juan para recomendar cuál debería vender y así iniciar un nuevo emprendimiento.

---

## 🧠 Objetivo del Proyecto

El análisis se enfoca en:
- Evaluar los **ingresos**, **ventas**, **reseñas** y **envíos** de cada tienda.
- Identificar patrones por **categoría de producto** y **ubicación geográfica**.
- Determinar cuál tienda tiene **peor rendimiento**.
- Generar visualizaciones que respalden la recomendación final.

---

## 🗂 Estructura del Código

El análisis se organiza en bloques de código en un archivo `.ipynb` (notebook) con las siguientes secciones:

1. **Importación de datos**
2. **Análisis de facturación**: cálculo de ingresos totales por tienda
3. **Análisis por categoría de productos vendidos**
4. **Promedio de calificaciones por tienda**
5. **Productos más y menos vendidos por tienda**
6. **Costo de envío promedio**
7. **Gráficos comparativos finales (barras, pie y dispersión)**
8. **Distribución geográfica de ventas (lat/lon)**
9. **Conclusión y recomendación de la tienda a vender**
---


# 🧩 Archivos Incluidos

- tienda_1.csv, tienda_2.csv, tienda_3.csv, tienda_4.csv: Datos de ventas de cada tienda.

- AluraStoreLatam.ipynb: Notebook con el análisis paso a paso.

- README.md: Este archivo explicativo.

# 📌 Recomendaciones
Mantén todos los CSV en el mismo directorio que el .ipynb.

Si ejecutas en Colab, asegúrate de cargar los archivos antes de correr el análisis.

# ❓ Posibles Problemas

- Error de columna no encontrada: Asegúrate de que los archivos tengan el nombre correcto y no contengan espacios adicionales.
- Errores de visualización: Verifica que matplotlib esté correctamente instalado.
- Problemas con encoding: Agrega encoding='utf-8' al pd.read_csv() si usas archivos en español con caracteres especiales.

# ✅ Resultado Esperado
Al final del análisis, se determina qué tienda tiene el peor rendimiento global con base en métricas cuantitativas, visuales y geográficas, recomendando su venta con una justificación completa basada en datos.

# 👩‍💻 Autor
Desarrollado por Luz Elena Campos Díaz como parte del reto de formación en análisis de datos con Python - Alura LATAM.


