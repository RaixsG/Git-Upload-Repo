# CREACION DE UN REPO Y ENLAZARLO CON GITHUB

<svg height="32" width="32">
    <path d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.27.01-1.13.01-2.2 0-.75-.25-1.23-.54-1.48 1.78-.2 3.65-.88 3.65-3.95 0-.88-.31-1.59-.82-2.15.08-.2.36-1.02-.08-2.12 0 0-.67-.22-2.2.82-.64-.18-1.32-.27-2-.27-.68 0-1.36.09-2 .27-1.53-1.03-2.2-.82-2.2-.82-.44 1.1-.16 1.92-.08 2.12-.51.56-.82 1.28-.82 2.15 0 3.06 1.86 3.75 3.64 3.95-.23.2-.44.55-.51 1.07-.46.21-1.61.55-2.33-.66-.15-.24-.6-.83-1.23-.82-.67.01-.27.38.01.53.34.19.73.9.82 1.13.16.45.68 1.31 2.69.94 0 .67.01 1.3.01 1.49 0 .21-.15.45-.55.38A7.995 7.995 0 0 1 0 8c0-4.42 3.58-8 8-8Z"></path>
</svg>

## Descripción

Este **README** nos ayudara a la creacion de un repositorio en **GitHub** y conectarlo con una carpeta que se desee subir al mismo.

*Para mayor información y más detallado, puede visualizar el siguiente enlace*
[https://www.hostinger.co/tutoriales/comandos-de-git]

## Contenido
    1. Creación Repositorio en GitHub.
    2. Obtener Url del Repositorio Remoto.
    3. Abrir Git Bash en la carpete a subir.
    4. Ejecución de comando.
    5. Recarga de pagina en GitHub.

## Instrucciones

**1** Creación de un Repositorio en GitHub!:
      [Alt text](image.png)
      De preferencia que el nombre sea igual que la carpeta que vaya a subir al repositorio.

**2** Luego de Crear el repositorio en GitHub, copias el codigo Url que te da de resultado!:
      [Alt text](image-1.png)

**3** En tu carpeta local abre una terminal, o abre el Git Bash!:
      (Con MAYUS + Click Derecho) puedes abrir el panel completo si en caso estas en Windows 11
      [Alt text](image-2.png)

      { Por parte de la prueba voy a crear un archivo .txt }

**4** Ahora dentro del Git Bash ejecuta los siguientes comandos:
    *4.1* 'git init'
        *[Esto iniciara un nuevo repositoro en el lugar ejecutado]*
        [Alt text](image-3.png)
        *[Esto nos dejara con un archivo .git en la carpeta]*
    *4.2* 'git add .'
        *[Con este comando, se agregaran TODOS los ARCHIVOS a la "cola" para enviarse al repositorio]*
        [Alt text](image-4.png)
        *[Si en caso desea ver la cola a enviarse, ejecute el siguiente comando]*
        *4.2.1* [git status]
              [Alt text](image-5.png)
              *[Como puede visualizar, esta en cola un nuevo archivo (que seria nuestro archivo .txt)]*
    *4.3* 'git commit -m "mensaje a enviar"
        *[Los cambios ya estan agregados, solo faltaria realizar el push hacia el repositorio Remoto]*
        [Alt text](image-6.png)
        *[Si quiere visualizar el estado de los archivos, nuevamente puede ejecutar el anterior comando]*
        *4.3.1* [git status]
              [Alt text](image-7.png)
              *[Se puede ver que no hay ningun Commit en cola]*
    *4.4* 'git remote add origin https://aqui-va-su-link.git'
        *[Con esto, sus archivos se van a conectar con su repositorio remoto dentro GitHub]*
        [Alt text](image-8.png)
    *4.5* 'git push origin main'
        *[Por ultimo, ejecutaremos este comando, lo que hará que se suban completamente todos sus archivos selecionados a su*
        *repositorio remoto]*
        [Alt text](image-9.png)
        *4.5.1* [git status]
              *[Ahora si desea, pueden comprobar el estados de sus archivos con el anterior comando]*
              [Alt text](image-10.png)

**5** Si volvemos a nuestro GitHub, y recargamos la pagina podremos visualizar nuestros archivos que hemos subido.
      [Alt text](image-11.png)