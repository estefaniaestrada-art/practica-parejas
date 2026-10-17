# Proyecto: Práctica en Parejas - Control de Versiones y DevOps

## Estrategia de Ramas: Git Flow
En este proyecto se implementa la metodología **Git Flow** como estrategia de ramificación.

### Justificación de la elección:
1. **Estabilidad del código:** La rama `main` almacena código listo para producción, mientras que `develop` actúa como integrador central.
2. **Aislamiento de tareas:** Las nuevas características se desarrollan en ramas `feature/*` independientes, evitando contaminar el código base antes de ser validadas.
3. **Gestión formal de lanzamientos:** Permite preparar *releases* estables (`release/*`) y aplicar etiquetado explícito de versiones (`v1.0.0`).
