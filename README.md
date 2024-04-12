Projeto de Rede Neural para Reconhecimento de Imagens
Descrição
Este projeto implementa uma rede neural convolucional (CNN) para reconhecimento de imagens. A rede é treinada usando o conjunto de dados MNIST para reconhecimento de dígitos escritos à mão. A implementação utiliza a biblioteca TensorFlow para construir e treinar a rede neural.

Arquivos do Projeto
train.py: Script Python para treinar a rede neural.
test.py: Script Python para testar a rede neural com novas imagens.
model.py: Definição da arquitetura da rede neural.
utils.py: Funções utilitárias para carregar e pré-processar os dados.
requirements.txt: Lista de dependências do projeto.
Arquitetura da Rede Neural
A rede neural implementada é uma CNN com a seguinte arquitetura:

Camada de convolução (32 filtros, tamanho do kernel 3x3)
Camada de max pooling (tamanho do pool 2x2)
Camada de convolução (64 filtros, tamanho do kernel 3x3)
Camada de max pooling (tamanho do pool 2x2)
Camada totalmente conectada (128 neurônios)
Camada de saída (10 neurônios para classificação de dígitos de 0 a 9)
