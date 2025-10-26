# Dashboard Executivo (BI) – Vendas e Marketing

## Objetivo
Consolidar KPIs de vendas, receita, ticket médio e retenção em um dashboard visual para apoiar decisões estratégicas de gestão e marketing.

## Escopo
- ETL simples (Power Query no Power BI ou pipeline Python → CSV).
- Tabelas de suporte: Fato Vendas, Dim Produto, Dim Tempo, Dim Cliente.
- Métricas: Receita total, Ticket médio, Crescimento mensal, Conversão.

## Entregáveis
- Arquivo principal: `dashboard.pbix` (ou versão Streamlit).
- Print dos visuais em `reports/figures/`.
- Manual de leitura (`docs/guia.md`).

## Principais KPIs
| Indicador | Descrição |
|-----------|-----------|
| Receita total | Total faturado no período |
| Crescimento % | Comparação mês a mês |
| Ticket médio | Receita média por pedido |
| Churn % | Clientes perdidos no período |
| CAC/LTV (opcional) | Custo de aquisição vs valor vitalício |

## Ferramentas
Power BI (principal) | Python (opcional para pré-processamento)

## Roadmap
- [ ] Montar base de dados (simulada ou real - ex.: Olist)
- [ ] Criar modelo dimensional (Star Schema)
- [ ] Desenvolver visuais
- [ ] Criar storytelling analítico
- [ ] Disponibilizar prints e documentação
