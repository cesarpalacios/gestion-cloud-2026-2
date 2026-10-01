# 03 · Sistema de asistencia con QR (serverless)
**Contexto:** controlar asistencia a laboratorios sin servidores: el estudiante escanea un QR único por sesión y queda registrado.
**Objetivo:** API 100% serverless con función que registra asistencia y un reporte básico.
**Servicios obligatorios:** API Gateway · Lambda · DynamoDB · S3 (reporte estático) · CloudFormation completo.
**Restricciones:** cero instancias EC2 · presupuesto objetivo ≤ 1 USD/mes (pay per use) · QR generado por la propia app.
**Entregables clave:** endpoint de registro funcionando · reporte HTML generado automáticamente · explicación de por qué serverless aquí (costo por solicitud).
**Reto extra:** alerta por correo (SNS) cuando un estudiante supere el límite de inasistencias.
