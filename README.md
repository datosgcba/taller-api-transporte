# Taller API Transporte

En el año 2019 se realizaron dos talleres para aprender a consultar cuestiones de movilidad en la API de Transporte. Uno, en Python 3.6 en el marco del Media Party. Y un segundo, en Rstudio en conjunto con EANT y la Subsecretaría de Movilidad de la Ciudad de Buenos Aires. 
En este repositorio pueden encontrarse los scripts y las presentaciones realizadas para ambos. 

# Repositorios y presentaciones

Repositorio del taller [Monitoreando la ciudad en tiempo real](https://docs.google.com/presentation/d/1IFS0DU3VdWO9ZgTIrKbabCRSRQ66XpRI8GqBGYtz01E/edit?usp=sharing) realizado en la [Media Party 2019](https://mediaparty.info/) para fomentar el uso de la [API de Transporte de la Ciudad de Buenos Aires](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte).

Repositorio del taller [Api Transporte + Mapas] (https://drive.google.com/open?id=1b84-l6OFpzg2mQZofUW2M2lGwv7ACoib) realizado en conjunto con [EANT](https://eant.tech/home) y la [SS de Movilidad](https://www.buenosaires.gob.ar/movilidad) para enseñar y fomentar el uso de la [API de Transporte de la Ciudad de Buenos Aires](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte).

## Requisitos

Para poder usar el servicio de la API de Transporte es necesario **[solicitar las credenciales (client_id y client_secret)](https://www.buenosaires.gob.ar/form/formulario-de-registro-api-transporte).**

Para ver todos los servicios disponibles podés consultar la [API Doc](https://www.buenosaires.gob.ar/desarrollourbano/transporte/apitransporte/api-doc).

Cualquier duda o consulta podés escribir a [apitransporte@buenosaires.gob.ar](mailto:apitransporte@buenosaires.gob.ar).

## Scripts
Los siguientes scripts están desarrollados en Python 3.6 (https://www.python.org/downloads/release/python-360/) y Rstudio, y permiten hacer las siguientes consultas:

* **[Consultar arribos y partidas de colectivos en una parada determinada](https://github.com/datosgcba/taller-api-transporte/blob/master/colectivos-arribos-partidas.ipynb)**

Este servicio brinda información sobre colectivos que llegan y parten desde una determinada parada, ingresando, además de las credenciales personales, el id de la parada, en Python 3.6. 
Dentro del ítem “colectivos”, acceder al título “arrivals-and-departures-for-stop”.


* **[Consultar eventos en la vía pública](https://github.com/datosgcba/taller-api-transporte/blob/master/eventos.ipynb)**

Búsqueda de información de eventos por mes en vía pública de la Ciudad Autónoma de Buenos Aires. Los eventos incluyen cortes de tránsito programados, hasta manifestaciones y embotellamientos, entre otros en Python 3.6. 
Dentro del ítem “tránsito”, acceder al título “eventos”.


* **[Consultar cortes de tránsito](https://github.com/datosgcba/taller-api-transporte/blob/master/cortes.ipynb)**

Datos sobre cortes en la vía pública de la Ciudad Autónoma de Buenos Aires, por día. Realizado en Python 3.6.
Dentro del ítem “tránsito”, acceder al título “cortes”.


* **[Consultar  reglas de estacionamiento de un determinado punto de la ciudad](https://github.com/datosgcba/taller-api-transporte/blob/master/estacionamiento.ipynb)**

Acceso a información de estacionamiento en vía pública para un tramo de una calle de la Ciudad Autónoma de Buenos Aires. Dado un punto y un radio, busca información de estacionamiento en esa área circular, en Python 3.6.
Dentro del ítem “tránsito”, acceder al título “estacionamiento”.

* **[Consultar estaciones de bicicletas públicas en la Ciudad](https://github.com/datosgcba/taller-api-transporte/blob/master/Estaciones_bicicletas_publicas.Rmd)**

Script para la recolección de a información sobre estaciones de Ecobici en la Ciudad Autónoma de Buenos Aires, realizado en el marco del taller de la API de Transporte en conjunto con EANT y SS Movilidad en R. 


## Reutilización

Si utilizás la API de Transporte para desarrollar una aplicación, hacer una visualización o un análisis te invitamos a compartirnosla!
Podés enviarnos un mail a [gobiernoabierto@buenosaires.gob.ar](mailto:gobiernoabierto@buenosaires.gob.ar) o twittearla y mencionar a [@BAGobAbierto](https://twitter.com/BAGobAbierto).

En [data.buenosaires.gob.ar/historias-con-datos](https://data.buenosaires.gob.ar/historias-con-datos) podés ver todos los desarrollos usando datos abiertos!

