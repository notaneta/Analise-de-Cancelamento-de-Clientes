# Análise de Cancelamento de Clientes

Projeto de estudo em análise de dados com Python. O objetivo é descobrir
quantos clientes cancelaram a assinatura e quais fatores mais influenciam
o cancelamento.

## Sobre a base de dados
- 50.000 clientes, 12 colunas (idade, sexo, tempo como cliente, frequência
  de uso, ligações ao call center, dias de atraso, tipo de assinatura,
  duração do contrato, total gasto, meses desde a última interação e
  se cancelou)

## O que foi feito
1. Importação e visualização da base com Pandas
2. Remoção de colunas inúteis (CustomerID) e de linhas com valores vazios
3. Análise inicial: quantidade e porcentagem de clientes que cancelaram
4. Análise detalhada: histogramas interativos com Plotly, comparando cada
   coluna com o cancelamento
5. Aplicação de filtros com base nos padrões encontrados e comparação da
   taxa de cancelamento

## Principais resultados
- Cerca de 57% dos clientes cancelaram a assinatura
- Todos os clientes com contrato mensal cancelaram
- Clientes com mais de 4 ligações ao call center tendem a cancelar
- Clientes com mais de 20 dias de atraso tendem a cancelar
- Ao filtrar esses perfis, a taxa de cancelamento cai para cerca de 18%

## Ações sugeridas
- Oferecer desconto em contratos anuais e trimestrais
- Alerta para clientes com 3 ligações ao call center
- Alerta para clientes com 15 dias de atraso

## Tecnologias
Python, Pandas, Plotly, Jupyter Notebook

## Como executar
pip install -r requirements.txt
Abra o arquivo Analise_de_Dados.ipynb e execute as células.

## Créditos
Projeto desenvolvido com base no Python Intensivão da Hashtag Treinamentos.