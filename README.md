# Casos de Dengue — Brasil

## Visão Geral

Este projeto tem como foco a **análise exploratória dos casos de dengue no Brasil**. A partir da base de dados `Base de Dados Dengue.xlsx`, o estudo busca compreender a distribuição, tendências temporais e possíveis padrões dos casos de dengue no território nacional.

## Estrutura do Projeto

- **Dengue_Brasil.ipynb** — Notebook principal organizado nas seguintes seções:
  1. **Casos de Dengue — Brasil** (título)
  2. **Importando Bibliotecas** — carregamento das dependências e leitura dos dados
  3. **Desenvolvendo Análise** — etapa de exploração e visualização dos dados

## Dados

A base de dados utilizada (`Base de Dados Dengue.xlsx`) contém registros de casos de dengue. O notebook carrega os dados com `pandas.read_excel` e, em seguida, realiza manipulações para a análise exploratória.

## Ferramentas Utilizadas

| Biblioteca   | Finalidade                           |
| ------------ | ----------------------------------- |
| pandas       | Manipulação e tratamento de dados   |
| numpy        | Operações numéricas                 |
| seaborn      | Visualização estatística de dados   |
| matplotlib   | Criação de gráficos e visualizações  |
| plotly       | Gráficos interativos                |

## Como Executar

1. Abra o notebook `Dengue_Brasil.ipynb` no Databricks
2. Certifique-se de que o arquivo `Base de Dados Dengue.xlsx` esteja acessível no mesmo diretório
3. Execute as células na ordem apresentada

## Objetivos da Análise

- Compreender a evolução dos casos de dengue ao longo do tempo
- Identificar regiões ou períodos com maior incidência
- Visualizar padrões e tendências por meio de gráficos estatísticos e interativos