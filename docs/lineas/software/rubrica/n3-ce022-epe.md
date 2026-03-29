# RÚBRICA NIVEL 3 — CE022 (Ingeniería de la Información) — EPE

## CONTEXTO DE EVALUACIÓN

Se evalúa sobre:
- Base de datos del sistema en operación, integrada al software
- Incluye: Modelo de datos (CE0221), SQL (CE0222), Programación BD (CE0223), Seguridad y administración (CE0224)

## PRINCIPIO

- NO evalúa interfaz ni lógica de negocio.
- Evalúa si los datos del sistema son correctos, seguros, eficientes y sostenibles.

## CRITERIOS DE EVALUACIÓN

| Criterio                        | Excelente (18–20)                                                                 | Bueno (15–17)                                   | Regular (13–14)                        | Deficiente (<13)                |
|---------------------------------|-----------------------------------------------------------------------------------|-------------------------------------------------|-----------------------------------------|-------------------------------|
| Modelado de datos               | Modelo conceptual, lógico y físico consistente, normalizado y alineado a requerimientos | Modelo adecuado con leves inconsistencias       | Modelo incompleto o con problemas de diseño | Modelo incorrecto o inexistente |
| Integridad y consistencia de datos | Integridad referencial, restricciones y relaciones correctamente implementadas     | Integridad funcional con errores menores        | Problemas de consistencia                | Datos inconsistentes            |
| Implementación y consultas SQL  | Consultas correctas, eficientes y alineadas al modelo; operaciones CRUD completas  | Consultas funcionales con oportunidades de mejora | Consultas incorrectas o ineficientes     | No hay consultas funcionales     |
| Programación de base de datos   | Uso adecuado de procedimientos, funciones, triggers y lógica en BD                 | Programación funcional con limitaciones         | Uso limitado o incorrecto                | No hay programación en BD        |
| Seguridad y administración      | Control de accesos, roles, privilegios, respaldo y recuperación correctamente definidos | Seguridad funcional con limitaciones            | Seguridad parcial                        | Sin control de seguridad         |
| Rendimiento y optimización      | Uso de índices, optimización de consultas y buen desempeño del sistema             | Rendimiento aceptable                          | Problemas de rendimiento                 | Sistema lento o ineficiente      |

## ESTRUCTURA DE LA RÚBRICA

- Modelo
- Integridad
- SQL
- Programación BD
- Seguridad
- Rendimiento

## VALIDACIÓN FINAL

- ✔ Alineada a BD1 + BD2
- ✔ No mezcla desarrollo (CE023)
- ✔ No mezcla calidad (CE024)
- ✔ Evalúa datos como activo del sistema
- ✔ Totalmente trazable a CE022*

### DIFERENCIA CLAVE

| CE022         | CE023         |
|---------------|---------------|
| Datos         | Código        |
| Persistencia  | Lógica        |
| Integridad    | Funcionalidad |

**Frase clave:**

> “Un sistema es tan confiable como la calidad de los datos que gestiona.”
