# brendas-cooking-club-powerbi
Projeto integrador feito no curso livre de Power BI do Senac Aclimação - Professor Gustavo Borges

Dashboard para gestão de um negócio de brownies: vendas, CMV (Método da Veri),
produção, perdas e estoque.

> ⚠️ Os dados de vendas, produção e estoque são **simulados** para fins didáticos.
> Os custos de ingredientes e a ficha técnica do brownie são baseados em dados reais.

## O que o projeto mostra
- Faturamento, ticket médio e margem bruta
- CMV teórico e CMV real (Estoque Inicial + Compras − Estoque Final)
- Taxa de perda na produção
- Giro e cobertura de estoque

## Ferramentas
Power BI · Power Query · DAX · Modelagem estrela (fatos e dimensões)

## Estrutura do modelo
Dimensões: Calendario, Produtos, Ingredientes
Fatos: Vendas, Producao, Estoque_Movimentos, Fichas_Tecnicas, Estoque_Saldo

## Prints
![Visão geral](imagens/01_visao_geral.png)
![CMV e margem](imagens/02_cmv_margem.png)

## Medidas DAX
Veja [dax/medidas.md](dax/medidas.md).
