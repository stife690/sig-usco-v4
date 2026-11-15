# SIG-USCO V4

Sistema de información geográfica de la Universidad Surcolombiana: mapa público del campus, ruteo peatonal entre bloques, asistente conversacional de orientación y módulo de administración para nuevas sedes y edificios.

Proyecto de grado · Ingeniería de Software · Universidad Surcolombiana
Autores: David Felipe Roa Rocha y Nicolás Mosquera Perdomo · Director: Prof. Fernando Rojas

## Estructura

| Carpeta | Contenido |
|---|---|
| `frontend/` | Aplicación web en Angular |
| `backend/` | API REST en Java (Spring Boot) |
| `docs/` | Documentación técnica |
| `tools/` | Herramienta en Python para digitalizar senderos |

## Cómo correrlo

Aún no hay código ejecutable. Esta sección se completará cuando existan los proyectos de `frontend/` y `backend/`.

## Cómo trabajamos

1. **Nadie sube directo a `main`.** Todo cambio entra por pull request.
2. **Ramas:** `feature/<nombre>` (funcionalidad), `fix/<nombre>` (corrección), `docs/<nombre>` (documentación). Ejemplo: `feature/mapa-publico`.
3. **Revisión cruzada:** cada pull request necesita la aprobación del otro integrante antes de integrarse.
4. **Commits:** [Conventional Commits](https://www.conventionalcommits.org) en español, por ejemplo `feat: agrega búsqueda de salones`.

```bash
git switch main
git pull
git switch -c feature/mi-cambio
# ... trabajar y hacer commits ...
git push -u origin feature/mi-cambio
```

Luego se abre el pull request en GitHub y se asigna al otro integrante como revisor.

## Confidencialidad

Este repositorio es **público**. Por el acta de entrega del 24 de septiembre de 2026, **no se suben** el código de V3, los documentos de fases anteriores, los planos AutoCAD de Planeación ni datos de la base de datos. El código de V3 está en un repositorio privado aparte, solo como referencia.
