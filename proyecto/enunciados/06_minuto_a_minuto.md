# 06 · Minuto a minuto de torneos deportivos
**Contexto:**Seguir los partidos de la liga universitaria en vivo genera picos: miles leyendo y pocos escribiendo.
**Objetivo:** API de eventos con patrón publicador/suscriptor que aguante picos de lectura.
**Servicios obligatorios:** EC2/ECS (API) · SQS o SNS (cola de eventos) · ElastiCache o CloudFront (caché de lectura) · CloudFormation.
**Restricciones:** simulador de carga incluido · presupuesto objetivo ≤ 15 USD/mes · métricas de latencia bajo pico.
**Entregables clave:** endpoint de eventos en vivo · demo del pico (simulador) · explicación del patrón fan-out elegido.
**Reto extra:** dos canales (vivo y resumen) con prioridad distinta.
