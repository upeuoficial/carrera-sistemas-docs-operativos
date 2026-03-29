# 5. Evaluación EPE

## Matriz — Evaluación EPE (macro final)

| CE | Evidencia de perfil (integrada) | Entregable EPE | Rúbrica (criterios de evaluación) |
|---|---|---|---|
| **CE021** Ingeniería de Requerimientos | Requerimientos, prototipos, arquitectura y modelado del sistema coherentes, trazables y validados con stakeholders | **Documento del sistema:**<br>- SRS completo<br>- Prototipos navegables<br>- Arquitectura (vistas, decisiones)<br>- UML | - Completitud y claridad<br>- Coherencia entre artefactos<br>- Trazabilidad<br>- Alineación con el contexto<br>- Validación con stakeholders |
| **CE022** Ingeniería de la Información | Modelo de datos implementado, consistente y operando con seguridad y rendimiento, alineado a los requerimientos del sistema | **Base de datos del sistema:**<br>- Modelo de datos<br>- SQL funcional<br>- Programación BD<br>- Seguridad y administración | - Integridad de datos<br>- Normalización<br>- Rendimiento<br>- Seguridad<br>- Consistencia con requerimientos |
| **CE023** Programación | Sistema de software funcional, integrado y coherente con el problema planteado, implementado mediante una arquitectura adecuada | **Sistema desarrollado:**<br>- Implementación funcional<br>- Integración de componentes<br>- Arquitectura aplicada<br>- Despliegue operativo | - Funcionalidad completa<br>- Integración entre componentes<br>- Calidad del código<br>- Arquitectura implementada<br>- Desempeño del sistema<br>- Coherencia con el problema |
| **CE024** Calidad de Software | Sistema validado, automatizado y evaluado con evidencia de calidad técnica y mejora continua | **Sistema validado y gestionado:**<br>- Pruebas automatizadas<br>- Pipeline CI/CD<br>- Evidencia de calidad técnica<br>- Auditoría + plan de evolución | - Cobertura y efectividad de pruebas<br>- Automatización (CI/CD)<br>- Calidad técnica<br>- Métricas del sistema<br>- Propuesta de mejora continua |

## Integración del perfil

```mermaid
flowchart LR
CE021 --> EPE[Sistema EPE]
CE022 --> EPE
CE023 --> EPE
CE024 --> EPE
```
