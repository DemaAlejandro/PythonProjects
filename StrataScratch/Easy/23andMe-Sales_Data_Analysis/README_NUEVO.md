# Sales Data Analysis

## Descripción del Proyecto

Este repositorio contiene un análisis exhaustivo de datos de ventas semanales (50 semanas) durante los años 2012 y 2013. El proyecto utiliza **Jupyter Notebook** para explorar patrones de ventas, cambios drásticos en el volumen de transacciones, análisis estadísticos y segmentación temporal.

## Preguntas Analizadas

1. **Visualización de ventas diarias** - Representación gráfica de las 50 semanas de datos
2. **Cambios drásticos** - Identificación de cuándo ocurren cambios significativos en las ventas
3. **Significancia estadística** - Prueba t de Student para validar cambios (p-valor)
4. **Análisis por género** - Impacto de la proporción hombre vs mujer en las ventas
5. **Análisis temporal** - Distribución de ventas por franjas horarias del día

## Datos

- **Total de datasets**: 50 archivos CSV (una semana cada uno)
- **Periodo**: Octubre 2012 - Septiembre 2013
- **Variables**: 
  - sale_time: Timestamp de la venta (YYYY-MM-DD HH:MM:SS)
  - purchaser_gender: Género del comprador (male/female)

## Hallazgos Clave

- **Cambio crítico**: 29 de abril de 2013 (p-valor < 0.01)
- **Patrón horario**: El mediodía (12PM-6PM) es la franja con mayor volumen (39.4% de ventas)
- **Tendencia de género**: Correlación negativa entre compras de hombres y mujeres

## Requisitos

`
pandas
matplotlib
scipy
jupyter
`

## Cómo Usar

1. Clona el repositorio
2. Instala los requisitos: pip install -r requirements.txt
3. Abre el notebook: jupyter notebook salesDA.ipynb
4. Ejecuta las celdas secuencialmente

## Nota Importante

✨ **Este repositorio ha sido subido completamente gracias al MCP de GitHub en VSCode** - Permitiendo la automatización del flujo de trabajo desde la integración directa con Visual Studio Code.

## Autor

Análisis realizado como parte del programa StrataScratch de ciencia de datos.

---

*Última actualización: Enero 2026*
