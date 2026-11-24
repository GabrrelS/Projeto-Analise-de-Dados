# Projeto de Análise de Dados — Principais Alimentos Produzidos no Brasil

Projeto acadêmico de análise de dados sobre a produção agrícola brasileira, desenvolvido com a metodologia DEILAS e apresentado em dashboards no Power BI.

## Disciplina

Análise de Dados e BI · Instituição: Centro Universitário de João Pessoa - UNIPÊ · Professor(a): Daniel dos Santos Brandão

## Sobre o projeto

O grupo escolheu o tema agronomia e focou nos cinco principais alimentos produzidos no Brasil, usando dados oficiais do IBGE. O objetivo é entender como a produção dessas culturas evoluiu ao longo do tempo e entre os estados.

# Culturas analisadas

Soja, Milho (em grão), Cana-de-açúcar, Café e Algodão herbáceo.

Período analisado: 2021–2025

## Metodologia utilizada

D.E.I.L.A.S

## Perguntas de negócio

1- Qual cultura cresceu mais dentro do atual top 5 de alimentos mais produzidos no Brasil
(Soja, Milho em grão, Cana de açúcar, Café e Algodão Herbáceo no período de 2021-2025)?

2- Quais estados cresceram mais proporcionalmente em cada cultura e quais deles foram os
mais produtivos no período de 2021-2025?

3- Desses estados, quais deles estão mudando a sua concentração de cultura e como eles
mudaram em relação ao Brasil no período de 2021-2025?

4- Quais estados e culturas tem maior risco de perda de safra?

5- Qual cultura gerou o maior valor de produção por hectare em cada estado no período de
2021-2025?

## Fonte dos dados

IBGE — SIDRA, tabela 5457 (Produção Agrícola Municipal): https://sidra.ibge.gov.br/tabela/5457

## Após coleta e limpeza

Bases tratadas:

df_colhida.csv, df_plantada.csv, df_produzida.csv, df_rendimento.csv, df_valor.csv e agrobd_tratada.csv (todas as bases juntas).

O dashboard foi construído no Power BI, com 5 páginas (cada uma feita por um integrante), uma para cada pergunta do D.E.I.L.A.S.

Arquivo: DashboardTodos.pbix

## Estrutura do repositório
```
Projeto-Analise-de-Dados/
├── dados/
│   ├── df_colhida.csv
│   ├── df_plantada.csv
│   ├── df_produzida.csv
│   ├── df_rendimento.csv
│   └── df_valor.csv
├── DashboardTodos.pbix
└── README.md
```
## Como usar

Clone o repositório:
```
bash
git clone https://github.com/GabrrelS/Projeto-Analise-de-Dados.git
```
Abra o arquivo DashboardTodos.pbix no Power BI Desktop.
Se o Power BI pedir, atualize os caminhos das fontes de dados na sua máquina (Transformar dados → Configurações da fonte de dados).

## Ferramentas utilizadas

Power BI e Google Colab

## Equipe

Artur Mota Gomes, Eduardo Pontes da Silva, Gabriel de Sousa, João Felipe Macêdo da Silva e Matheus Rodrigues da Silva.