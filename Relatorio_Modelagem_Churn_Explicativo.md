# Relatório — Modelagem Preditiva de Churn (TelecomX)

**Data:** 2025-08-19

Resumo do notebook `notebooks/TelecomX_Modelagem_Churn.ipynb`:
- Pré-processamento com One-Hot para categóricas; normalização quando necessário;
- Correlações e análises direcionadas (tenure, custos);
- Split estratificado; SMOTE opcional para balanceamento;
- Modelos: Logistic Regression e Random Forest; comparação por Acurácia, Precisão, Recall, F1 e ROC-AUC;
- Importâncias: coeficientes (LR) e feature_importances_ (RF);
- Geração de relatório HTML com métricas e insights.
