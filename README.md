# Plantilla de economía
plantilla tipo para asignaciones de economía. pieces/header.tex es donde se modifican los datos personales

### Imagenes
Si las imagenes se encuentran en **/img/** unicamente es necesario colocar el nombre de la imagen.


### Instalación
Si tiene Python instalado puedo optar por instalar [texpj](https://pypi.org/project/texpj/) y así tener una forma sencilla de administrar
plantillas, si ya tiene instalado texpj ejecute los siguiente:

```
texpj install BenyaminGaleano/economia-plantilla NOMBRE_PLANTILLA "cuestionario básico para economía"
```

Para que funcione se necesita que tenga instalado **git**.


### Linux
Puede utilizar estos comandos y ahorrarse acciones:
- **bin/clean** limpia todos los archivos no necesarios en el proyecto.
- **bin/create nombre_carpeta** crea un nuevo reporte a partir del actual, limpia y actualiza [Utilidades](https://github.com/BenyaminGaleano/utilidades.git) si se lo permite, además abre la carpeta que se creo (se crea en la carpeta padre de donde se ejecutó el script) y abre texstudio en el proyecto si lo tiene instalado.
- **bin/open** para abrir el proyecto si en dado caso lo dejó pendiente.




