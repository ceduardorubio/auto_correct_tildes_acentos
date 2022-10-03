# Diccionario de tildes para la extension de Visual Studio Code - Auto Correct 
Para no tener que desperdiciar tiempo en tildes y acentos.

## Pasos para utilizar
    - 1. Instalar la extension Auto Correct de Visual Studio Code
    - 2. Abrir el archivo de configuración de la extension
    - 3. Encontrar la sección de "Auto Correct" ( "auto-correct.dictionary": { ... } )
    - 4. Copiar el listado del campo "words" del archivo "dictionary.json" de este repositorio
    - 5. Pegar el listado de palabras copiado en el paso anterior en el campo words del archivo de configuración de la extension

## Pasos para agregar palabras localmente 
    - 1. Abrir el archivo settings.json de vscode
    - 2. Encontrar la sección de "Auto Correct" ( "auto-correct.dictionary": { ... } )
    - 3. Al final del listado words (de preferencia en el bloque de todos los lenguajes) agregar la palabra sin tilde[acento ~] entre comillas dobles seguida de dos puntos ( : ) seguida de la palabra escrita correctamente con tilde[acento ~] entre comillas dobles. Ejemplo: "tambien": "también"
    - 4. Seleccionar todo el listado de las palabras y ordenarlo descendente presionando F9
    - 5. Guardar el archivo settings.json

## Pasos para agregar palabras al repositorio
    - 1. Abrir el archivo settings.json de vscode
    - 2. Encontrar la sección de "Auto Correct" ( "auto-correct.dictionary": { ... } )
    - 3. Copiar todo el listado de palabras 
    - 4. Pegar el listado de palabras copiado en el paso anterior en el campo words del archivo "dictionary.json" de este repositorio
    - 5. Seleccionar todo el listado de las palabras y ordenarlo descendente presionando F9
    - 6. Guardar el archivo "dictionary.json"
    - 7. Pushear los cambios al repositorio