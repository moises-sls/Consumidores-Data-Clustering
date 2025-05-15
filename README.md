# consumidores-data-clustering
Dados: https://archive.ics.uci.edu/dataset/502/online+retail+ii

Foi desenvolvido um modelo de aprendizado de máquina não supervisionado para a criação de diferentes perfis para os clientes de uma loja, possibilitando uma análise mais aprofundada e permitindo a criação de estratégias direcionadas a tipos específicos de clientes.

Utilizei a biblioteca Pandas e o KMeans clustering para trabalhar com mais de 500.000 transações presentes no banco de dados.

As métricas utilizadas foram: Gasto Monetário Total do cliente, durante um ano completo, Frequência de Compras, e Recência, ou seja, quantidade de dias desde a sua última compra na loja. Utilizei o "método do cotovelo" e a medida "Silhouette Score" para definir o número de Clusters.

Entre os clientes que não foram categorizados como outliers, quatro grupos distintos foram criados. Já entre os outliers, três grupos foram definidos.
