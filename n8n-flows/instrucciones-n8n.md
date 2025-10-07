# 🔄 Configuración n8n

## Importar Flujo
1. Ir a n8n > Workflows
2. Click "Import from file"
3. Seleccionar `flow-agente-reputacion.json`

## Configurar Credenciales
1. Google Sheets: Service account con permisos de lectura
2. Webhook: Configurar método POST

## Endpoints
- Webhook: `/webhook/agente_prueba`
- Método: POST
- Content-Type: application/json