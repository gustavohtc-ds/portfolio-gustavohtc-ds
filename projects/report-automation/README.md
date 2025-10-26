# Automação de Relatórios – Python

## Objetivo
Gerar e enviar relatórios periódicos (PDF/HTML/Excel) de forma automática para reduzir trabalho operacional.

## Casos de uso
- Relatório semanal de vendas
- Ranking de produtos por período
- Alerta de anomalias (queda brusca de vendas)

## Stack
Pandas, openpyxl/xlsxwriter, Jinja2/WeasyPrint (HTML→PDF), SMTP.

## Entregáveis
- `src/generate_report.py`
- Templates em `templates/`
- Amostras em `reports/`

## Roadmap
- [ ] Template base (HTML/Excel)
- [ ] Automação e parâmetros
- [ ] Envio por e-mail (SMTP)
- [ ] Logs e documentação
