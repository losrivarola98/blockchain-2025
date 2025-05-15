# Mercado descentralizado en Ephemery

## Dependencias

Es posible que se necesite reinstalar las dependencias, en cuyo caso se debe:

**1.** Borrar las carpetas *node_modules* del directorio raiz y de la carpeta *web_app*

**2.** Borrar los archivos *package-lock.json* del directorio raiz y de la carpeta *web_app*

**3.** Reinstalar las dependencias en el directorio raiz y en la carpeta *web_app* `npm install`

## Instalación y uso
**1.** Modificar el archivo .env del directorio raiz y colocar la clave privada de la billetera

**2.** Desplegar el contrato: `npx hardhat run scripts/despliegue.js --network ephemery`


**3.** Copiar la dirección del contrato y pegarlo en la variable del archivo .env del directorio *web_app*

**4.** Ejecutar el front-end desde el directorio *web_app*:
```shell
npm run dev
```
**5.** Visualizar el mercado en la dirección web que te muestre en consola
