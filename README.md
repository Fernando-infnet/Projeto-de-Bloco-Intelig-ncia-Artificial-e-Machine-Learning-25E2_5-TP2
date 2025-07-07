# O modelo utilizado
Foi utilizado o algoritmo K-Nearest Neighbours (KNN) para classificar as notícias como falsas ou reais. Para isso, primeiro foi convertido as notícias para um formato numérico utilizando o TF-IDF, que destaca as palavras mais importantes de cada texto.

Para encontrar o melhor valor de “K” (o número de vizinhos que o KNN considera), testamos valores de 1 a 20. Descobrimos que um “K” menor geralmente leva a uma melhor precisão. No entanto, mesmo com o melhor “K”, nosso modelo alcançou apenas cerca de 56% de precisão em valores em torno de 2.

Isto sugere que simplesmente confiar no TF-IDF com KNN não é suficiente para distinguir com precisão notícias falsas de notícias reais. Técnicas mais avançadas, como aprendizagem profunda ou processamento de texto mais sofisticado, podem ser necessárias para melhorar o desempenho.

# Conclusões
Apesar dos resultados, é possível notar que o uso do conteúdo das notícias para se assegurar de estar real ou falso, não tem uma acuracidade alta, devido às próprias palavras usadas não apresentarem tanta conexão, como por exemplo 'trump' ser tanto associado à notícias reais quanto associado à notícias falsas, e não em diferentes posições, ambos ocupando o primeiro lugar de real e falso.
