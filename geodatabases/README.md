# Geodatabases
Una base de datos espacial (spatial database) es un sistema administrador de bases de datos que maneja datos existentes en un espacio o datos espaciales.

En este tipo de bases de datos es imprescindible establecer un cuadro de referencia (un SRE, Sistema de Referencia Espacial) para definir la localización y relación entre objetos, ya que los datos tratados en este tipo de bases de datos tienen un valor relativo, no es un valor absoluto. Los sistemas de referencia espacial pueden ser de dos tipos: georreferenciados (aquellos que se establecen sobre la superficie terrestre. Son los que normalmente se utilizan, ya que es un dominio manipulable, perceptible y que sirve de referencia) y no georreferenciados (son sistemas que tienen valor físico, pero que pueden ser útiles en determinadas situaciones).

La construcción de una base de datos geográfica implica un proceso de abstracción para pasar de la complejidad del mundo real a una representación simplificada que pueda ser procesada por el lenguaje de las computadoras actuales. Este proceso de abstracción tiene diversos niveles y normalmente comienza con la concepción de la estructura de la base de datos, generalmente en capas; en esta fase, y dependiendo de la utilidad que se vaya a dar a la información a compilar, se seleccionan las capas temáticas a incluir.

La estructuración de la información espacial procedente del mundo real en capas conlleva cierto nivel de dificultad. En primer lugar, la necesidad de abstracción que requieren los computadores implica trabajar con primitivas básicas de dibujo, de tal forma que toda la complejidad de la realidad ha de ser reducida a puntos, líneas o polígonos.

En segundo lugar, existen relaciones espaciales entre los objetos geográficos que el sistema no puede obviar; la topología, que en realidad es el método matemático-lógico usado para definir las relaciones espaciales entre los objetos geográficos puede llegar a ser muy compleja, ya que son muchos los elementos que interaccionan sobre cada aspecto de la realidad.

## Geodatabase de ESRI

En su nivel más básico, una geodatabase de ArcGIS es un conjunto de datasets geográficos de distintas clases que están almacenados en una carpeta común del sistema de archivos o en un sistema de administración de bases de datos relacionales multiusuario, como IBM Db2, Microsoft SQL Server, Oracle, PostgreSQL o SAP HANA. Las geodatabases pueden tener muchos tamaños, poseer un número variado de usuarios y ser bases de datos pequeñas de un solo usuario creadas en archivos o bases de datos más grandes de grupos de trabajo, departamentos y geodatabases corporativas a las que acceden muchos usuarios.

# Datos Espaciales
Un modelo de datos geográfico es una abstracción del mundo real que emplea un conjunto de objetos dato, para soportar el despliegue de mapas, consultas, edición y análisis. Los datos geográficos, presentan la información en representaciones subjetivas a través de mapas y símbolos, que representan la geografía como formas geométricas, redes, superficies, ubicaciones e imágenes, a los cuales se les asignan sus respectivos atributos que los definen y describen.

Un dato espacial es una variable asociada a una localización del espacio. Normalmente se utilizan datos vectoriales, los cuales pueden ser expresados mediante tres tipos de objetos espaciales.

![Datos Espaciales](/https://es.wikipedia.org/wiki/Archivo:Sig.jpg)

