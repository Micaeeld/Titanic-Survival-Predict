# Previsão de Sobrevivência no Titanic
Este notebook apresenta uma previsão de sobrevivência no Titanic, utilizando um conjunto de dados disponibilizado no Kaggle. O conjunto de dados contém informações sobre os passageiros a bordo do Titanic, incluindo idade, gênero, classe, entre outros. O conjunto de dados específico usado neste projeto pode ser encontrado em https://www.kaggle.com/competitions/titanic/data.

## Conjunto de dados
O conjunto de dados é composto por 891 linhas e 12 colunas. As colunas incluem:

- ID do passageiro: identificador único do passageiro
- Sobreviveu: indica se o passageiro sobreviveu ou não (0 = não sobreviveu, 1 = sobreviveu)
- Classe: classe do passageiro (1 = primeira classe, 2 = segunda classe, 3 = terceira classe)
- Nome: nome do passageiro
- Gênero: gênero do passageiro (masculino ou feminino)
- Idade: idade do passageiro
- Número de irmãos/cônjuges a bordo
- Número de pais/filhos a bordo
- Ticket: número do bilhete do passageiro
- Tarifa: valor da tarifa do passageiro
- Cabine: número da cabine do passageiro
- Porto de embarque: porto de embarque do passageiro (C = Cherbourg, Q = Queenstown, S = Southampton)

## Preparação dos dados
Antes de criar o modelo de previsão de sobrevivência, os dados foram pré-processados e preparados para o treinamento. Algumas das etapas de preparação de dados incluem:

- Limpeza de dados ausentes e valores atípicos
- Codificação de recursos categóricos
- Normalização dos dados
- Modelo de previsão de sobrevivência
Para prever a sobrevivência no Titanic, foi utilizado o modelo GradientBoostingClassifier. O modelo foi treinado utilizando as características dos passageiros como variáveis independentes e a sobrevivência como variável dependente.

Os resultados mostraram que o modelo apresentou uma acurácia de 84%.

## Conclusão
Este notebook apresentou uma previsão de sobrevivência no Titanic utilizando um conjunto de dados disponibilizado no Kaggle. O modelo de Árvore de Decisão foi capaz de prever com precisão se um passageiro sobreviveu ou não com base em suas características pessoais. A previsão de sobrevivência pode ser útil para empresas de seguro que desejam avaliar o risco de viagens marítimas.


## Contribuição

Contribuições são bem-vindas! Se você encontrar algum bug ou tiver alguma sugestão de melhoria, abra um problema no repositório ou envie uma solicitação de pull.
uma solicitação de pull.
