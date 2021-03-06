# Challenge company mysql 馃檶

Desafio: superar test haciendo uso de consultas en sql.

## Entorno

Asegurarse de tener instalado `git` . Esto se puede revisar muy facilmente a trevez del comando `git --version` . En caso de no estar instalado, se puede hacer a travez de los siguientes paso

- En linux, a travez del comando `sudo apt install git`.
- En Windows, a travez de la pagina oficial https://git-scm.com/

Procurar tener actualizado `node.js` a la versi贸n lts. Para saber si Node.js esta instalado en su sistema, abra una terminal y ejecute el siguiente comando `node --version`. El resultado debe ser la versi贸n de node instalada. Si el comando no se encuentra o no se encuentra en la versi贸n lts, se puede instalar Node.js mediante alguno de los siguientes pasos

- En windows, desde la [pagina oficial](https://nodejs.org/en/), descargando y ejecutando la versi贸n `lts`.
- En Linux, a trav茅s de `nvm`.
    - Abrir una terminal y ejecutar alguno de los siguientes comando
      
        ```bash
        curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh) | bash
        ```
        
        ```bash
        wget -qO- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh) | bash
        ```
        
    - Cerrar la terminal y abrir otra para ejecutar el siguiente comando para verificar la correcta instalaci贸n`nvm --version` . Una vez observada la versi贸n, ejecutar el siguiente comando para instalar Node.js
      
        ```bash
        nvm install --lts
        ```

## Instalaci贸n y ejecuci贸n

- 馃洜Para instalar las dependencias ejecutar el siguiente comando `npm install`

- 鈿扨ara ejecutar el modo playground o repl, ejecutar el siguiente comando `npm run dev`

- 馃敡Para traducir el c贸digo en `/src` a `JavaScript` , usar el comando `npm run build`

- 馃攽Para ejecutar el c贸digo con `Node.js`, usar el comando `npm run start`

- 馃ИPara ejecutar los test con jest, usar el comando `npm run test`

- 馃ИPara ejecutar los test de cobertura, usar el comando `npm run test:coverage`

## Variables de entorno

- `BDD_HOST`: host de la base de datos, por defecto es `localhost`
- `BDD_USER`: usuario para acceder a la base de datos, por defecto es `root`
- `BDD_PASS`: contrase帽a para acceder a la base de datos, por defecto es `newpass`

Se puede usar el archivo `.env` para configurar estas variables de entorno en testing y desarrollo. Solo se debe ejecutar el comando `cp .env.example .env`.

## Caracter铆sticas

- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/)
- [mysql2](https://www.npmjs.com/package/mysql2)
