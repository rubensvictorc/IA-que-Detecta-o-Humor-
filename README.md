# IA-que-Detecta-o-Humor-

Este código é um exemplo de como você poderia começar a escrever um código para uma IA que detecta o humor usando Python e a biblioteca Keras. Ele importa as bibliotecas necessárias, incluindo a biblioteca Keras, que é usada para construir e treinar o modelo de IA. Em seguida, ele carrega o conjunto de dados de treinamento e teste, normaliza os dados e converte os rótulos para categóricos, que é necessário para o treinamento do modelo.

Em seguida, ele cria o modelo usando uma arquitetura de rede neural chamada Sequential, que é composta de camadas de convolução, ativação, pooling, dropout e camadas densas. As camadas de convolução e pooling são usadas para extrair características das imagens, enquanto as camadas densas são usadas para fazer a classificação final. As camadas de ativação e dropout são usadas para melhorar a capacidade de generalização do modelo.

Em seguida, ele compila e treina o modelo usando uma função de perda categórica cross-entropia e otimizador Adam. Por fim, ele avalia o modelo testando-o no conjunto de teste e imprimindo a perda e a precisão do teste.
