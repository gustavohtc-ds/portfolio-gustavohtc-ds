# Churn Prediction – Modelo Básico de Cancelamento de Clientes

## Problema de negócio
Empresas perdem receita quando clientes deixam de consumir (churn). Este projeto busca prever, com base em comportamento histórico, quais clientes possuem maior risco de cancelamento, permitindo ações de retenção proativa.

## Dados
- Colunas exemplo: frequência de uso, valor da última compra, tempo desde a última interação, número de chamados abertos, plano contratado.
- Fonte: dataset simulado ou público (ex.: Telecom Customer Churn - Kaggle).

## Metodologia (pipeline)
1. Limpeza e preparação dos dados  
2. Feature engineering (ex.: RFV – Recência, Frequência, Valor)  
3. Divisão entre treino e teste  
4. Criação de modelos baseline (Árvore de Decisão, Regressão Logística)  
5. Avaliação por métricas: Accuracy, Recall, Precision, F1, AUC ROC  
6. Análise de importância de variáveis  

## Entregáveis
- Notebook: `notebooks/churn_model.ipynb`
- Métricas comparativas em `reports/metrics.md`
- Possível curva ROC/Lift

## Perguntas de negócio
- Quais variáveis mais influenciam no churn?
- Qual grupo de clientes possui maior risco?
- Qual estratégia de retenção pode ser sugerida?

## Ferramentas
Python (Pandas, Scikit-Learn, Matplotlib/Seaborn)

## Roadmap
- [ ] Escolher dataset
- [ ] Criar baseline
- [ ] Interpretar variáveis
- [ ] Documentar plano de retenção
