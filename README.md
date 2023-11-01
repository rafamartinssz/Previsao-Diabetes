# Previsao Diabetes - Machine Learning
# Objetivo

O objetivo desse projeto é desenvolver modelos de predição utilizando Machine Learning para prever se um paciente, de acordo com suas características, tende a ter diabetes ou não, além de descobrir quais características que mais contribuem e influenciam uma pessoa a ter diabetes. Esse trabalho tem apenas fins acadêmicos, porém, pode servir para auxiliar auxiliar profissionais da saúde a identificar indivíduos em risco, permitindo intervenções preventivas ou diagnósticos mais rápidos.

# Como funciona

Inicialmente, o código recebe uma base com 100 mil dados médicos de pacientes, juntamente com seu estado de diabetes, dentre eles a idade do paciente, o gênero, hipertensão, doenças cardíacas, histórico de tabagismo, IMC, nível de açúcar no sangue, nível de glicose e se possui diabetes ou não.

No pré-processamento dos dados, podemos ver a distribuição das principais varáveis da base. Além disso, apliquei a técnica One-Hot Encoding para transformar todas as váriáveis categóricas em variáveis numéricas, visto que os modelos não trabalham com texto. Por fim, normalizei dos dados utilizando o método Min-Max Scaler, para garantir que todas as características tenham o mesmo peso nos algoritmos.

Portanto, treinei os modelos e apliquei eles na base de teste, tendo bons resultados e acurácias altas. Após isso, concluí de acordo com os resultados os pontos importantes, que estão na apresentação e no notebook do projeto de forma detalhada.

# Modelos usados

Os seguintes modelos foram utilizados no projeto:

- Árvore de Decisão, com aproximadamente 94,9% de acurácia
- Regressão Logística, com aproximadamente 95,8% de acurácia
- k-NN (K-Nearest Neighbors), com aproximadamente 95,7% de acurácia

Mais detalhes de cada modelo na apresentação e no notebook.

# Resultados

Para testar o modelo, criei uma base de dados fictícia igual a original com 15 pacientes, manipulei para que os 5 primeiros tenham características de pessoas que possuem diabetes, os próximos 5 com características de pessoas que não possuem diabetes, e os últimos 5 com dados aleatórios. Os 3 modelos acertaram todos os pacientes com características manipuladas, e tiveram resultados bem semelhantes com as aleatórias.

# Detalhes

- **Arquivos necessários**: para rodar sem problemas, deixe os arquivos `diabetes_prediction.csv` e `diabetes_prediction_test.csv` na mesma pasta do código.
- **Acurácia**: vale lembrar que, mesmo com todo esse trabalho, a IA não é perfeita e pode errar nas previsões, esse é apenas um projeto para predições de diferentes modelos.
- Todas as informações estão mais detalhadas no notebook do projeto e na apresentação em slides.
