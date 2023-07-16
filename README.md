# ⚙️🪄instalador de Dependencias e Inicializador del Proyecto Node.js🪄⚙️

Este conjunto de scripts `.bat` te permitirá realizar dos acciones importantes al comenzar tu proyecto Node.js: realizar la inicialización básica de tu proyecto Y instalar todas las dependencias necesarias. Con solo ejecutar estos archivos, tendrás todo listo para empezar a desarrollar. 

*(Este mini proyecto nació por mi aburrimiento al tener que instalar todo en el momento de iniciar un nuevo proyecto de node ;3)*

------



## 🌌🏁Requisitos previos🏁🌌

Antes de ejecutar estos scripts, asegúrate de tener instalado en tu sistema:

1. [Node.js](https://nodejs.org/): El entorno de ejecución para JavaScript.
2. [npm](https://www.npmjs.com/): El gestor de paquetes de Node.js.

## ♾️🟣Pasos de instalación e inicialización🟣♾️

Sigue los siguientes pasos para inicializar tu proyecto Node.js y instalar las dependencias:

1. ### Descarga los archivos `.bat`

   Descarga los archivos `install_dependencies.bat` e `iniciar_node.bat` en la raíz de tu proyecto, en la misma carpeta donde se creara el archivo `package.json`.

2. ### .Ejecutar `iniciar_node.bat`

   Haz doble clic en el archivo `iniciar_node.bat`. Esto ejecutará el primer script y realizará la inicialización básica de tu proyecto, creando un archivo `package.json` con configuraciones por defecto.

3. ### Ejecutar `install_dependencies.bat`

   Haz doble clic en el archivo `install_dependencies.bat`. Esto ejecutará el segundo script y comenzará la instalación de todas las dependencias necesarias para tu proyecto.

4. ### ¡Listo para desarrollar!

   Una vez completados los pasos anteriores, tendrás todas las dependencias instaladas y tu proyecto inicializado. Ahora puedes comenzar a desarrollar tu aplicación Node.js.

## 🎉🎇Dependencias instaladas🎇🎉

El segundo script (`install_dependencies.bat`) instalará las siguientes dependencias en tu proyecto:

- `nodemon`: Herramienta que reinicia automáticamente el servidor cada vez que detecta cambios en los archivos.
- `class-validator`: Biblioteca para validar clases y objetos en TypeScript.
- `class-transformer`: Biblioteca para transformar objetos (por ejemplo, desde JSON) en instancias de clases.
- `dotenv`: Biblioteca para cargar variables de entorno desde archivos `.env`.
- `express`: Framework web para Node.js.
- `mysql2`: Cliente MySQL para Node.js.
- `reflect-metadata`: Biblioteca que permite usar decoradores con TypeScript.
- `typescript`: Compilador de TypeScript.

## 😶‍🌫️🥽Notas importantes🥽😶‍🌫️

- Asegúrate de que Node.js y npm estén instalados en tu sistema antes de ejecutar estos scripts.
- Si necesitas agregar más dependencias o personalizar la configuración de tu proyecto, puedes hacerlo manualmente editando el archivo `package.json` que fue generado durante la inicialización.

¡Disfruta desarrollando tu proyecto Node.js con todas las dependencias instaladas y la configuración inicial lista para usar!