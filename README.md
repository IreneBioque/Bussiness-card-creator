# Business card creator 🗃️

Esta aplicación consiste en un creador de tarjetas profesionales, donde debes rellenar los datos que aparecen en el formulario, y a continuación darle a crear tarjeta. Esta tarjeta se puede compartir directamente por Twitter a través de la web.
El proyecto consistió en refactorizar un código heredado, generar los componentes necesarios usando React, desarrollar una API Rest y servidor básico, crear un motor de plantillas para visualizar las tarjetas creadas, siempre usando Scrrum como marco de referencia de trabajo.

This application consists of a business card creator, where you have to fill in the details that appear on the form, and then click on create card. This card can be shared directly via Twitter through the web.
The project consisted of refactoring a legacy code, generating the necessary components using React, developing a Rest API and basic server, creating a template engine to visualise the cards created, always using Scrrum as a framework.

## Comenzando 🚀 / Starting 🚀

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

These instructions will allow you to get a working copy of the project on your local machine for development and testing purposes.

### Pre-requisitos 📋 / Prerequisites 📋

¿Que necesitas para instalar el software?

```
Necesitas tener instalado Node JS
```

What do you need to install the software?

```
You need to have installed Node JS
```

### Instalación 🔧

1. Descargar este repositorio en zip o clonar el repositorio en tu dispositivo (si clonas el repositorio, ten en cuenta de que no podrás añadir tus commits)
2. Abre una terminal en la carpeta raíz de tu repositorio
3. Instala las dependencias locales ejecutando en la terminal el comando:

```
npm install
```

4. Abre la carpeta web y vuelve a ejecutar el comando anterior.

### Installation 🔧

1. Download this repository in zip or clone the repository on your device (if you clone the repository, note that you will not be able to add your commits).
2. Open a terminal in the root folder of your repository.
3. Install the local dependencies by running the command in the terminal:

```
npm install
```

4. Open the web folder and run the above command again.

### Arrancar el proyecto ⚙️

Una vez hecho el paso anterior, **hay que arrancar el proyecto cada vez que programes**.

Pero, hay que tener en cuenta 2 cosas:

1. Para arracar la parte del front, hay que ejecutar el siguiente comando en la carpeta web:

```
npm start
```

2. Para arracar la parte del back, hay que ejecutar el siguiente comando en la carpeta raíz:

```
npm run dev
```

Puedes arrancar esta parte tambíen con el comando:

```
npm start
```

pero los cambios que hagas en index.js no se actualizarán, por lo que te recomiendo utilizar el primer comando.

Si abres la parte del front, puedes observar que:

- Se abrirá una ventana en tu navegador pretederminado, que mostrará tu web.
- Los ficheros sobre lo que trabajarás estan dentro de la carpeta `src/`

Si abres la parte del back, puedes observar que:

- En la terminal de Vscode, aparecerá la ruta en la que se está ejecutando.

### Starting the project ⚙️

Once you have done the previous step, **start the project every time you program**.

But, you have to take into account 2 things:

1. To start the front end, you have to execute the following command in the web folder:

```
npm start
```

2. To start the back part, run the following command in the root folder:

```
npm run dev
```

You can also run this part with the command:

```
npm start
```

but the changes you make to index.js will not be updated, so I recommend using the first command.

If you open the front end, you can see that:

- A window will open in your pre-finished browser, which will display your website.
- The files you will be working on are inside the `src/` folder.

If you open the back part, you can see that:

- In the Vscode terminal, the path where it is running will appear.

### Publicar el proyecto en Heroku 📚

Si has cambiado algo en la parte del front, deberás hacer subirlo al repo para que se guarden los cambios.

Introducir el comando

```
npm run publish-react
```

Y a continuación:

Ve a la página de Heroku
Haz click en la opción hacer una nueva aplicación
Selecciona tu continente y el nombre de la aplicación
Cambia la ruta de la tarjeta creada en index.js para que coincida con el nombre de tu aplicación
Asocia tu Github con Heroku
Busca el nombre con el que hayas guardado tu repositorio
Selecciona la opción **Automatic deploys**
Selecciona la rama master y haz click en el botón **Deploy Branch**

### Publish the project on Heroku 📚

If you have changed anything on the front end, you will need to upload it to the repo to save the changes.

Enter the command

```
npm run publish-react
```

And then:

Go to the Heroku page
Click on the make a new application option
Select your continent and the name of the app
Change the path of the card created in index.js to match your app name
Associate your Github with Heroku
Search for the name you have saved your repository under
Select the **Automatic deploys** option
Select the master branch and click on the **Deploy Branch** button.

## Construido con 🛠️ / Built with 🛠️

- HTML
- SASS
- CSS
- React
- Node JS
- SQLite

## Autores ✒️ / Authors ✒️

- **Irene Bioque** [Github](https://github.com/IreneBioque)
- **Mesalina Bracho** [Github](https://github.com/Mesalina23)
- **Ana Montegrifo** [Github](https://github.com/anamontegrifo)
- **Claudia B Stein** [Github](https://github.com/ClaudiaBStein)

## Colaboradores 🖊️ / Partners 🖊️

- **Maitane Abad** -**Código Original** [Github](https://github.com/MaitaneAbad)
- **Moni Lamas** -**Código Original** [Github](https://github.com/moniLamas)
- **Ángela Miranda Rodriguez** -**Código Original** [Github](https://github.com/AMirandaRd)
- **Clara Vilela** -**Código Original** [Github](https://github.com/ClaraVilelaJato)

## Licencia 📄 / Licence 📄

Este proyecto está bajo la Licencia MIT License mira el archivo [LICENSE](LICENSE) para más detalles

This project is licensed under the MIT License MIT License see the [LICENSE](LICENSE) file for more details.

## Gracias 🎁 / Thanks 🎁

- Gracias a las compañeras y profesores de Adalab 🍺
- Thanks to the colleagues and teachers of Adalab 🍺
