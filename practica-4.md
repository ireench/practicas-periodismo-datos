# PRÁCTICA 4 – Periodismo de Datos 2022

##  Explicación de lo que se ha realizado en la práctica cuatro del curso.

### Realizado por Irene Acosta Huesca

En esta práctica se puede ver el notebook realizado a través de Jupyter aplicando lo aprendido en las clases y las prácticas de la asignatura de Periodismo de Datos. Para realizar la tarea debíamos escoger unos datos de un portal web de datos abiertos, en mi caso escogí el portal web [datos.gob.es, una iniciativa de datos abiertos del Gobierno de España](https://datos.gob.es/es). 

Escogí los datos en csv publicados en la web del Gobierno publicados por el Ayuntamiento de Rivas Vaciamadrid, yo en la práctica he querido hacer dos partes para practicar y complementar la información de la primera parte por ello encontramos dos conjuntos de datos (ambos del Ayuntamiento de Rivas Vaciamadrid): 

- [Conjunto de datos Bicinrivas](https://datos.gob.es/es/catalogo/l01281230-bicinrivas)
- [Conjunto de datos Rutas Verdes](https://datos.gob.es/es/catalogo/l01281230-rutas-verdes) De este seleccioné la ruta por la laguna del Campillo. 

Aunque las URLS de los csv las cogí de la propia página [web de datos Abiertos del Ayuntamiento de Rivas Vaciamadrid](https://datosabiertos.rivasciudad.es/). Estas son las dos URL utilizadas en el notebook de Jupyter: 

- Bicinrivas csv - url = https://datosabiertos.rivasciudad.es/dataset/8f444e87-99a9-453c-b4f6-74d72ddc6908/resource/09b242f7-1b58-413e-a492-f689244bf036/download/bicinrivas.csv
- Ruta laguna del Campillo csv - url =  https://datosabiertos.rivasciudad.es/dataset/78f9ffb3-1950-4feb-a154-be24e365541d/resource/8acb9b6b-a74a-499f-8985-802427aa7d09/download/campillo.csv

###¿Por qué se han usado dos conjuntos de datos?

Decidí realizar dos conjuntos de datos y por lo tanto dos partes en la práctica por dos razones. En primer lugar, para poder practicar más y aprender a utilizar bien las funciones e intentar aplicar nuevas, algunas como `folium.marker` si se han conseguido aplicar con éxito, otras como `folium.PolyLine` no. 

Además, consideré que si este trabajo de representación de datos lo estuviera realizando para un periódico o cualquier departamento de comunicación debía aumentar la información. En este caso escogí los datos con los estacionamientos de alquiler del servicio municipal Bicinrivas, por ello que mejor que escoger los datos de una ruta verde donde poder utilizar una bici alquilada. Escogí de todas las rutas verdes, la de la laguna del Campillo porque tiene la primera parada en el metro de Rivas Vaciamadrid y ahí también se encuentra un estacionamiento de alquiler de bicis. 

