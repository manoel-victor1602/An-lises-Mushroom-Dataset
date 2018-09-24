# Analises-Mushroom-Dataset
Algumas análises feitas no Mushroom Dataset

A partir das Análises do dataset foi percebido que há um conjunto de regras em que é possível aplicar para gerar um modelo que classifique corretamente todos os exemplos da base, tornando assim desnecessário o uso de Machine Learning, porém foi usado o modelo de Árvore de Decisão para tornar visível esse conjunto de regras, a árvore gerada pode ser visualizada no arquivo "arvore_gerada.png". 

Foi notado também que há alguns atributos que não agregam tanto para a classificação e usando seleção bidirecional esses atributos foram retirados da base, para provar que não afetam o resultado, a árvore foi treinada apenas com a base sem os atributos e pode-se ver que não houve perda de desempenho. 
