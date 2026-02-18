# Día 14 — Gestor de tareas con JSON 🗂️

Este repositorio forma parte de mi reto personal **100 días aprendiendo a programar**.

En el Día 14 he mejorado mi gestor de tareas utilizando formato JSON en lugar de texto plano para guardar la información de forma estructurada.

---

## 📚 Qué he aprendido

- Qué es JSON
- Cómo usar `import json`
- Leer datos con `json.load()`
- Guardar datos con `json.dump()`
- Trabajar con listas de diccionarios
- Guardar estado booleano (`True` / `False`)
- Persistencia estructurada

---

## 🚀 Proyecto: Gestor de tareas estructurado

Ahora el programa:

- Guarda las tareas en un archivo `tareas.json`
- Mantiene el estado de cada tarea (completada o no)
- Permite añadir tareas
- Permite completar tareas
- Muestra tareas con indicador visual (✅ / ❌)

Las tareas se almacenan así:

```json
[
    {
        "titulo": "Estudiar Python",
        "completada": false
    }
]
