# Laboratório de Machine Learning no Azure IA - Modelo preditivo utilizando Regressão

Nesse projeto foram utilizadas diversas funcionalidades e opções oferecidas pela Azure IA para desenvolver um modelo preditivo de regressão, que prevê aluguéis de bicicletas baseado no Aprendizado de Máquina.
Após configurar corretamente o programa, usamos o Auto Machine Learning, que realiza o processo de análise dos dados e treinamento da Inteligência Artificial automaticamente, retornando um modelo testável no qual é possível predizer o número de aluguel de bicicletas dependendo dos dados fornecidos.

Vamos analisar melhor o processo:

### 1. Acesso e Início:

  Primeiramente, foi necessário criar uma conta na Azure e entrar nos serviços de IA, escolhendo o serviço de Machine Learning. Após isso, basta criar uma área de trabalho.

### 2. Configurações:

  Agora, iremos entrar na aba de recursos do Azure IA e selecionar o espaço de trabalho criado anteriormente para lançar um "estúdio". Feito isso, escolhemos a opção de Auto ML, colocamos nome e descrição e configuramos escolhendo o modelo de regressão. Em seguida,     baixamos o arquivo com os dados utilizados para treinar o modelo em:  https://aka.ms/bike-rentals, selecionamos esses dados e configuramos o modelo baseado no guia: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html.

### 3. Validação, Análise e Teste:

  Após congigurar corretamente, enviamos o modelo de treinamento e aguardamos o processo ser concluído. Então, assim que acabar, podemos ir na opção Métricas do nosso modelo, analisar o gráfico de "Predição vs Realidade" e um Histograma, e depois, implantar esse modelo para testá-lo com determinados valores.
