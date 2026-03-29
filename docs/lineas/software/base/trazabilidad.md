# 6. Trazabilidad completa

!!! success "Valor de esta matriz"
    Esta matriz garantiza que cada competencia:
    - se desarrolla
    - se evidencia
    - se integra
    - se valida en el EPE
    
## Trazabilidad completa — Línea Software (versión final)

| CE | Subcompetencia | Evidencias (CE02xx) | Cursos | Productos de curso (U3) |
|---|---|---|---|---|
| **CE021** | Ingeniería de Requerimientos | CE0211 SRS<br>CE0212 Prototipos<br>CE0213 Arquitectura<br>CE0214 UML | IR (c3)<br>ADS (c4) | **IR:** SRS + prototipos validados<br><br>**ADS:** Arquitectura del sistema + UML completo |
| **CE022** | Ingeniería de la Información | CE0221 Modelo de datos<br>CE0222 SQL<br>CE0223 Programación BD<br>CE0224 Seguridad / Administración BD | BD1 (c3)<br>BD2 (c4) | **BD1:** Modelo + SQL funcional<br><br>**BD2:** Base de datos operativa segura y optimizada |
| **CE023** | Programación | CE023a Aplicación consola<br>CE023b Aplicación desktop<br>CE023c Aplicación web MVC<br>CE023d Aplicación full-stack<br>CE023e Microservicios<br>CE023f Aplicación móvil | FP (c1)<br>POO (c2)<br>LP1 (c3)<br>LP2 (c4)<br>DIST (c5)<br>MOV (c6) | **Sistemas progresivos:**<br>- Consola<br>- Desktop<br>- Web MVC<br>- Full-stack<br>- Microservicios<br>- Aplicación móvil<br><br>*(El tipo de sistema depende del problema y debe justificarse)* |
| **CE024** | Calidad de Software | CE0241 Pruebas automatizadas<br>CE0242 Pipeline CI/CD<br>CE0243 Gestión técnica del desarrollo<br>CE0244 Auditoría y evolución | IS1 (c6)<br>PDS (c7)<br>IS2 (c7) | **IS1:** Gestión técnica del desarrollo (decisiones, deuda técnica, calidad en desarrollo)<br><br>**PDS:** Sistema con pruebas automatizadas + CI/CD<br><br>**IS2:** Sistema evaluado + métricas + plan de mejora |

## Relación completa

```mermaid
flowchart TD
A[Competencias] --> B[Evidencias]
B --> C[Cursos]
C --> D[Productos U3]
D --> E[EPE]
```


### Principios de trazabilidad

- Cada competencia tiene evidencias progresivas
- Cada evidencia corresponde a cursos
- Las evidencias convergen en un artefacto EPE
- Cada artefacto se evalúa con rúbrica específica
- La evaluación se basa en productos reales

---

### Garantía de calidad

El modelo asegura:

- Coherencia entre formación y evaluación
- Evaluación basada en evidencia observable
- Separación clara de competencias (CE021–CE024)
- Independencia tecnológica
- Alineación con el perfil de egreso

---

### Declaración final

La trazabilidad del programa permite demostrar que cada competencia es desarrollada progresivamente y evaluada mediante productos reales, garantizando consistencia, objetividad y alineación con estándares de ingeniería de software.