# INSTALACION DE DEPENDENCIAS

## INSTALACION DE NVM

NVM (Node Version Manager) es una herramienta que permite instalar y gestionar múltiples versiones de Node.js en el mismo sistema. Esto es especialmente útil para mantener proyectos con diferentes requisitos de versiones de Node.js sin conflictos.

### Instalación de NVM

Para instalar NVM se debe ir a la siguiente página :

    https://github.com/coreybutler/nvm-windows/releases

Luego ejecutar y seguir los pasos correspondientes de instalación:

    nvm-setup.exe

Para verificar la instalación de NVM, usa:

    nvm --version

### Importancia de NVM

NVM facilita la gestión de múltiples versiones de Node.js en el mismo sistema, lo cual es esencial para trabajar en diferentes proyectos que pueden requerir distintas versiones de Node.js. Además, NVM permite actualizar fácilmente a las últimas versiones de Node.js y cambiar entre versiones según sea necesario.

## ¿POR QUÉ UTILIZAR NPM Y NO NODEJS LTS?

NPM (Node Package Manager) es una herramienta fundamental para gestionar las dependencias de un proyecto Node.js. Aunque Node.js LTS es importante para la estabilidad y seguridad a largo plazo, NPM permite instalar y gestionar librerías y herramientas de desarrollo de manera más flexible y eficiente. Usar NPM junto con NVM permite una mejor gestión de las versiones de Node.js y las dependencias del proyecto.

## INICIALIZAR UN PROYECTO CON NODEJS

Para iniciar un nuevo proyecto con Node.js, sigue estos pasos:

1. Crea un directorio para tu proyecto y navega a él:

        mkdir sesion2
        cd sesion2

2. Inicializa un nuevo proyecto Node.js:

        npm init 

    Esto creará un archivo `package.json` con la configuración predeterminada.

## INSTALACION DE DEPENDENCIAS

### Instalación de dependencias de desarrollo

Estas dependencias solo existen en el ámbito de desarrollo y no se incluyen en el entorno de producción.

    npm install -D axios

### Instalación de dependencias de producción

Estas dependencias se incluyen en el entorno de producción.

    npm install react-dom

### Instalación de dependencias globales

Las instalaciones globales se realizan en todo el sistema operativo y son útiles para herramientas que se usan en múltiples proyectos.

    npm install -g nodemon

