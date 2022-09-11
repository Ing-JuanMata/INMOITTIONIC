# FRONTED PARA EL PROYECTO INMOITT

## PRIMORDIAL
Ejecutar el modelo de la base de datos que viene en el proyecto usando alguna herramienta como "Mysql WorkBench"

## Pasos a seguir para probar este codigo para produccion
`docker compose build --no-cache`
`docker compose up --build`
## Pasos para desarrollar en este proyecto y probarlo en web
- Haber hecho "build" y "up" del compose
- Tener instalado la extension [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Dar click en el icono >< que aparece en la parte inferior izquierda
- Seguido a lo anterior darle a "open in container"

# USAR LABORATORIO Y CONSTRUCCION PARA DISPOSITIVOS MOVILES
- Tener instalado Node:16
- Instalar de forma global la herramienta de ionic `npm i -g @ionic/cli`
- correr el comando `ionic serve -l` para el laboratorio o `ionic build [options]` para instalarlo en algun dispositivo, donde [las opciones son](https://ionicframework.com/docs/cli/commands/serve#options) 
