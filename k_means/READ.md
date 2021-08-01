# K-Means

K-Means é, na verdade, um dos algoritmos de agrupamento não supervisionado mais simples. Suponha que temos pontos de dados de entrada x1, x2, x3,…, xn e valor de K (o número de clusters necessários). 
Seguimos o procedimento abaixo:

1) Escolha K pontos como os centróides iniciais do conjunto de dados, aleatoriamente ou o primeiro K.

2) Encontre a distância euclidiana de cada ponto no conjunto de dados com os K pontos identificados - centróides do cluster.

3) Atribua cada ponto de dados ao centróide mais próximo usando a distância encontrada na etapa anterior.

4) Encontre o novo centróide tomando a média dos pontos em cada grupo de cluster.

5) Repita 2 a 4 para um número fixo de iterações ou até que os centróides não mudem.

-> O ponto onde essa distorção diminui mais é o ponto do cotovelo e esse será o K ideal.
