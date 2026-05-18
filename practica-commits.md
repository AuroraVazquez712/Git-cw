# Práctica de commits — Git · ENP6 UNAM

Cada nivel te pide un cambio concreto en este archivo.  
Edita → `git add practica-commits.md` → `git commit -m "..."`

---

## Nivel 1 · Preséntate

**Qué hacer:** Llena los campos con tus datos.  
**Commit:** `feat(perfil): agrega presentación de [tu nombre]`

```
Nombre     : Aurora Betshabé Vázquez Robles 
GitHub     : AuroraVazquez712
Algo sobre mí : Quiero trabajar para Microsoft
```

---

## Nivel 2 · Lo que ya sabes hacer

**Qué hacer:** Agrega al menos tres cosas que sabes hacer (no tienen que ser de programación).  
**Commit:** `feat(habilidades): agrega lista de habilidades`

- Bailar

- Leer braille

- Cocinar

## Nivel 3 · Corrige los errores

**Qué hacer:** El párrafo de abajo tiene **cuatro errores**. Corrígelos todos en un solo commit.  
**Commit:** `fix(convenciones): corrige errores en descripción de Git`

> Git es un sistema de control de versiones creado en 2005 por Linus Torvalds
> para reemplazar a BitKeeper, que era de licencia y dejó de darse gratis al proyecto Linux.
> Cada commit guarda una fotografía de todos los archivos del repositorio en ese momento,
> identificada con un hash SHA-1 único. Para subir cambios al servidor usamos `git push`.

---

## Nivel 4 · Qué aprendí hoy

**Qué hacer:** Escribe tres cosas concretas que aprendiste en esta sesión.  
**Commit:** `docs(aprendizaje): agrega notas de la sesión`

1. Aprendí a nombrar bien los commits
2. Aprendí los nombres de los nuevos asesores 
3. Aprendí a vincular una segunda cuenta 

---

## Nivel 5 · Tabla de comandos

**Qué hacer:** Completa las celdas vacías de la tabla.  
**Commit:** `docs(comandos): completa tabla de referencia`

| Comando | ¿Qué hace? |
|---------|------------|
| `git init` |inicializa el nuevo repo |
| `git status` | Te muestra en qué estado se encuentran los archivos|
| `git add .` |Después de realizar cambios, es como añadir el archivo para despúes hacer commit |
| `git commit -m "..."` |Una vez que se puso git add se termina de subir y lo nombras según el tipo de cambio realizado |
| `git log --oneline` |Historial de los últimos cambios |
| `git push` |Subir de tu computadora a la nube después de realizar commits |

---

## Nivel 6 · Marca tu avance

**Qué hacer:** Cambia `[ ]` por `[x]` en cada punto que ya dominas.  
**Commit:** `chore(practica): actualiza checklist de avance`

- [x] Hice `git init` sin ayuda
- [ ] Entiendo para qué sirve el Staging Area
- [x] Escribí un mensaje de commit con formato Conventional Commits
- [x] Puedo ver el historial con `git log`
- [x] Completé todos los niveles de esta práctica

---

## Referencia rápida

| Tipo | Cuándo |
|------|--------|
| `feat` | Agrego algo nuevo |
| `fix` | Corrijo un error |
| `docs` | Solo toco documentación o notas |
| `style` | Formato, sin cambiar contenido |
| `refactor` | Reorganizo sin cambiar el resultado |
| `chore` | Tareas de mantenimiento |
