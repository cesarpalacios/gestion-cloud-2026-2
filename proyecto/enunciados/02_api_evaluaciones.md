# 02 · API de evaluaciones ( notas en línea )
**Contexto:** los docentes necesitan una API REST para registrar y consultar notas por curso; en temporada de cierre la carga se multiplica.
**Objetivo:** API (contenedor Docker) con base de datos administrada y balanceo, lista para escalar.
**Servicios obligatorios:** EC2 o ECS con ALB · RDS (MySQL/PostgreSQL) · Security Groups por capa · CloudFormation completo.
**Restricciones:** app en contenedor (Dockerfile incluido) · base de datos NO en el contenedor · presupuesto objetivo ≤ 15 USD/mes · pruebas de carga documentadas.
**Entregables clave:** endpoint `/health` y CRUD de notas público para el panel · esquema de BD versionado · arquitectura multi-capa en diagrama.
**Reto extra:** autoescalado del frente web probado con métricas de CloudWatch.
