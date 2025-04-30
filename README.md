# Fiap Sprint2

### Como acessar o Google Collab
Basta Clicar no arquivo "Lucas_Da_Fonseca_Costa_rm560575.ipynb" acima.

### Dataset utilizado
O Dataset utilizado é o "satveg_planilha.xlsx" que se encontra acima. O dataset foi obtido atráves do site https://www.satveg.cnptia.embrapa.br/satveg/login.html, com a área escolhida da fazenda tropical Lon: -52.67208 Lat: -21.0026

### Variaveis chaves escolhidas
NDVI_max - Valor máximo anual — indica pico da produtividade vegetal

NDVI_mean_growing - NDVI médio durante o ciclo de crescimento

Start of Season (SOS)- Mês em que a vegetação começa a crescer (NDVI > limiar[0.55])

End of Season (EOS) - Mês em que a vegetação deixa de crescer

Length of Season - Duração do período vegetativo (EOS - SOS)

NDVI_std_growing - Variabilidade do NDVI na estação — sensível a estresse hídrico, pragas

### Modelo escolhido

Random Forest → RMSE: 2.37, R²: 0.25

SVR → RMSE: 1.85, R²: 0.55

KNN → RMSE: 1.93, R²: 0.50

Regressão Linear → RMSE: 0.95, R²: 0.88

Como podemos observar acima a regressão Linear teve o melhor desempenho tanto em precisão (menor RMSE) quanto em capacidade explicativa (maior R²), SVR e KNN apresentaram desempenhos medianos, e por ultimo, a random forest foi a que apresentou o pior desempenho
