# Atividade 1 : 

### 1. Explique, com suas palavras, o que é machine learning?

Machine learning é um conjunto de técnicas que possibilita o desenvolvimento de modelos que resolvam problemas por meio do reconhecimento de padrões e de características entre os dados de forma que eles sejam relacionados e entreguem a resposta esperada. 

Uma exemplo, passando várias imagens para um modelo de forma que ele relacione padrões dos dados da imagem com o conteúdo. Uma forma de visualizar isso seria com a criação de 2 pastas, uma com fotos de gatos e a outra com fotos que não contém gatos, podemos então passar as imagens para o modelo de forma que ele aprenda a reconhecer se a foto contém ou não gatos.


### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

- O conjunto de treinamento é para treinar o modelo;
- O conjunto de validação (pelo que entendi) é usado para ir ajustando os hiper parâmetros durante o treinamento, isto é, avaliar o quão bem o modelo está generalizando para dados não vistos, se o modelo está enviesado ou não.
- O conjunto de testes é usado no final do treinamento do modelo, ele serve para testar se o modelo está conseguindo 'prever' as respostas direito.



### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Verificaria a relevância da coluna de dados e a porcentagem de dados faltantes, caso a coluna não apresenta-se muita relevância para o modelo ou houvesse uma quantidade muito maior de dados faltantes, removeria a coluna.

Caso a coluna de dados fosse relevante, analisaria os dados para encontrar algum valor que fizesse mais sentido, por exemplo, substituindo os valores faltantes por 0 ou vendo em linhas similares quais os valores mais relacionados, usando métricas como média e valores similares como base.


### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

É uma forma de visualizar o quão acurado o modelo está em suas previsões. Organizando valores entre os resultados esperados e os previstos, com base na relação entre eles é possível saber se o modelo estar acertando bem (verdadeiro positivo e verdadeiro negativo).

As vezes, por diversas questões, é preferível que um modelo tenha mais precisão nos seus acertos do que nos seus erros, por exemplo, no caso de uma detecção de uma doença grave, pode-se preferir ter um maior número de falsos positivos do que falsos negativos, isto é, identificar mais pessoas erroneamente doentes do que não detectar os que de fato estão doentes.


### 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos  de machine learning?

Jogos e geração de conteúdos audiovisuais. No caso de jogos em especifico, acredito que existe um potencial gigantesco na utilização de modelos de AI com ML para dar maior 'vivacidade' aos mundos virtuais, algo que acredito que vai trazer experiências incríveis nos próximos anos. Um exemplo que acho muito incessante sobre o assunto é o uso de ML com Behaviours Trees para dar vida ao Alien em Alien Isolation. 