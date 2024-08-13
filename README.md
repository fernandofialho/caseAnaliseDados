# CaseDataAnalysis
Este projeto foca na análise de dados utilizando três bases distintas: ACCOUNT, TRANSACTION e RESPONSAVEL. O objetivo principal é verificar a conformidade com limites operacionais, calcular valores transacionados e avaliar se os responsáveis atingiram determinados objetivos de transação.

## Principais Funcionalidades
- Tratamento de Dados: Limpeza e conversão de dados das colunas críticas para garantir precisão na análise.
- Análise de Conformidade: Verificação se o número de contas associadas a cada responsável está dentro dos limites permitidos (max_account_load).
- Cálculo de Transações: Cálculo do valor total transacionado por cada responsável, incluindo segregação entre valores creditados e debitados.
- Avaliação de Metas: Determinação de quais responsáveis atingiram os objetivos de transação geral e de crédito.
- Cálculo de AUC: Avaliação do saldo final (AUC) das contas dos clientes em uma data específica.

## Tecnologias Utilizadas
- Python
- Pandas
- Power BI

## Exemplo de Saída
- Os resultados incluem informações detalhadas sobre o cumprimento de metas, valores transacionados e saldos finais (AUC) por responsável e cliente, fornecendo uma visão abrangente do desempenho e conformidade operacional.
