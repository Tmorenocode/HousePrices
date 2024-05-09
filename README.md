# 3 modelos com resultados diferentes de uma competição do kaggle

## HousePrices

### 1° fase

Modelo inicial sem tratamento de dados

![image](https://github.com/Tmorenocode/HousePrices/assets/86325594/34cae3a5-c954-4133-b183-62c6ede8cae4)

- Nesta primeira fase, foi feito um modelo base para termos a titulo de comparação e ver o quanto podemos melhorar
- Sem ter feito nenhum tipo de tratamento na base de dados
- Foi utilizado 3 modelos de regressão sendo eles *KNN, árvore de descisão e regressão linear*
- O melhor resultado adquiro foi com o modelo *Regressão linear*

### 2° fase

<img src = "[https://github.com/Tmorenocode/HousePrices/blob/main/imagens/image.png](https://github.com/Tmorenocode/HousePrices/blob/main/imagens/resultado2.jpg)">

- Na 2° fase. Foi realizado uma limpeza dos dados na base
- Fazendo o tratamento dos valores nulos, utilizado conhecimento básico de estatistica
- Não foi necessário excluir nenhuma coluna
- Valores ausentes que não eram nulos, foi usado o valor -1 pra preencher
- Foi utilizado os modelos da etapa anterior e novamente a *Regressão linear* teve o melhor resultado

### 3° fase

<img src = "https://github.com/Tmorenocode/HousePrices/blob/main/imagens/resultado3.jpg">

- Nesta 3° fase. Foi feito uma análise explotória dos dados
- Analisado primeiramente a correlação das colunas
- Começamos o tratamento para transformar as principais colunas de textos para numéros
- Foi utilizado os modelos da etapa anterior e novamente a *Regressão linear* teve o melhor resultado

- ### Considerações finais
- O 2º modelo foi o que apresentou a menor taxa de erros
- 3° Modelo se tivesse um tratamento a mais nas colunas de texto, poderia apresentar um resultado melhor, mas iria demandar mais tempo
- Nitido a grande diferença do 1° modelo pros outros, mostrando a importancia do tratamento de dados.
