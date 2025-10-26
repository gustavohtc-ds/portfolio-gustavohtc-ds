# Web Scraping de Preços – Concorrência

## Objetivo
Coletar preços de produtos/concorrentes e gerar uma série temporal para monitorar variações e auxiliar decisões de precificação.

## Stack
Python (Requests, BeautifulSoup, Pandas). Respeitar `robots.txt` e termos de uso.

## Pipeline
Agendador (cron/Task Scheduler) → Scraper (`src/scraper.py`) → CSV/Parquet (`data/`) → Análise (`notebooks/`).

## Entregáveis
- `src/scraper.py` (MVP de coleta)
- Amostras em `data/`
- Painel simples (opcional: Streamlit)

## Roadmap
- [ ] Scraper MVP
- [ ] Normalização de categorias
- [ ] Série temporal e gráfico
- [ ] Painel simples (Streamlit, opcional)
