# Guía de Contribución

Este documento define los estándares para contribuir al repositorio de plantillas de reportes.

## 1. Estándar de Formato
* Todos los documentos deben redactarse estrictamente en sintaxis **Markdown**.
* Mantener neutralidad y concisión técnica en las descripciones.
* Utilizar listas estructuradas para enumeración de vulnerabilidades o metodologías.

## 2. Convenciones de Commits
Utilizar prefijos estándar para el historial de versiones:
* `feat:` Añadir una nueva plantilla.
* `fix:` Corrección de errores tipográficos o de formato en plantillas existentes.
* `docs:` Actualización de documentación interna o de este archivo `CONTRIBUTING.md`.

**Ejemplo de commit:**
```text
feat: añadir plantilla de respuesta a incidentes (IR)
```

## 3. Flujo de Trabajo (Branching)
1. Crear una rama derivada de `main` con el formato `tipo/nombre-plantilla` (ej. `feat/plantilla-cis`).
2. Realizar los cambios y ejecutar commits atómicos.
3. Solicitar un Pull Request (PR) hacia la rama `main`.
