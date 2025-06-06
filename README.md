# Índice de Pobreza no Brasil (2012–2022)

Este projeto apresenta uma análise descritiva do índice de pobreza no Brasil, com foco em tendências gerais e por grupos específicos.

## 🎯 Objetivo

Analisar como o índice de pobreza evoluiu ao longo de uma década, destacando grupos como indígenas, quilombolas e ciganos.

## 📁 Estrutura

- `dados/`: contém o arquivo `.csv` com os dados
- `scripts/`: script em R com toda a análise
- `imagens/`: gráficos gerados pela análise

## 🛠️ Ferramentas

- R
- tidyverse
- ggplot2
- readr
- janitor

## 📊 Resultados

- A taxa de pobreza caiu entre 2012 e 2014, mas voltou a crescer a partir de 2015.
- Povos indígenas e quilombolas apresentaram índices significativamente superiores.

![Exemplo de gráfico](imagens/grafico_linhas_pobreza.png)

## 🚀 Como rodar

1. Instale os pacotes listados em `pacotes_utilizados.R`
2. Execute `scripts/analise_descritiva.R`
