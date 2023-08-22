# CREACION DE UN REPO Y ENLAZARLO CON GITHUB

<svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
  <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
  <path d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5" />
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
      [](image.png)
      De preferencia que el nombre sea igual que la carpeta que vaya a subir al repositorio.

**2** Luego de Crear el repositorio en GitHub, copias el codigo Url que te da de resultado!:
      [](image-1.png)

**3** En tu carpeta local abre una terminal, o abre el Git Bash!:
      (Con MAYUS + Click Derecho) puedes abrir el panel completo si en caso estas en Windows 11
      [](image-2.png)

      { Por parte de la prueba voy a crear un archivo .txt }

**4** Ahora dentro del Git Bash ejecuta los siguientes comandos:
    **4.1**'git init'
        *[Esto iniciara un nuevo repositoro en el lugar ejecutado]*
        [](image-3.png)
        *[Esto nos dejara con un archivo .git en la carpeta]*
    **4.2** 'git add .'
        *[Con este comando, se agregaran TODOS los ARCHIVOS a la "cola" para enviarse al repositorio]*
        [](image-4.png)
        *[Si en caso desea ver la cola a enviarse, ejecute el siguiente comando]*
        *4.2.1* [git status]
              [](image-5.png)
              *[Como puede visualizar, esta en cola un nuevo archivo (que seria nuestro archivo .txt)]*
    **4.3** 'git commit -m "mensaje a enviar"
        *[Los cambios ya estan agregados, solo faltaria realizar el push hacia el repositorio Remoto]*
        [](image-6.png)
        *[Si quiere visualizar el estado de los archivos, nuevamente puede ejecutar el anterior comando]*
        *4.3.1* [git status]
              [](image-7.png)
              *[Se puede ver que no hay ningun Commit en cola]*
    **4.4** 'git remote add origin https://aqui-va-su-link.git'
        *[Con esto, sus archivos se van a conectar con su repositorio remoto dentro GitHub]*
        [](image-8.png)
    **4.5** 'git push origin main'
        *[Por ultimo, ejecutaremos este comando, lo que hará que se suban completamente todos sus archivos selecionados a su*
        *repositorio remoto]*
        [](image-9.png)
        *4.5.1* [git status]
              *[Ahora si desea, pueden comprobar el estados de sus archivos con el anterior comando]*
              [](image-10.png)

**5** Si volvemos a nuestro GitHub, y recargamos la pagina podremos visualizar nuestros archivos que hemos subido.
      [](image-11.png)