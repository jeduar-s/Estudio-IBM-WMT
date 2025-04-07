# Estudio de Correlación entre IBM y Walmart

## Objetivo
Analizar la relación entre los precios de las acciones de IBM y Walmart utilizando análisis de series temporales, con el fin de evaluar su grado de correlación y comportamiento conjunto en el tiempo.

---

## Tabla de Contenidos
- [Introducción](#introducción)  
- [Fuente de Datos](#fuente-de-datos)  
- [Análisis de Correlación](#análisis-de-correlación)  
- [Series Temporales](#series-temporales)  
- [Conclusiones](#conclusiones)  
- [Requisitos](#requisitos)  
- [Uso](#uso)  
- [Contribuciones](#contribuciones)  
- [Autor](#autor)

---

## Introducción
El estudio busca determinar si existe una relación significativa entre el comportamiento de las acciones de IBM y Walmart, lo cual podría tener implicaciones para estrategias de inversión o diversificación de portafolios.

---

## Fuente de Datos
- **Origen:** Yahoo Finance u otras fuentes financieras confiables.
- **Símbolos analizados:** `IBM` y `WMT`.
- **Periodo sugerido:** Diario o mensual entre 2015 y 2024 (según disponibilidad de datos).

---

## Análisis de Correlación
Se aplican las siguientes técnicas:
- Cálculo del coeficiente de correlación de Pearson.
- Visualización de precios históricos.
- Análisis de dispersión entre precios de ambas acciones.

---

## Series Temporales
- Descomposición de series para identificar tendencias, estacionalidad y ruido.
- Análisis cruzado para comparar comportamiento temporal.
- Discusión sobre posibles causas de similitudes en la evolución de precios.

---

## Conclusiones
- **Correlación:** Se observa una correlación positiva de aproximadamente **0.9274** entre ambas series.
- **Patrones comunes:** Ambas acciones tienden a moverse de forma similar, aunque operan en industrias diferentes.
- **Diferencias clave:** Las mayores diferencias se observan en la volatilidad y volumen de transacciones.

---

## Requisitos

```bash
pip install pandas numpy matplotlib seaborn statsmodels yfinance
```

---

## Uso
1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/ibm-walmart-correlacion.git
```
2. Abre el notebook:
```bash
jupyter notebook "estudio de IBM y WMT.ipynb"
```
3. Ejecuta las celdas para descargar los datos, visualizar los resultados y calcular la correlación.

---

## Contribuciones
¿Deseas mejorar el análisis incluyendo más empresas, técnicas avanzadas de cointegración o predicción?  
¡Tus aportes son bienvenidos! Abre un issue o envía un pull request.

---

## Autor
**José Eduardo Saucedo Martínez**  
