# JOSM imagery Argentina

**Catálogo de imágenes de Argentina para el editor de OpenStreetMap JOSM**

Para agregar el este catálogo ingresar a Preferencias, luego habilitar el "Modo experto" y seleccionar la última pestaña "Establecer valores de preferencia manualmente" (el ícono es una hoja con una llave). 

Buscar "imagery" y modificar el valor de "imagery.layers.sites" agregando el siguiente valor o reemplazando el existente, como se ve en la siguiente tabla:

| Clave | Valor |
|--|--|
| imagery.layers.sites | `https://osm-ar.github.io/josm-imagery/maps.xml%<?ids=>` |

**Por qué un catálogo personalizado**

 1. El catálogo por defecto es muy completo, pero tiene muchas imágenes que si sólo se edita en Argentina no son necesarias
 2. La edición del catálogo principal de JOSM a veces está bloqueada por lo que agregar nuevos fondos para que puedan ser utilizados por la comunidad puede ser difícil o imposible.
