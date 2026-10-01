# 05 · Dashboard de indicadores estudiantiles
**Contexto:** coordinación quiere visualizar indicadores (deserción, promedios, uso de laboratorios) que hoy viven en CSV.
**Objetivo:** pipeline: ingesta de datos → almacenamiento → visualización.
**Servicios obligatorios:** S3 (data lake crudo) · Athena o Lambda (procesamiento) · QuickSight o contenedor con Grafana (EC2) · CloudFormation.
**Restricciones:** datos ficticios generados por script · presupuesto objetivo ≤ 12 USD/mes · pipeline reproducible (datos → dashboard sin pasos manuales).
**Entregables clave:** dashboard con 4+ gráficas útiles · documentación del modelo de datos · costo por consulta estimado.
**Reto extra:** actualización automática programada (EventBridge).
