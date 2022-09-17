# Comandos usados para subir el repositorio a github

## Inicializar git
```bash
git init
```

## Establecer la conexion remota
```bash
git remote add origin "https://github.com/12aptor/flex-box.git"
git branch -M main
git add --all
git commit -m "mensaje"
git push origin main
```

## Creamos una nueva rama (develop)
```bash
git branch develop
git switch develop
git add --all
git commit -m "mensaje"
git push origin develop
```

## Guardamos los cambios efectuados la nueva rama
```bash
git add --all
git commit -m "mensaje"
git push origin develop
```

# Para hacer merge y eliminar(local y remotamente) la rama develop
```bash
git switch main
git merge develop
git branch -d develop
git push origin --delete develop
git push origin main
```