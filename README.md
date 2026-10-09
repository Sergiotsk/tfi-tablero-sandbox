# Tablero TFI — sandbox

Repo de prueba para mostrarle al equipo cómo proponemos organizar el trabajo del TFI con
GitHub Projects y Scrumban.

**Todo el contenido es de ejemplo.** Las issues, los PR y los archivos solo sirven para mostrar el
flujo y no son trabajo real.

## Qué mirar

1. **El Project** (pestaña *Projects* del repo), con sus tres vistas: *Tablero*, *Por incremento*
   y *Mi trabajo*.
2. **Las issues**: historias de usuario con criterios Dado / Cuando / Entonces, habilitadores,
   consultas, documentación, un bug y la retro.
3. **Los PR**: uno mergeado, que cerró su tarjeta, y otro abierto, en revisión.
4. **[CONTRIBUTING.md](CONTRIBUTING.md)** y las plantillas de `.github/`: así se abre una issue o
   un PR.

## Cómo se mueve una tarjeta

```
Backlog → Listo → En curso → En revisión → Hecho
```

- **Listo**: tiene criterios de aceptación, nada la bloquea y tiene `Área` y `Puntos`.
- **En curso**: una tarjeta por persona como máximo.
- **En revisión**: hay un PR abierto. Revisa cualquier compañero que no sea el autor.
- **Hecho**: el PR está mergeado en `develop`, con el CI en verde y los criterios cumplidos.
