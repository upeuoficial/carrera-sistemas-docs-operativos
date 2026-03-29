# 📄 Estándar Oficial: Política de Ramas y Pull Requests (PR)

## Obligatorio para todos los proyectos de software

Esta política define el flujo de trabajo estándar para ramas y Pull Requests (PR) en los repositorios de la línea de software. Su cumplimiento es obligatorio para todos los equipos y colaboradores.

---

## 1. Rama principal
- La rama estable del repositorio es `main`.
- No se trabaja directamente sobre `main`.

## 2. Regla común (aplica a todos)
- Todo cambio se desarrolla en rama de trabajo.
- Toda integración se realiza por PR hacia `main`.
- `main` queda reservada para integración estable.

## 3. Formato de ramas de trabajo

### Ramas de trabajo alumnos
**Formato:**

    tarea/<autor>-<tema>

**Ejemplo:**

    git checkout -b tarea/ana-perez-crud-productos

### Ramas de sesión docentes
**Formato:**

    sesion/<numero>-<tema>

**Ejemplo:**

    git checkout -b sesion/01-arquitectura-base-ms

## 4. Tags de cierre por sesión
**Formato recomendado:**

    vs<numero>-<tema>-final

**Ejemplo:**

    vs01-base-catalogo-final

## 5. Pull Requests (PR)
Todo PR debe indicar:
- Objetivo del cambio
- Cambios principales
- Artefacto de prueba
- Impacto en base de datos (si aplica)
- Estrategia de merge esperada: **Squash and merge**

### Regla de oro con Squash and merge
Cuando un PR se integra con Squash and merge, la rama fuente queda "huérfana" desde el punto de vista del historial.

**Regla obligatoria:**
- Borrar la rama de trabajo ya mergeada.
- Actualizar la rama destino (normalmente `main` o `sesion/...`).
- Crear una rama nueva para la siguiente tarea.

## 6. Flujo mínimo de trabajo
1. Sincronizar `main` cuando la tarea es nueva.
2. Crear rama propia de trabajo.
3. Implementar cambio.
4. Ejecutar pruebas.
5. Hacer commit claro.
6. Subir rama.
7. Abrir PR hacia `main`.

---

## Referencia
- [Manual de PR con GitHub Web](manual-pr-github-web.md) _(Guía paso a paso)_

---

> Este estándar es de cumplimiento obligatorio y debe ser referenciado en la documentación de cada proyecto de software.
