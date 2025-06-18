# Avaliação das fontes de dados

1. Relação Principal entre os Arquivos:

- O arquivo Meganium_Sales_Data.txt contém essencialmente todos os registros de vendas do arquivo Updated_Anbernic_Sales_Data.txt, com apenas uma diferença no campo product_sold:
  - No Meganium_Sales_Data.txt: os produtos são identificados como “MEGANIUM” (ex.: NEW MEGANIUM RG35XX).
  - No Updated_Anbernic_Sales_Data.txt: os mesmos produtos aparecem como “ANBERNIC” (ex.: NEW ANBERNIC RG35XX).

2. Demais Campos:
  - Todos os outros campos (data, quantidade, preço unitário, preço total, moeda, site, cupom de desconto, valor do desconto, data de nascimento do comprador, nome do comprador, país de entrega, ID da fatura) são idênticos para os registros equivalentes nos dois arquivos.

3. Conclusão Principal:
  - O arquivo Meganium_Sales_Data.txt é uma versão do Updated_Anbernic_Sales_Data.txt com alteração apenas no nome da marca do produto.

4. Outras Fontes:
  - As fontes menores — Meganium_Sales_Data_-AliExpress.txt, Meganium_Sales_Data-Etsy.txt, Meganium_Sales_Data-_Shopee.txt — são subconjuntos ou variações parciais.
  - Nenhuma delas contém todos os registros da Meganium_Sales_Data.txt nem é totalmente contida por ela.
  - São arquivos relacionados, mas não equivalentes em abrangência de dados.


# Agrupamento por país e produto
![image](https://github.com/user-attachments/assets/e86990f3-55c2-4fd9-8f0b-913185f213fe)

# Continentes
Os países de entrega registrados nas vendas dos produtos Meganium (e Anbernic, cujos registros de vendas parecem ser idênticos aos da Meganium nas fontes fornecidas) incluem:
América do Norte:
◦ Estados Unidos (USA)
◦ Canadá

Europa:
◦ Alemanha (Germany)
◦ Reino Unido (UK)
◦ França (France)

Oceania:
◦ Austrália (Australia)

Ásia:
◦ Japão (Japan)


# Produto por continente
![image](https://github.com/user-attachments/assets/70cd93a3-f8d7-46ea-b614-817d0d2a5a01)



