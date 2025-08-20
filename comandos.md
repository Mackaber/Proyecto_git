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
