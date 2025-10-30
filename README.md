# BetaBank, Aprendizaje supervisado

📖 Resúmen:  
  -Entrenamiento y elección del mejor modelo con métricas f1-score y AUC-ROC para predecir los clientes potenciales que podrían abandonar el banco, de esta forma podríamos idear una estretegia para tratar de evitarlo.



🎯 Objetivo:  
  Identificar clientes potenicales que podrían abandonar el banco (cerrar sus cuentas).

❌ Problema:  
  Los clientes están comenzando a cerrar sus cuentas en el banco, para la institución se traduce a pérdidas de ingresos.

✅ Solución:  
  Creamos y probamos un modelo que identifica con buena exactitud que clientes podrían estarse planteando dejar el banco, de está forma podrían abordarlo y ofrecerle incentivos para que permanezca. 

🔢 Metodologia:  
  1- Formateo y limpieza de datos.  
  2- Codificación, segmentación y estandarización de datos para poder entrenar modelos.  
  3- Entrenamiento y elección de modelos (arbol de decisión, bosque aleatorio y regresión lineal) con diferentes balances de clases (desequilibrado, balanceado, sobremuestreo y combinado).  
  4- Finalmente aplicamos el modelo elegido a nuestro dataset de prueba y mostramos la conclusión.  

📊 Conclusiones:  
  Creamos un modelo que predice correctamente el 85.30% de los clientes que abandonarán (AUC score). Nuestro modelo también tiene una eficiencia entre recall y precisión del 59.97% (f1 score). 
  
