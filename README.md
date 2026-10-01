# ☁️ Gestión de Tecnologías en la Nube — 2026-2

Ecosistema del curso (UNAL): proyecto del semestre, laboratorios y rúbricas. Todo el trabajo de los equipos vive en GitHub.

## 🗺️ Mapa del repositorio
| Carpeta | Qué contiene |
|---|---|
| `proyecto/` | Reglas, hitos semanales y los **8 proyectos base** (cada equipo escoge uno, sin repetir) |
| `plantilla-equipo/` | Repositorio plantilla que cada equipo copia con *"Use this template"* |
| `laboratorios/` | Lab 01–06 con la evidencia exigida (Nota 5) |
| `rubricas/` | Rúbrica de Arquitectura (Nota 2) y de Sustentación (Nota 3) |
| `.starter/` | LocalStack para practicar **CloudFormation gratis en local** |

## 🧰 Stack del curso
- **AWS** (cuenta de AWS Academy — se abre en la semana 2)
- **Docker** (la app del proyecto viaja en contenedor)
- **AWS CloudFormation** — la infraestructura se entrega **como código (IaC)** en YAML
- **GitHub + Actions** — versionamiento, PRs y pipeline de validación

## 📜 Reglas de trabajo (Git)
1. Cada equipo crea su repositorio desde `plantilla-equipo` (*Use this template*) y lo nombra `gtn-proyecto-<nombre>`.
2. Se trabaja con **ramas + Pull Requests**: nada se sube directo a `main` sin PR.
3. Cada **hito semanal** se entrega cerrando su issue correspondiente (plantilla en `.github/ISSUE_TEMPLATE`).
4. El CI valida automáticamente cada PR: `cfn-lint` sobre la IaC y build del contenedor.
5. El **README del equipo es la carta de presentación**: ficha del caso, arquitectura, costo mensual y URL de la demo.
