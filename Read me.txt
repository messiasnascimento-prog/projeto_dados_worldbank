# Investimento Público em Educação e Desemprego na América Latina

**Disciplina:** EAE1106 – Métodos Computacionais para Economia  
**Prof.:** Arthur Viaro — USP, 1º Semestre de 2026  
**Autor:** Messias Victor Assunção Ribeiro do Nascimento

## Pergunta de pesquisa
Existe relação entre o gasto público em educação (% do PIB) e a taxa de 
desemprego nos países da América Latina na última década?

## Fonte dos dados
World Bank Open Data API — indicadores:
- `SE.XPD.TOTL.GD.ZS` — Gasto público em educação (% do PIB)
- `SL.UEM.TOTL.ZS` — Taxa de desemprego (% da força de trabalho)

Os dados são obtidos automaticamente via biblioteca `wbgapi`. 
**Não há dados tratados no repositório** — o código reconstrói tudo a partir da API.

## Como reproduzir
1. Instale as dependências: `pip install wbgapi pandas matplotlib seaborn scipy`
2. Execute o notebook `analise_banco_mundial_FINAL.ipynb` célula por célula

## Estrutura do repositório
- `analise_banco_mundial_FINAL.ipynb` — código completo (coleta, limpeza, análise)
- `relatorio_final.pdf` — relatório final