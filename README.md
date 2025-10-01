# R-Nvidia-Stock-Forecast-Arima

## Descripción

Análisis de series de tiempo y pronóstico del precio de cierre de las acciones de NVIDIA (NVDA) utilizando modelos ARIMA. El proyecto incluye modelado estadístico, pruebas de estacionariedad, selección de modelos y pronósticos a futuro.

## Objetivos

- Analizar el comportamiento histórico del precio de NVIDIA (2015-2025)
- Desarrollar modelos ARIMA para pronosticar precios futuros
- Evaluar diferentes configuraciones de modelos
- Identificar el mejor modelo mediante criterios de información (AIC/BIC)

## Datos

- **Fuente**: Yahoo Finance via `quantmod`
- **Ticker**: NVDA
- **Periodo**: Enero 2015 - Febrero 2025
- **Frecuencia**: Mensual
- **Variable**: Precio de cierre ajustado

## Metodología

1. **Exploración inicial**: Análisis visual y pruebas de estacionariedad
2. **Diferenciación**: Aplicación de diferencias para lograr estacionariedad
3. **Modelado**: Comparación de 6 modelos ARIMA diferentes
4. **Selección**: Evaluación mediante AIC y BIC
5. **Validación**: Análisis de residuos y pronósticos


## Autor

- José Luis Corona López

## Referencias

- **Hamilton, J. D. (1994).** *Time Series Analysis*. Princeton University Press.
- **Yahoo Finance** - Fuente de datos históricos de NVIDIA


