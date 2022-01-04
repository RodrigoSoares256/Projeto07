Projeto medicina personalizada: Otimizando tratamento de câncer através de interpretação de diagnóstico médico assistido por machine learning

Este é um projeto da formação cientista de dados

O projeto visa fornecer uma maneira de auxiliar na detecção de mutações de tipos de câncer, para tal devemos nos valer de uma base de dados contendo
* Texto ==> Um texto descrevendo informações sobre o câncer encontrado em diversas amostras, anotadas por especialista humanos
* Gene ==> O gene analisado
* Variante ==> A variante à qual pertence a amostra analisada

O objetivo do projeto é encontrar à qual classe pertence a amostra analisada, basicamente existe uma mutação genética que pode ser classificada de diversas
formas, o que pode interferir no câncer 

A tarefa é gerar um classificador multi-classe que possa inferir à qual categoria pertence a amostra usando para isso tanto o texto quanto as outras informações
e Gene e Variante presentes no Dataset.

Trata-se portanto de um projeto que envolve PLN - Processamento de Linguagem Natural - mas não apenas isso, visto que existem variáveis categóricas que
devem ser acomodadas pelo modelo de maneira a utilizar o máximo de dados possível, produzindo assim um modelo com a maior acurácia que pudermos proporcionar

Os Datasets de treino e de teste podem ser encontrados no link:

https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

Não os inclui nesse repositório devido ao seu tamanho

Como o objetivo desse projeto não é ser submetido ao Kaggle apenas o dataset de treino foi utilizado, visto que o dataset de teste não possui a coluna alvo
inviabilizando a avaliação da acurácia do modelo, dessa forma dividi os dados do dataset de treino em treino e teste e realizei o treinamento, bem como a 
avaliação de acurácia


Licença: Uso livre