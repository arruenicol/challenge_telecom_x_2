# 📊 Telecom X (2) - Análisis Predictivo de Cancelación

## 🎯 Descripción
Proyecto de machine learning para predecir la cancelación de clientes en telecomunicaciones, identificando patrones de abandono y proporcionando estrategias de retención basadas en datos.

## 🏆 Resultados Clave
- **Modelo**: Random Forest con **60.8% F1-Score**
- **Detección**: **71.1% recall** (identifica abandonos reales)
- **Precisión**: **75.6%** accuracy general
- **AUC-ROC**: **0.84** (excelente capacidad discriminativa)

## 📋 Dataset
- **7,032 registros** con 22 características
- **Desbalance**: 73.4% retención vs 26.6% abandono
- Variables: datos demográficos, servicios, facturación y comportamiento

## 🔧 Metodología
1. **Preprocesamiento**: Limpieza, encoding categórico, normalización
2. **Feature Engineering**: SelectKBest para 20 características óptimas
3. **Balanceo**: SMOTE para equilibrar clases
4. **Modelado**: Comparación Random Forest, Logistic Regression, KNN
5. **Validación**: División estratificada 70/30 con validación cruzada

## 🔑 Factores Críticos de Abandono
1. **Método de Pago - Cheque Electrónico** (22.0%)
2. **Meses de Antigüedad** (16.8%) 
3. **Servicio Fibra Óptica** (12.0%)
4. **Tipo de Contrato** (10.0%)
5. **Cargos Totales** (9.1%)

## 🎯 Estrategias Recomendadas
- **Migración a autopago** con descuentos del 5-10%
- **Programa de fidelización** por antigüedad
- **Soporte especializado** para servicios premium
- **Contratos de mayor duración** con beneficios

## 🛠️ Tecnologías
- **Python**: pandas, numpy, scikit-learn
- **Visualización**: matplotlib, seaborn
- **ML**: Random Forest, SMOTE, feature selection
- **Evaluación**: ROC-AUC, matriz de confusión, validación cruzada


## 📈 Impacto Esperado
- **Reducción de churn**: 15-25%
- **Mejora en retención**: De 73.4% a 80-85%
- **ROI**: 3:1 en intervenciones proactivas
- **Ahorro**: 20% en costos de adquisición


## ⭐ Autoría
- 👤 [arruenicol](https://github.com/arruenicol) 
- **Desafío**: Telecom X - Análisis de Evasión de Clientes
- **Fecha**: 08/2025
