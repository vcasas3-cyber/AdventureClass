# AdventureClass

Gamificación de las entregas de clase con un personaje aventurero, al estilo Classcraft.

## Funcionalidades hechas

### v1 · Vista de alumno individual (`expedicion.html`)
- [x] Personaje con nombre, nivel, XP, vida y monedas
- [x] Cursos y entregas propias con fecha y dificultad (20, 40 o 70 XP)
- [x] Entrega a tiempo: XP completa, monedas y vida. Entrega tarde: mitad de XP y pérdida de vida
- [x] Racha de entregas a tiempo e insignias
- [x] Tema claro y oscuro, adaptado a móvil
- [x] Progreso guardado en el navegador (`localStorage`)

### v2 · Profesor y alumnos (`expedicion-clase.html`)
- [x] Vista de profesor: crea cursos con código de unión
- [x] El profesor crea tareas con fecha límite y XP
- [x] Los alumnos se unen con el código y entregan
- [x] El profesor revisa y aprueba entregas (tarde = mitad de XP)
- [x] El profesor da XP extra a cualquier alumno
- [x] Datos compartidos entre usuarios (base de datos de la página publicada)

## Pendiente
- [ ] Tienda para gastar monedas
- [ ] Ranking del curso
- [ ] Penalizaciones de vida dadas por el profesor
- [ ] PWA instalable (manifest y service worker)
