# PAC2 Visualitzacio de dades
Orígen de les dades:
- Birds: https://data.world/data-ny-gov/tk82-7km5 
- Oil consumption: https://data.world/brianray/gapminder-oil-consumption-per
- Bitcoin: https://data.world/petroniocandido/bitcoin

Aquest paquet està format pels següents arxius:

- _Representacions visuals de cada tècnica:_

  - `Pyramid_Chart_Birds.png`: _Pyramid Chart_ del nombre d'espècies d'ocells de la comarca de Chautauqua que es troben en classificats en els diferents estatus de conservació.
  - `Slope_Chart_Oil_consumption.png`: _Slope Chart_ dels 10 païssos pels anys 1985 i 2010.
  - `OHLC_Chart_Bitcoins_Nov2017-May2018.png`: _Open-High-Low-Close Chart_ del valor del _Bitcoin_ per un període de temps més redüit (entre novembre de 2017 i Maig de 2018).

- _Datasets amb les dades:_

  - `Slope_chart/Oil_consumption_per_person.csv`: dataset original amb les dades de consum de combustible per persona en tones per any.
  - `Slope_chart/oil_consumption_per_QueryResult.csv`: dades filtrades per 10 païssos (_Algeria_, _Germany_, _China_, _Brazil_, _India_, _Japan_, _Russia_, _Spain_, _United States_, _Saudi Arabia_).

  - `Pyramid_chart/biodiversity-by-county-distribution-of-animals-plants-and-natural-communities-1.csv`: dataset original amb dades de biodiversitat amb la distribució d'animals, plantes i comunitats naturals segons la comarca.
  - `Pyramid_chart/count_chautauqua_birds_QueryResult.csv`: dades filtrades per totes les espècies d'ocells de la comarca de Chautauqua, Nova York.
  - `Pyramid_chart/Chautauqua_birds_QueryResult.csv`: dades agrupades segons l'estatus de conservació de les espècies d'ocells de la comarca de Chautauqua.

  - `OHLC_chart/BTCUSD.csv`: dataset original amb les dades del valor del bitcoin entre el 2011 i el 2019.
  - `OHLC_chart/Bitcoins_2011-2019.png`: OHLC chart per tot el dataset (entre el 2011 i el 2019).
  - `OHLC_chart/Bitcoins_Nov2016-Sep2018.png`: OHLC chart per un període més reduït (entre Novembre de 2016 i Setembre de 2018).
  - `OHLC_chart/Bitcoins_Sep2017-Feb2018.png`: OHLC chart per un període més reduït (entre Setembre de 2017 i Febrer de 2018).

A més, es pot visitar l'enllaç https://public.tableau.com/app/profile/estrella.fernandez/viz/Bitcoin_data/Sheet1 on està publicat el gràfic original de les dades de Bitcoins, on de manera intercativa es pot modificar el període de temps que es vol visualitzar.
