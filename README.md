# previsao-valores-de-casas
 1 - Introdução:
 Esse é um exercício prático de regressão para prever preços de imóveis, usando um modelo de Machine Learning treinado com dados reais. O dataset utilizado foi o
blob:https://www.kaggle.com/44dbf339-0030-4ac2-9ea6-7cd03da89551

2 - Problema e Dados:
 O dataset veio do kaggle com 13 colunas e 545 linhas com a variável alvo sendo "prices"
usei algumas lógicas que já foram utilizadas antes em outro projeto meu feito em grupo (também no meu github) mas tive que dessa vez ir além do teórico, então nessa semana eu aprendi sozinho o que fazer, principalmente com videos e pequenos exercícios.

3 - O que eu fiz: 
- Tratei as variáveis categóricas (sim/não) transformando-as em valores numéricos (Assim como meu trabalho de previsões de atrasos disponível também no meu github)
- Separei dos dados em conjunto de treino (80%) e teste (20%) (Assim como o outro trabalho idem)
- Treinei um modelo de Regressão Linear com Scikit-learn
- Avaliei o modelo utilizando as métricas MAE e R²
- Testei o modelo com um exemplo de casa inventada, para validar se a previsão fazia sentido

4 - Resultados:
- MAE (erro médio absoluto): ~R$ 1.029.305
- R² (quanto o modelo explica da variação do preço):0.6048

O modelo conseguiu capturar relações reais entre as características dos 
imóveis e o preço, mas ainda tem uma parte significativa de variação não 
explicada, provavelmente por fatores fora do dataset (como localização e etc) 
ou pela limitação de um modelo linear diante de relações mais complexas.

5 - Sobre o processo:
Esse foi um desafio diferente do que eu já tinha feito antes. Tive que 
estudar por conta própria conceitos de regressão e novas funções de pandas 
ao longo da semana, assistindo vídeos e praticando até conseguir aplicar 
tudo na prática, célula por célula, entendendo cada etapa do processo, minha vantagem foi saber como funciona transformar variáveis strings em números pra máquina, mas ainda assim foi um aprendizado bem interessante.
6 - Tecnologias que usei:
- Python
- Pandas
- Scikit-learn

7 - Possíveis melhorias:
-Testar outros modelos, como Random Forest (Que vi depois que seria possível embora eu não saiba como fazer)
- Normalizar variáveis com escalas muito diferentes entre si
- Incluir mais dados e variáveis, como localização do imóvel e proximidade com o centro da cidade, praias e etc











