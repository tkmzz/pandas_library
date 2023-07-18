# pandas_library

#O dataset de varejo que temos em mãos é composto por informações de vendas de uma loja virtual que atua em todo o território naciona, vendendo produtos de diferentes departamentos. Além disso, a loja atual em diferentes canais de venda, como marketplace, loja própria, entre outros.

Premissas do negócio:
Ao analisar os dados, é importante ter em mente que existem algumas premissas de negócio que devem ser consideradas. A primeira deles é que, devido a um erro no sistema, algumas compras não possuem informações de UF. Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul(MS). A segunda premissa é que o preço final de um produto não pode ser maior do que o preço com frete.

Métricas:
Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informaçãos pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preço com frete por Nome de departamento: Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem desejada.
3. Qtd de vendas por mês: Analisando a qtd de vendas realizadas em cada mês, podemos identificar sazonalidade no comportamento de compra e planejar campanhas de marketing específicas para cada período.
4. Média de renda para cada tipo de canal de venda: Identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a adotar uma campanha de marketing e vendas para cada público-alvo.
5. Média de idade de clientes por bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar os mesmos para atender melhor cada público.
