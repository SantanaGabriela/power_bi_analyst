# Desafio De Projeto Dio - Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

## Descrição do Desafio 🚀

Foi utilizada uma tabela única de Financial Sample(do prórpio BI) para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal forão criadas as tabelas:

Financials_origem (modo oculto – backup)

D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)

D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)

D_Descontos (ID_produto, Discount, Discount Band)

D_Detalhes (*)

D_Calendário – Criada por DAX com calendar()

F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))

## Processo de Criação 📚

A tabela ID_Produto foi criada apartir da opção agrupamento. As demais tabelas foram modeladas de forma manual, com as colunas informadas na descrição do desafio. 
A tabela D_Calendário foi criada atráves da linguagem DAX.



 

