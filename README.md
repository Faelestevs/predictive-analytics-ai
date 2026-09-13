# Previsão de Evasão Escolar baseada em Renda Média (Brasil)

Repositório destinado ao Projeto da Disciplina de Inteligência Artificial (7°J SI - Noite) da Faculdade de Computação e Informática da Universidade Presbiteriana Mackenzie.

## Integrantes do Grupo
* Guilherme Silva Dias (RA: 10427415)
* Raffael Rodrigues Esteves (RA: 10420414)
* Ricardo Carvalho Paixa Brandão (RA: 10376918)

## Descrição do Dataset
O dataset "Abandono Escolar por Renda Média (Brasil 2013-2023)" utilizado neste projeto cruza dados abertos de duas fontes governamentais:
* **INEP:** Taxas de Rendimento Escolar (focando nas métricas de abandono).
* **IBGE (PNAD):** Rendimento médio mensal real por nível de instrução (Tabela 7443).

Os dados estão anonimizados e agregados por região e estado. O objetivo é utilizar estes dados para treinar modelos preditivos de Machine Learning utilizando a biblioteca `scikit-learn` (Opção Framework) para identificar e prever o impacto socioeconômico na retenção escolar.

## Arquivos da Entrega N1
* `AbandonoEscolar_RendaMedia_2013_2023.csv`: Base de dados utilizada.
* `analise_exploratoria.ipynb`: Notebook em Python contendo a Análise Exploratória de Dados (EDA), limpeza, tratamento e visualização das correlações.
