# spotify-clone
PID Electronics Test Practico
## Creacion de repositorio

Primero se creo una carpeta donde sere el trabajo

```sh
mkdir spotify-clone
cd spotify-clone
```

se agrega git al proyecto

```sh
git init
```

luego se agrega el remoto del repositorio

```sh
git remote add origin https://github.com/montesp/spotify-clone.git
```

se traen los cambios del proyecto

```sh
git pull origin main
```

## Subir archivos
Cuando se acaba el proyecto se agregan al stage, para agregar los archivos

```sh
git add .
git commit -m ["Que es lo que hace el commit"]
```

Con los cambios ya guardados, aora los subimos a nuestro repositorio:

```sh
git push origin main
```
