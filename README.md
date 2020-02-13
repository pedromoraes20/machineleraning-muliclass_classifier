# machineleraning-muliclass_classifier
Training an algorithm that allows 4 recommendations for agricultural machines.

Area:
Multiclass Classifier – Recomendações de ações de operação

Tags:
#statistics #python #jupyternotebook # supervisedlearning #multiclass-classifier #AWS #sagemaker

Briefing:
Esse é um caso bastante específico da agricultura. Quando chove, algumas fazendas ficam impossibilitadas de receber operações mecanizadas, além de oferecem riscos aos funcionários e a lucratividade do negócio. Por isso, baseado em algumas variáveis como umidade, chuva de dias anteriores, probabilidade de chuvas para o dia atual e seguinte, declividade do terreno e tipo de operação, foi treinado um algoritmo que possibilita 4 recomendações para essas situações. Esse projeto foi realizado com produtos AWS, mais precisamente o Sagemaker, que viabiliza um notebook jupyter onde pode-se usar a linguagem python para programação.
Como não posso expor detalhes que identifiquem o cliente, seguem outras coisas que posso mostrar.

Codes:
Código para treinamento do algoritmo do tipo multiclass_classifier em instância ml.m4.xlarge, com número de classes para treinamento = 4 (quatro rótulos).

Observação: algumas partes do código precisam ser retiradas para não identificar o cliente. :(
