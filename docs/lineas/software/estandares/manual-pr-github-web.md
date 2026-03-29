# Manual de PR con GitHub Web

## Paso 1: Crear el repo en GitHub, de preferencia dentro de una organización
El repo debe ser creado con sólo el README.md, por ejemplo: mi-repo

```sh
git clone https://github.com/miorg/mi-repo.git
cd mi-repo
```

## Paso 2: Una vez en su proyecto, actualice su local y crea tu rama de trabajo
```sh
git pull origin main
git checkout -b tarea/deploy-doc-v1 
# Hacer el trabajo
git add .
git commit -m "feat: doc linea de soft"
git push -u origin tarea/deploy-doc-v1
```

## Paso 3: Hacer PR en GitHub Web y luego elimina tu rama de trabajo
```sh
git checkout main
git pull origin main
git branch -d tarea/deploy-doc-v1
git push origin --delete tarea/deploy-doc-v1
```

## Paso 4: Crea tu nueva rama para continuar con la segunda tarea, y repita desde el paso 2. Por ejemplo:
```sh
git pull origin main
git checkout -b tarea/deploy-doc-v2
# Hacer el trabajo 2
git add .
git commit -m "feat: doc linea de soft v2"
git push -u origin tarea/deploy-doc-v2
git checkout main
git pull origin main
git branch -d tarea/deploy-doc-v2
git push origin --delete tarea/deploy-doc-v2
```
