# 08 · Chatbot de preguntas frecuentes académicas
**Contexto:** las mismas 50 preguntas del programa llegan cada semestre al asistente; quieren responderlas con IA 24/7.
**Objetivo:** chat (web en contenedor) que consulta un modelo y responde desde una base de preguntas/respuestas propia.
**Servicios obligatorios:** Lambda o ECS (API) · Bedrock (modelo) o equivalente en contenedor para demo · DynamoDB (FAQ) · CloudFormation.
**Restricciones:** prompt + contexto documentados · presupuesto objetivo ≤ 10 USD/mes · límite de gasto del modelo configurado.
**Entregables clave:** chat web funcional con historial · 3 ejemplos de respuesta buena y 1 fallida (con mejora) · análisis de costo por consulta.
**Reto extra:** evaluación automática de calidad de respuestas en el pipeline.
