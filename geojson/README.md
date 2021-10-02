# GeoJSON

GeoJSON​ es un formato estándar abierto diseñado para representar elementos geográficos sencillos, junto con sus atributos no espaciales, basado en JavaScript Object Notation. El formato es ampliamente utilizado en aplicaciones de cartografía en entornos web al permitir el intercambio de datos de manera rápida, ligera y sencilla.

La gramática del formato está basada en el estándar WKT del Open Geospatial Consortium, con unas geometrías que pueden ser de tipo punto (direcciones, ubicaciones, puntos de interés, etc.), líneas (calles, carreteras, fronteras, etc.), polígonos (países, provincias, parcelas catastrales, etc.) y colecciones de estos tipos. GeoJSON usa un sistema de referencia de coordenadas geográficas, WGS84 y unidades en grados decimales.

El formato GeoJSON difiere de otros estándares SIG en que no está desarrollado y mantenido por una organización oficial, sino que es mantenido por una comunidad de desarrolladores en Internet.

Una evolución de este formato es TopoJSON, una extensión de GeoJSON que codifica topología geoespacial y que proporciona ficheros de menor tamaño que GeoJson.