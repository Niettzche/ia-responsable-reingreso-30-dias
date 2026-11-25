# Ciclo de vida de una IA responsable: reingreso hospitalario a 30 días

Notebook de referencia del reporte de la materia **Ética en IA** (Equipo 2).

`IA_Responsable_Reingreso_30_dias.ipynb` reproduce los resultados del reporte sobre una base de 100 pacientes
sintéticos, analizada como un solo conjunto:

- Tasas de reingreso por grupo y pacientes casi idénticos con desenlace opuesto.
- Matriz de correlación de Pearson.
- Árbol de decisión como auditor: reglas, importancia de variables, hiperparámetros y sensibilidad a ellos.
- Agente basado en distancias inicial (10 variables) frente al propuesto (sin el género): matrices de confusión,
  métricas por grupo y prueba contrafactual de género.
- Indicador de validez por consenso de los 5 casos más parecidos y dos casos de uso.

Requisitos: Python 3, `numpy`, `pandas`, `matplotlib`, `scikit-learn`.

Autor: Mario Ezequiel Verdugo Gordillo (2276504).
