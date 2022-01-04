Projeto medicina personalizada: Otimizando tratamento de c�ncer atrav�s de interpreta��o de diagn�stico m�dico assistido por machine learning

Este � um projeto da forma��o cientista de dados

O projeto visa fornecer uma maneira de auxiliar na detec��o de muta��es de tipos de c�ncer, para tal devemos nos valer de uma base de dados contendo
* Texto ==> Um texto descrevendo informa��es sobre o c�ncer encontrado em diversas amostras, anotadas por especialista humanos
* Gene ==> O gene analisado
* Variante ==> A variante � qual pertence a amostra analisada

O objetivo do projeto � encontrar � qual classe pertence a amostra analisada, basicamente existe uma muta��o gen�tica que pode ser classificada de diversas
formas, o que pode interferir no c�ncer 

A tarefa � gerar um classificador multi-classe que possa inferir � qual categoria pertence a amostra usando para isso tanto o texto quanto as outras informa��es
e Gene e Variante presentes no Dataset.

Trata-se portanto de um projeto que envolve PLN - Processamento de Linguagem Natural - mas n�o apenas isso, visto que existem vari�veis categ�ricas que
devem ser acomodadas pelo modelo de maneira a utilizar o m�ximo de dados poss�vel, produzindo assim um modelo com a maior acur�cia que pudermos proporcionar

Os Datasets de treino e de teste podem ser encontrados no link:

https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

N�o os inclui nesse reposit�rio devido ao seu tamanho

Como o objetivo desse projeto n�o � ser submetido ao Kaggle apenas o dataset de treino foi utilizado, visto que o dataset de teste n�o possui a coluna alvo
inviabilizando a avalia��o da acur�cia do modelo, dessa forma dividi os dados do dataset de treino em treino e teste e realizei o treinamento, bem como a 
avalia��o de acur�cia


Licen�a: Uso livre