# 📊Resiliencia Inversa ante Rating Downgrade

Detección de absorción institucional tras noticias negativas

## 📌Descripción del Proyecto

Este proyecto identifica un comportamiento anómalo y altamente informativo del mercado: situaciones en las que, tras un Rating Downgrade, el momentum (RSI) de una acción aumenta de forma significativa, en lugar de colapsar como dictaría la lógica tradicional.

Este fenómeno sugiere que el mercado ya había descontado el peor escenario y que la noticia negativa actúa como un evento de limpieza de incertidumbre, habilitando compras agresivas por parte de manos fuertes.

## 🎯Insight Principal

- ¿Qué empresas muestran una recuperación inmediata del momentum tras un downgrade de rating, indicando resiliencia estructural y posible acumulación institucional?

Un RSI que sube con fuerza después de una mala noticia es una señal contraria potente:
- El riesgo ya estaba en precio
- El downgrade no sorprende
- La demanda supera rápidamente a la oferta

## 🧠Hipótesis de Mercado

Normalmente, un Rating_Downgrade provoca:
- Venta masiva
- Caída del precio
- Deterioro del momentum

Este modelo busca el caso opuesto:
- El RSI sube más de 15 puntos en los días posteriores
- Señal de sobreventa previa extrema
- Probable reacumulación institucional

## 🧩Metodología

- Se seleccionan eventos corporativos de tipo Rating_Downgrade.

Se compara el RSI:

- Día anterior al evento
- Dos días posteriores al evento

Se filtran únicamente los casos donde:
- El RSI posterior supera al previo en más de 15 puntos
- Se devuelve información contextual de la empresa para análisis cualitativo adicional.

## 🗂️Fuentes de Datos

- eventos_corporativos
- tipo_evento = Rating_Downgrade
- indicadores_tecnicos
- RSI de 14 períodos
- tickers
- Nombre de la empresa

## 📈Output del Modelo

El resultado identifica empresas que presentan:
- Downgrade oficial de rating
- Mejora abrupta del momentum inmediatamente después

Potencial señal de:
- Fin de capitulación
- Cambio de régimen
- Oportunidad contraria de alta calidad

## 💼Valor de Negocio

📉 Estrategias contrarian avanzadas

🏦 Detección de compras institucionales encubiertas

🔍 Filtro de falsas noticias negativas

🌍 Apoyo a decisiones de value investing táctico

🧠 Complemento ideal para análisis fundamental

## ⚠️Consideraciones

No implica señal automática de compra

Debe combinarse con:
- Contexto fundamental
- Liquidez
- Estructura de mercado

Funciona mejor en:
- Acciones líquidas
- Mercados desarrollados

## 🚀Extensiones Futuras

- Validar impacto en precio a 5 y 10 días
- Cruzar con volumen anómalo
- Analizar efecto por sector o país
- Incorporar cambios en skewness y kurtosis post-evento

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
