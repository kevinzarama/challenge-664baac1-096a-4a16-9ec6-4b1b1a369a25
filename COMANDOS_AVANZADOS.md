# Comandos Avanzados de Git

## 1. git stash
Propósito: Guardar cambios sin hacer commit para cambiar de rama.
Ejemplo:
git stash save "cambios temporales"
git stash pop

## 2. git rebase
Propósito: Reorganizar commits de una rama sobre otra rama.
Ejemplo:
git rebase main
git rebase -i HEAD~3

## 3. git rm
Propósito: Eliminar archivos del repositorio.
Ejemplo:
git rm archivo.txt
git commit -m "Eliminado archivo.txt"

## 4. git reset
Propósito: Deshacer cambios y commits.
Ejemplo:
git reset --soft HEAD~1
git reset --hard HEAD~1
