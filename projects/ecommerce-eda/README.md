# EDA – Vendas de E-commerce (Exploração e Insights)

## Problema de negócio
Mapear padrões de compra, sazonalidade e produtos com baixa performance para orientar ações de marketing e estoque.

## Dados
- Fonte: dataset público (ex.: Olist, Kaggle ou simulado).
- Arquivos: `raw/` (bruto), `processed/` (limpo).
- Dicionário: coluna, tipo, descrição.

## Metodologia (pipeline)
1. Ingestão → 2. Limpeza/Tratamento (tipos, nulos, outliers) → 3. EDA (distribuições, correlações, sazonalidade) → 4. Insights → 5. Recomendações.

## Entregáveis
- Notebook `notebooks/eda_ecommerce.ipynb`.
- Gráficos principais em `reports/figures/`.
- Sumário executivo (`reports/summary.md`).

## Principais perguntas
- Quais produtos/linhas têm queda de desempenho?
- Existe sazonalidade relevante por mês/semana?
- Ticket médio por categoria e por período?
- Quais regiões/canais mais convertem?

## Stack
Python (Pandas, NumPy), Matplotlib/Seaborn/Plotly.

## Como rodar (local)
```bash
# criar venv (opcional)
python -m venv .venv && source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\Activate.ps1  # Windows (PowerShell)

pip install -r requirements.txt
jupyter lab  # ou jupyter notebook
