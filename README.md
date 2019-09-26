# Taller API Transporte

Repositorio del taller "Monitoreando la ciudad en tiempo real" realizado en Media Party 2019 para uso de la [API de Transporte de la Ciudad de Buenos Aires](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte).

## Requisitos

Para poder usar el servicio de la API de Transporte es necesario solicitar las credenciales (client_id y client_secret) lo cual puede hacerse en [esta página](https://www.buenosaires.gob.ar/form/formulario-de-registro-api-transporte)

Para ver todos los servicios disponibles podés consultar la [API Doc](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte/api-doc).

Cualquier duda o consulta podés escribir a [apitransporte@buenosaires.gob.ar](mailto:apitransporte@buenosaires.gob.ar).

## Scripts
Los siguientes scripts están desarrollados en [Python 3.6](https://www.python.org/downloads/release/python-360/) y permiten hacer las siguientes consultas a la API:

* **[Consultar arribos y partidas de colectivos en una parada determinada](https://github.com/datosgcba/taller-api-transporte/blob/master/colectivos-arribos-partidas.ipynb)**
Este servicio brinda información sobre colectivos que llegan y parten desde una determinada parada, ingresando, además de las credenciales personales, el id de la parada. 
Dentro del ítem “colectivos”, acceder al título “arrivals-and-departures-for-stop”.

* **[Consultar eventos en la vía pública](https://github.com/datosgcba/taller-api-transporte/blob/master/eventos.ipynb)**
Búsqueda de información de eventos por mes en vía pública de la Ciudad Autónoma de Buenos Aires. Los eventos incluyen cortes de tránsito programados, hasta manifestaciones y embotellamientos, entre otros. 
Dentro del ítem “tránsito”, acceder al título “eventos”.
