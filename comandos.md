# Comandos de Git

- Inicializar repositorio
```bash
git init
```

- Nos dice el estatus en el que se encuentra nuestro repo
```bash
git status
```

- Nos dice cuales son los últimos cambios que se han hecho
```bash
git log
```

## Estados de Git

![alt text](image.png)

- Añade archivos a la etapa de staged
```bash
git add comandos.md
```

- Quitar archivos del repositorio
```bash
git rm comandos.md
```

- Hace una versión de todos los archivos en staged
```bash
git commit -m "Mensaje descriptivo"
```

## Repositorios en línea

- Añadir un repositorio remoto
```bash
git remote add origin https://direccion-remota.com/git
```

- Hacer una copia de un repositorio existente
```bash
git clone https://direccion-remota.com/git
```

- Subir nuestros cambios al repositorio remoto
```bash
git push
```

- Descargar los cambios del reposiotio remoto
```bash
git pull
```

## Control de ramas (branches)

- Crear una nueva rama
```bash
git branch "Nombre de la rama"
```

- Cambiar a una rama
```bash
git checkout "Nombre de la rama"
```

(Tip) Para crear una rama y cambiar a ella
```bash
git checkout -b "Nombre de la nueva rama"
```

- Para mezclar ramas (desde la rama principal)
```bash
git merge "Rama destino"
```

- Para mezclar ramas (desde una rama hija)
```bash
git rebase "Rama de origen"
```