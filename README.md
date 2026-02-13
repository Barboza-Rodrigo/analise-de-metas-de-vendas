# Avaliador de Metas de Vendas a partir de CSV (Python)

## Visão Geral
Este projeto implementa um sistema em Python para análise de desempenho de vendas a partir de um arquivo CSV, simulando um cenário real de avaliação de metas comerciais.

O sistema realiza validação de dados, cálculo de percentual de metas atingidas e classificação final do desempenho do time, seguindo regras de negócio bem definidas.

É um exemplo prático de automação de análise de dados simples, aplicável a contextos corporativos e freelancers.

---

## Funcionalidades
- Leitura de dados a partir de arquivo CSV
- Validação de dados de entrada
- Tratamento de valores inválidos (arquivo vazio ou valores negativos)
- Cálculo de percentual de metas atingidas
- Classificação automática do desempenho do time
- Geração de relatório final no terminal

---

## Regras de Negócio
- O arquivo CSV não pode estar vazio
- Valores negativos não são permitidos
- Classificação do desempenho:
  - **Excelente**: ≥ 80%
  - **Atingiu Expectativa**: 50% a 79%
  - **Abaixo do Esperado**: < 50%

---

## Tecnologias Utilizadas
- Python 3.x
- Biblioteca padrão (`csv`)

---

## Estrutura do Projeto

