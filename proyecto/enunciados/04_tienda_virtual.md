# 04 · Tienda virtual de la facultad
**Contexto:** la tienda de productos institucionales (polos, stickers) quiere vender en línea con catálogo y carrito simple.
**Objetivo:** mini-tienda 3 capas: front contenedor, API de pedidos, base de datos; imágenes por CDN.
**Servicios obligatorios:** ECS Fargate · RDS · S3 + CloudFront para estáticos · CloudFormation completo.
**Restricciones:** front y back separados (2 contenedores mínimo) · presupuesto objetivo ≤ 20 USD/mes · datos sensibles solo en RDS encriptado.
**Entregables clave:** flujo de compra completo (catálogo → pedido) · backup/restore de RDS demostrado · diagrama con zonas de disponibilidad.
**Reto extra:** cola SQS para pedidos y worker que los procesa asíncrono.
