# Repositorio de Tablas de FoundryVTT

Las tablas contribuidas por la comunidad de Foundry se añaden aquí y se juntan para crear el módulo de Tablas de la Comunidad de Foundry para facilitar su uso.

## Atención

Esta es una traducción directa del código del repositorio de tablas de Foundry en inglés, para darle una mayor accesibilidad al usuario hispanohablante.
Si por algún casual prefieres el módulo de tablas en inglés o simplemente quieres comprobar quienes son los autores originales, dirígerte al repositorio original:
[https://github.com/dasuberchin/tables.git](https://github.com/dasuberchin/tables.git)

## Instalación

### Uso como Módulo

Ahora puedes instalar este módulo automáticamente especificando la siguiente URL pública del módulo:

`https://raw.githubusercontent.com/foundry-vtt-community/tables/main/module.json`

Como DM, dirégete a **Administrar Módulos** en el menú de opciones de tu pestaña de **Configuración del Mundo** y habilita el módulo **Tablas de la Comunidad de FoundryVTT**.

Este módulo traduce todas las tablas de la comunidad commo un Paquete de Compendio llamado **Tablas de la Comunidad de FoundryVTT**.

Puedes abrir estos paquetes, haciendo clic derecho y clic en importar las tablas que tu quieras.

### Uso sin el Modulo:
1. Descarga el fichero `.json` en tu máquina.
2. Crea una nueva tabla en FoundryVTT.
3. Clic derecho en la tabla en la pestaña de **Tablas** y selecciona **Importar**.
4. Importa tu ficherò `.json` y a disfrutar.

## Preguntas Frecuentes

### ¿Por qué no hay tablas de DnDBeyond?
La mayoría de esas tablas son propiedad de Wizards of the Coast, sin embargo existe un maravilloso guion que puedes utilizar para crear tu propia tabla en un fichero `.json` para importarlo en Foundry. Échale un vistazo: [useful_scripts/DnDBeyond_extractor.js](useful_scripts/DnDBeyond_extractor.js)

### Macros
Puede que quieras uilizar macros con estas tablas. Cómprueba [el repo de macros de la comunidad de foundry (inédito en español)](https://github.com/foundry-vtt-community/macros)
You may want to utilize macros with these rollable tables. Checkout [the foundry community macro repo](https://github.com/foundry-vtt-community/macros)

## Desarrollo/Contribución
Para clonar este repositorio, así como con cada tabla del mismo, utiliza el siguiente comando:

```
git clone --recurse-submodules https://github.com/gabriel-canals/tablas-foundryvtt.git
```

Puedes realizar pull request para añadir o modificar tablas aquí: [https://github.com/gabriel-canals/tablas-foundryvtt/pulls](https://github.com/gabriel-canals/tablas-foundryvtt/pulls)

1. Dirígete al directorio donde deseas añadir tu fichero.
2. Clic en "Añadir archivo" en la parte superior.
3. Ponle un nombre a tu fichero que finalize con `.json` y pega tu contenido y guarda (añade detalles en la descripción acerca de tu fichero `.json`).
4. Guarda el fichero y abre una pull request (GitHub debería guiarte a través de ese proceso).

Si tienes *múltiples ficheros que deberían agruparse juntos* y puede que utilicen una macro, considera crear un nuevo directorio que contenga todos los ficheros y añade un fichero README.md al directorio.
