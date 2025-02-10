# Projeto de Cálculo de Métricas de Avaliação de Aprendizado
Nesse projeto apresento os resultados de métricas de avaliação para um modelo de classificação multiclasse com 10 classes. Tenho como objetivo calcular e visualizar as métricas de avaliação como a acurácia, sensibilidade (recall), F1-Score, matriz de confusão e curva ROC. Desenvolvi o código para ser executado no Google Colab e utilizo bibliotecas como TensorFlow, Pandas, NumPy, Seaborn e Matplotlib.

# Métricas Calculadas
* **Acurácia:** Proporção de previsões corretas em relação ao total de previsões.
* **Sensibilidade (Recall):** Proporção de verdadeiros positivos identificados corretamente.
* **F1-Score:** Média harmônica entre precisão e recall.
* **Matriz de Confusão:** Tabela que mostra os acertos e erros do modelo para cada classe.
* **Curva ROC:** Gráfico que mostra a taxa de verdadeiros positivos (TPR) em relação à taxa de falsos positivos (FPR).

# Bibliotecas
**Nesse projeto, utilizei as seguintes bibliotecas:**
* TensorFlow
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

# Resultados

![relatorio-classificacao](https://github.com/user-attachments/assets/7c4c3f28-79a7-4997-9906-eddf3fbcc067)

*Relatório de classificação* 


O relatório de classificação detalha as métricas de precisão, recall e F1-Score para cada classe, além da acurácia geral do modelo. Os resultados mostram um desempenho consistente em todas as classes, com valores próximos de 0.80 a 0.88.

   * Acurácia Geral: 82%

   * Precisão Média: 82%

   * Recall Médio: 82%

   * F1-Score Médio: 82%



![matriz-de-confusao](https://github.com/user-attachments/assets/680bf8f2-7fe1-424b-adb3-a9c20f9d9d62)

*Matriz de confusão*


A matriz de confusão demonstra os acertos e os erros nas previsões do modelo para cada classe. A maior parte dos acertos está concentrada na diagonal principal, indicando que o modelo está classificando corretamente a maioria das instâncias. Alguns erros ocorrem fora da diagonal, mas em quantidade pequena, o que é esperado em um modelo com bom desempenho.



![curva-de-roc](https://github.com/user-attachments/assets/a67a0058-7503-4c40-af80-0acfd6e7ebb6)

*Curva de ROC*


A curva ROC foi plotada para cada uma das 10 classes. As áreas sob as curvas (AUC) estão próximas de 0.98 a 0.99, indicando um excelente desempenho do modelo na distinção entre as classes.



