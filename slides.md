<!-- $theme: default -->

# Quien soy
- 15 años desarrollando Ground Segments de satellites Desde Landsata hasta Sentinel)

- Desde el 2006 en el mundo del GFOSS con contribuciones a GRASS
Desde entonces trabajando con QGIS

- Fundadór del Italian OSGeo Local Chapter, GFOSS.it

- Contributor al core de QGIS desde años con bug fix y nuevas funcionalidades (WMS legend, SLD)

- Desarrolaldor portador de muchos plugins

- Trainer de PyQGIS

- hace poco Desarrollando un producto baseado en QGIS de una empresa de EEUU.

---
# Co-author de Mastering QGIS (Packt)
<img src="images/Cover-MasteringQGIS.png" alt="Drawing" style="width: 500px"/>

---
# Modelo de negocio de QGIS

---
## Se puede vivir vendendo SW libre?

En orden de importancia: Como hacemos negocio con SW Geografico libre?

1. Customización (adaptar GUI, plugins, añadir botones, facilitar el trabajo)
2. Suporte (Resolver problemas, 24/7 support)
3. Bug Fix (Del core o de plugins)
4. Producto/Paquetización (relacionado con el suporte)
---
## Sanguijuelas o Contribudoras

En General hay que elegir si:
* estar en la comunidad
* ser como las mayoria que usa SW libre sin devolver

### Hay poco grados intermedio. Ejemplo

* devuelvo solo si me da una ventaja de marketing o imagen
* Devuelvo para que lo demas me hagan el testeo
* Devuelvo si me lo permite el cliente (GPL)
---
## Casos de exito de los que estan en la comunidad

Hay empresas grandes y pequeñas que basan sus negocios sobre QGIS o GFOSS

* CampToCamp
* OSLandia 
* 3Liz
* SourcePole
* itOpen
* NaturalGIS
* BoundlessGeo ?????
---
# Comunidad de desarrollo y usuarios
---
## Participar, ayudar y recibir ayuda
* Reportar fallos - http://hub.qgis.org/issues
* Ayudas - In ML o en freenode #qgis channel
* Lista de fallos: https://github.com/qgis/QGIS/pulls
* Traducír - http://qgis.org/en/site/getinvolved/translate.html
* en Castillano QGIS-es: http://lists.osgeo.org/cgi-bin/mailman/listinfo/qgis-es
---
## Los Hackmeetings

<img src="images/HackmeetingNodebo.png" alt="Drawing" style="width: 600px;"/>

* La parte mas divertida
* Se aprende mucho
* Proximo  20-25 February 2018, Madeira (Pt)
---
## Como se decide en QGIS	
* PSC es la Dirección general (no tecnica)
* Committers
* Un representante para cada UserGroup (y en ES?)
* QEP https://github.com/qgis/QGIS-Enhancement-Proposals
---
# PyQGIS o cómo extender QGIS
---
## Que es PyQGIS

### QGIS is wrote in (www.openhub.net/p/qgis):
* C++ (almos all)
* Python (some core plugins)
* Javascript (some parts in Plugin Manager)
### SIP Bind
95% of C++ API can be accessed by Python thanks to SIP
https://wiki.python.org/moin/SIP
 
PyQGIS Cookbook
http://docs.qgis.org/2.18/en/docs/pyqgis_developer_cookbook/
http://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/

---

### APIs
* C++ - http://qgis.org/api/
* Python - http://qgis-python.kartoza.com/docs/
http://geoapis.sourcepole.com/qgispyapi/
https://webgeodatavore.github.io/pyqgis-samples
---
### La mejor escuela: Leer el codigo de los plugins
Una metodo de aprendizaje
* Buscar el o los plugins mas similares
* Instalarlos
* Estudiar el codigo en ~/.qgis2/python/plugins/\<plugin name\>
* Hay mas de 800 plugins en el repo oficial, y mucho mas...
---
## Necesito un Plugin o Uno script de Processing?
* Necesito un plugin? soy capaz?
  * Conocimiento de Python
  * Conocimiento de Programación a Objectos
  * Conocimeintos de QT
* Y si hago uno script de Processing?
  * Solo conocimiento de Python
  
  * puedo aprender desde otros scripts o modelos
---
