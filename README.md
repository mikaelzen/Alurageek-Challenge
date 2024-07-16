# Alurageek-Challenge

## Acceso al proyecto

Para poder hacer uso del proyecto es necesario simular un servidor local: se puede hacer con [json-Server](https://www.npmjs.com/package/json-server), también es necesario [Node.js](https://nodejs.org/en) así que descárgalos.

Crea una carpeta donde vas a crear un archivo .json 

`db.json`

Luego ejecuta los siguientes comandos en la terminal, en la misma ruta del archivo anterior.

`npm init -y`

`npm install json-server`

`npx json-server --watch db.json --port 3001`

Tras estos pasos puedes ver en funcionamiento la aplicación sin clonar el proyecto.

También se puede clonar.

`git clone https://github.com/EdwardbotA/challenge-alurageek.git`

`npm install`

`npm run serve`