---
title: Razonamiento bajo incertidumbre.
description: Introducción al cálculo y estimación de errores e incertidumbre
date: 2024-09-24 00:00:00 -0300
category: Machine-Learning Redes-Neuronales Razonamiento-Bajo-Incertidumbre 
tags:
  - markdown
  - jekyll
---

## Resumen de Tipos de Errores y Métodos

### Tipos de Errores

1. **Error Absoluto**: La diferencia entre el valor real y el aproximado. 
   - Fórmula: E_abs = |V_real - V_aprox|

2. **Error Relativo**: Es el cociente entre el error absoluto y el valor real.
   - Fórmula: E_rel = (|V_real - V_aprox|) / |V_real|

3. **Errores de Redondeo**: Ocurren debido a la limitación en la cantidad de cifras significativas que una computadora puede manejar.

4. **Errores de Truncamiento**: Surgen al usar una aproximación en lugar de una solución exacta.

5. **Errores de Propagación**: Se acumulan a lo largo de los cálculos intermedios y afectan el resultado final.

6. **Errores de Modelado**: Suceden cuando el modelo matemático no captura todas las características del fenómeno real.


## Pros y Contras de los Métodos de Errores


| Método                    | Pros                                                           | Contras                                                        |
|---------------------------|----------------------------------------------------------------|----------------------------------------------------------------|
| **Error Absoluto**         | Fácil de calcular e interpretar.                               | No toma en cuenta la magnitud relativa del valor.               |
| **Error Relativo**         | Útil para comparar errores en diferentes magnitudes.           | Puede ser grande o indefinido si el valor exacto es cercano a cero. |
| **Errores de Redondeo**    | Importante para cálculos numéricos con alta precisión.         | Acumula errores si se repite en múltiples cálculos.             |
| **Errores de Truncamiento**| Permite manejar problemas complejos de manera más simple.      | Introduce error al no calcular soluciones exactas.              |
| **Errores de Propagación** | Ayuda a comprender cómo los errores iniciales afectan el final.| Puede llevar a grandes inexactitudes si no se controla.         |
| **Errores de Modelado**    | Facilita la creación de modelos aproximados para problemas complejos.| No siempre refleja todas las características del fenómeno real.|


### Errores e Incertidumbre en IA

1. **Errores de Modelado**: No capturan todas las características del fenómeno físico o real, introduciendo incertidumbre.
2. **Errores de Redondeo**: Surgen debido a la precisión limitada en los cálculos.
3. **Errores de Truncamiento**: Relacionados con el uso de aproximaciones en lugar de soluciones exactas.
4. **Errores de Propagación**: La incertidumbre se propaga desde los errores en los datos de entrada.

### Métodos para Medir Incertidumbre en IA

1. **Métodos basados en probabilidad bayesiana**: Usan el teorema de Bayes para manejar la incertidumbre.
   - Fórmula: P(H|E) = (P(E|H) * P(H)) / P(E)

2. **Lógica difusa**: Maneja incertidumbre permitiendo grados de pertenencia.

3. **Factores de certeza**: Utilizados en sistemas expertos para manejar incertidumbre.

### Tipos de Razonamiento

1. **Razonamiento Deductivo**: Si las premisas son verdaderas, la conclusión también lo es.
2. **Razonamiento Inductivo**: Las premisas apoyan la conclusión, pero no la garantizan.
3. **Razonamiento Basado en la Incertidumbre**: Utiliza probabilidad e inferencia.

### Tabla de Pros y Contras de Métodos de Incertidumbre y Razonamiento

| Método                                | Pros                                                        | Contras                                                        |
|---------------------------------------|-------------------------------------------------------------|----------------------------------------------------------------|
| **Probabilidad Bayesiana**            | Cuantifica incertidumbre con distribuciones de probabilidad. | Requiere cálculos avanzados y puede ser costoso.               |
| **Lógica Difusa**                     | Maneja vaguedad e incertidumbre con grados de pertenencia.   | Resultados menos precisos, depende de reglas definidas.        |
| **Factores de Certeza**               | Cuantificación en sistemas expertos.                         | Depende de reglas preestablecidas.                             |
| **Razonamiento Deductivo**            | Conclusión válida si las premisas son verdaderas.            | No maneja bien la incertidumbre.                               |
| **Razonamiento Inductivo**            | Permite obtener conclusiones probables.                      | Las conclusiones no siempre son garantizadas.                  |
| **Razonamiento Basado en Incertidumbre** | Útil para escenarios inciertos.                              | Requiere manejo de datos probabilísticos complejos.            |

