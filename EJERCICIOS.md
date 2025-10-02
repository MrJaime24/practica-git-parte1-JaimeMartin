# EJERCICIOS PARTE 2

## Ejercicio 1. Ciclo básico
- **Comando:** `git add notas.md && git commit -m "feat: añade notas iniciales" && git push origin main`
- **Explicación:** Se añadió el archivo `notas.md` con asignaturas y se subió al remoto.

## Ejercicio 2. Ramas
- **Comando:** `git switch -c feature-tareas`
- **Explicación:** Se creó una rama para trabajar en tareas pendientes sin afectar la rama principal.

## Ejercicio 3. Borrado y restauración
- **Comando:** `git rm temporal.txt`
- **Explicación:** Se eliminó el archivo `temporal.txt` del repositorio y luego se restauró desde el último commit con `git restore`.

## Ejercicio 4. Logs y diffs
- **Comando:** `git log --oneline --graph --all`
- **Explicación:** Muestra el historial de commits en forma resumida y gráfica.
- **Comando:** `git diff HEAD~1 HEAD`
- **Explicación:** Muestra los cambios realizados entre el último commit y el anterior.

## Ejercicio 5. Conflictos intencionados
- **Comando:** `git merge feature-conflicto`
- **Explicación:** Se generó un conflicto al editar la misma línea en dos ramas. Se resolvió manualmente y se documentó en `conflicto.md`.

## Ejercicio 6. Tags
- **Comando:** `git tag v1.0 && git push origin --tags`
- **Explicación:** Se creó un tag ligero. Luego se creó un tag anotado `v1.1` con mensaje para marcar la primera versión estable.
