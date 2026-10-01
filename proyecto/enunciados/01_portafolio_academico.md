# 01 · Portafolio académico del programa
**Contexto:** el programa quiere un sitio público donde mostrar proyectos de los estudiantes, rápido y barato, que soporte picos de visitas en épocas de entregas.
**Objetivo:** sitio estático (o generador como Hugo/Astro) servido con CDN, desplegado automáticamente desde GitHub.
**Servicios obligatorios:** S3 (hosting) · CloudFront (CDN) · ACM (HTTPS) · CloudFormation (todo el entorno) · GitHub Actions (deploy).
**Restricciones:** sin servidores administrados (0 EC2) · presupuesto objetivo ≤ 3 USD/mes · DNS con Route 53 (opcional).
**Entregables clave:** URL pública con HTTPS · pipeline que publica en cada push a main · informe de costos real vs objetivo.
**Reto extra:** versión "staging" y "producción" con el mismo template y parámetros distintos.
