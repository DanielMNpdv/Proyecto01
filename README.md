###### Para subirlo a GitHub:
- git init 
- git add .
git commit -m "subida hola mundo"
git remote add origin https://github.com/DanielMNpdv/
git push -u origin main

###### Otros Comandos git
git clone (para descargar el repositorio desde la nube)
git pull (fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local)
git checkout ()
git remote -v
git remote add origin <host-or-remoteURL>
git branch
git merge <branch-name>

//Comandos a introducir para empezar a trabajar (-g es global y se hace 1 sola vez):

npm init --yes
npm install -g typescript
npm install tsc-init -g
npm install mongoose
npm install @types/mongoose
npm i @types/node@14.14.6
npx tsc -w

//Se genera el tsconfig.json y en el hacemos las modificaciones de siempre: '"target": "es6",', '"outDir": "./build",' 
y en la linea 68 ponemos lo siguiente: 
"exclude": [ "node_modules" ]

//En el .gitignore ponemos: 
build
node_modules

//Creamos src y dentro index.ts y la carpeta model y view, 
en model iran las clases y en view irán los programas .ts que iremos creando, 
crearemos tambien la carpeta doc y dentro de ella crearemos un pdf explicando lo que has aprendido,
en el readme explicaras tu proyecto

//Primero debes crear los scripts .ts y luego los tienes que compilar con (opcion --watch para compilar en tiempo real):
tsc ./index.ts --out ./build/index.js --watch

//Para ejecutar lo que hemos compilado usamos: 
node build
npm run build
-- o -- 
node build/index

//Para ejecutar e instalar un trabajo de alguien
npm install
npm run build
npm start
