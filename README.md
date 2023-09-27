# Tratando dados e definindo KPIs para uma Loja de Varejo

## Introdução
Uma loja de varejo deseja criar algumas métricas para acompanhar seus resultados. Para tal, ela disponibiliza de duas bases de dados: uma de vendas e outra de clientes.

## Objetivo do projeto
O objetivo do projeto é fazer todo o tratamento e união das bases para construção das seguintes métricas de negócio:
* Departamentos mais vendidos;
* Média de preço com frete por Nome de Departamento;
* Quantidade de vendas por mês;
* Média de renda dos clientes para cada tipo de canal de venda;
* Média de idade de clientes por bandeira.

## Premissas do Negócio
* Tem-se um erro de sistema: para compras sem UF, considere o estado do MS;
* Preço não pode ser maior que o preço com frete.