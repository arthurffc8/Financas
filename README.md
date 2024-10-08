## Contexto e descrição

- Temos uma Base de Dados (`Base Financeiro.xlsx`) com histórico de transações e movimentações financeiras de uma empresa.
- A Base de dados fornece o número da movimentação, o nome juridico da pessoa, o município da sede da empresa da transação, o valor da movimentação, o tipo (se foi de recebimento ou pagamento), além do banco utilizado na movimentação.
- [DashboardFinanceiro](https://app.powerbi.com/view?r=eyJrIjoiODI4NjI2ZTYtMzE4ZC00MDYxLTk3OWItNTIxOGFhYWVlYjFlIiwidCI6ImRmY2E2YzQyLWM0NjktNDg1Ny05NDk5LWViN2YzNjczZjY4NCJ9): Este projeto realiza uma análise da popularidade dos filmes lançados ao longo do tempo. 


# Dashboard Financeiro

Clique na imagem para visualizar o dashboard interativo no Power BI:


[![ProjetoGame](https://github.com/arthurffc8/MeusProjetos/blob/main/ProjetoFinanceiro/DashFinanceiro.png)](https://app.powerbi.com/view?r=eyJrIjoiODI4NjI2ZTYtMzE4ZC00MDYxLTk3OWItNTIxOGFhYWVlYjFlIiwidCI6ImRmY2E2YzQyLWM0NjktNDg1Ny05NDk5LWViN2YzNjczZjY4NCJ9)



## Estrutura do Projeto

- **`Base Financeiro.xlsx`**; Arquivo com os dados utilizados na análise.
- **`DashboardFinanceiro.pbix`**; Dashboard com os insights obtidos.

  
## Ferramentas Utilizadas

- **Power Query**: Utilizado para limpar e modelar os dados.
- **Power BI**: Utilizado para criação das medidas, de dashboards interativos e visualizações avançadas.


  
## Principais Métricas calculadas e Insights 

- **Receita Total**: Utilizado a formula Calculate para somar as movimentações apenas do tipo recebimento.
- **Despesas**: Utilizado a formula Calculate para somar as movimentações apenas do tipo pagamento.
- **Impostos pagos**: Produto da Receita com 15% de impostos.
- **Lucro total**: Receita Total - Despesas - Lucro.
- **Margem de Lucro**: Divisão do Lucro pela receita.
- **Lucro por mês**: Um gráfico com lucro ou prejuízo em cada mês, terminando com o lucro acumulado no final do ano.
- **Desvio de Margem**: Informações da margem e o desvio de lucro de cada cidade, utilzando 30% como margem de lucro esperada.


 ## Dicas Adicionais 

 - **Filtros**: É possível filtrar todas as informações para cada Banco individualmente, basta clicar na imagem do Banco de interesse.
   



## Conclusão 

- **São Paulo com melhor desempenho**: São Paulo foi a cidade sede com maior desvio de margem, possuindo 33,6% de margem acima do esperado
- **NUbank e Safra com desempenhos opostos**: Enquanto o Banco NUbank teve um lucro próximo de zero, o Banco Safra obteve o melhor desempenho, inclusive obtendo lucro em todos os meses, acumulando um total de 77,54% de margem de lucro ao longo do ano.



