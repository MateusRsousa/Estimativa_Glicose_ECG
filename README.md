# Estimativa_Glicose_ECG

O monitoramento dos níveis de glicose é essencial para prevenir doenças e sintomas associados à hiperglicemia e à hipoglicemia. O diabetes, por exemplo, está entre as doenças que
mais causam mortes no mundo, tornando o acompanhamento contínuo da glicose sanguínea uma prática indispensável para pessoas diagnosticadas com a condição. No entanto,
os métodos tradicionais de medição são, em sua maioria, invasivos, causam desconforto,
dor e exigem a coleta de amostras de sangue, o que pode dificultar o monitoramento
frequente. Diante disso, cresce o interesse em pesquisas que buscam estimar os níveis de
glicose de forma não invasiva. Este estudo propõe o uso de sinais de eletrocardiograma
(ECG), obtidos por meio de um dispositivo vestível, para estimar a glicose sanguínea.
O conjunto de dados foi desenvolvido especificamente para este projeto e envolve etapas de pré-processamento e filtragem dos sinais, extração de características relevantes
e treinamento de modelos de aprendizado de máquina, com o objetivo de desenvolver
uma abordagem precisa, prática e menos desconfortável para o monitoramento contínuo
da glicose. Os modelos com melhor performance foram Random Forest, com erro RMSE
de 11.295 e MAPE de 8,63% e 93% das estimativas na Zona A do Gráfico de Clarke, e
o modelo Gradient Boosting, com erro RMSE de 11.768 e MAPE de 9,09% e 84% das
estimativas na Zona A. O modelo CatBoost também chegou próximo, com RMSE e MAPE
iguais a 12.512 e 9,53% e 81% das estimativas na Zona A. Portanto, os resultados deste
trabalho reforçam que variações nos níveis glicêmicos afetam características morfológicas
do sinal de eletrocardiograma.
