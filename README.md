# biblioteca_pandas

# o dataset de varejo que temos em mãos é composto por informações de vendas de uma loja virtual que atua em todo territorio nacional, vendendo produtos de diferentes departamentos. alem diso, a loja atua em diferentes canais de vendas, como marketplace, loja propria, entre outros.

premissas de negocio:
Ao analisar os dados, é importante lembrar que tem premissas de negocios que devem  ser consideradas. A primeira delas é que, devido a um erro no sistema, algumas compras  nao possuem informações de UF (Unidade Federativa).Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado do Mato Grosso do Sul(MS). A segunda é que o preço final de um produto não pode sr maior que o preço final com frete.

Métricas
Com base nesse contexto e nas premissas de negocios estabelecida, podemos avaliar as seguintes metricas:

1.Departamento mais vendido
2.Média de preço com frete por nome de departamento
3.Quantidade de vendas por mes
4.Média de renda por cada tipo de canal de venda
5.Média de idade de clientes por bandeira
