# Mercado descentralizado en Ephemery

## Dependencias

Puede haber más dependencias en los archivos `package.json` del proyecto y de la carpeta `web_app`. Se recomienda ejecutar `npm install` en ambos directorios para instalar todas las dependencias necesarias.

## Instalación y uso
**1.** Modificar el archivo .env del directorio raiz y colocar la clave privada de la billetera

**2.** Desplegar el contrato: `npx hardhat run scripts/despliegue.js --network ephemery`


**3.** Copiar la dirección del contrato y pegarlo en la variable del archivo .env del directorio *web_app*

**4.** Ejecutar el front-end desde el directorio *web_app*:
```shell
npm run dev
```
**5.** Visualizar el mercado en https://localhost:1537/