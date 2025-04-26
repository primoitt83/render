FROM docker.n8n.io/n8nio/n8n:latest

ENV \                     
    - N8N_HOST=n8n-fjrp.onrender.com && \
    - N8N_PORT=5678 && \                    
    - N8N_PROTOCOL=https && \                        
    - N8N_RUNNERS_ENABLED=true && \
    - NODE_ENV=production && \    
    - WEBHOOK_URL=https://n8n-fjrp.onrender.com && \
    - TZ=America/Sao_Paulo && \
    - GENERIC_TIMEZONE=America/Sao_Paulo && \
    - N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=true

# URL esperada = https://n8n-fjrp.onrender.com/workflow/rest/oauth2-credential/callback

VOLUME ["/home/node/.n8n"]