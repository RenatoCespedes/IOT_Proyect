# Practica de Internet de las Cosas
En este proyecto se instalará y configurará lo propuesto en el Capítulo 9 *Building the Critical Components* del libro **Build Your Own IoT Platform**.
## Requerimientos
- Docker

## Instalación

Los servicios a utilizarse se configurarón en un archivo [docker](docker-compose.yml), donde contiene:

| SERVICIO| VERSIÓN|
| ----- | ---- |
| node-red | latest|
| mosquitto| 1.6|
| mysql| latest|
| phpmyadmin| latest|

Luego se ejecuta el siguiente comando para la instalación y el levantamiento de los servicios:
```bash
docker-compose up
```
** Nota: En caso de presentar error con el servidor del nodo, cambiar el nombre del servidor con respecto a la salida del comando *docker ps*, por ejemplo en el caso del nodo de base de datos el servidor seria: *IOT_Proyect_mysql1* **
## Importación de Flujos
Para la importación solo se hace click en el icono de opciones(esquina superior derecha), luego en **import**. Seguido se agrega el archivo json a importar y se hace selección de nuevo diagrama. Este proceso se repite para los demas archivos json.

## Integrantes

- Céspedes Fuentes, Renato
- Vicente Castro, Renzo

