# Classificador de Imagens com CNN (Convolutional Neural Network)

Este projeto utiliza uma rede neural convolucional (CNN) para classificar imagens do dataset CIFAR-10. O objetivo é construir um modelo capaz de classificar as imagens em 10 classes diferentes (avião, automóvel, pássaro, gato, etc.), utilizando técnicas de **data augmentation**, **regularização** e **normalização**.


## Visão Geral

Este projeto foi desenvolvido como parte do aprendizado de **redes neurais convolucionais (CNNs)** e serve para classificar imagens de diferentes categorias presentes no CIFAR-10, um conjunto de dados amplamente utilizado para treinamento de modelos de aprendizado de máquina.

A rede neural foi construída com a biblioteca **TensorFlow**, com as seguintes principais características:
- **Data augmentation** para aumentar a variabilidade dos dados de treinamento.
- **Batch normalization** para normalizar os valores de ativação estabilizando e acelerando o treinamento.
- **Regularização** com **dropout** para reduzir o overfitting.
- **Arquitetura de rede** com múltiplas camadas convolucionais e camadas densas.

---

## Análises e Resultados

Após o treinamento foram geradas as seguintes métricas:

- **Acurácia no conjunto de teste**: 76.17%
- **Loss no conjunto de teste**: 0.71

---

### Gráficos e Visualizações

Para entender melhor o desempenho do modelo, foram gerados os seguintes gráficos e análises:

- **Curvas de Acurácia e Loss**: Gráficos mostrando a evolução do modelo ao longo das interações de treinamento, ajudando a visualizar possíveis problemas de overfitting ou underfitting.
- **Matriz de Confusão**: Demonstra como o modelo classifica cada categoria do CIFAR-10, identificando quais classes são mais confundidas.
- **Previsões Erradas**: Algumas previsões incorretas foram visualizadas para analisar onde o modelo falhou e quais padrões ele teve dificuldade de aprender.


