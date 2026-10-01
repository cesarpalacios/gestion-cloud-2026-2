# 07 · Gestor de archivos con recuperación ante desastres
**Contexto:** un centro de datos necesita guardar documentos con respaldo en otra región y ciclo de vida por antigüedad.
**Objetivo:** almacenamiento con replicación cross-region, versionado y archivo automático a Glacier.
**Servicios obligatorios:** S3 (versionado + replication cross-region) · lifecycle a Glacier · IAM mínimo necesario · CloudFormation.
**Restricciones:** presupuesto objetivo ≤ 8 USD/mes · política de retención documentada · simulación de "pérdida" de la región primaria.
**Entregables clave:** subida/descarga funcionando · demostración de failover a la copia · tabla de costos por GB y por recuperación.
**Reto extra:** eventos (S3 → SNS/Lambda) que notifican cada archivo crítico subido.
