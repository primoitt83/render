FROM docker.n8n.io/n8nio/n8n:latest

ENV \
    ## db 
    - DB_TYPE=postgresdb && \
    - DB_POSTGRESDB_DATABASE=meupostgres_g1un && \
    - DB_POSTGRESDB_HOST=dpg-d06ju4buibrs73em5k30-a && \
    - DB_POSTGRESDB_PORT=5432 && \
    - DB_POSTGRESDB_USER=meupostgres && \       
    - DB_POSTGRESDB_PASSWORD=cLnHE9kOkqg6ut3POER93K7iHYw4aHeN && \
    ## n8n                         
    - N8N_HOST=n8n.local && \
    - N8N_PORT=5678 && \                    
    - N8N_PROTOCOL=http && \                        
    - N8N_RUNNERS_ENABLED=true && \
    - NODE_ENV=production && \             
    - WEBHOOK_URL=http://n8n.local:5678 && \
    - TZ=America/Sao_Paulo && \
    - GENERIC_TIMEZONE=America/Sao_Paulo && \
    - N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=true
    
VOLUME ["/home/node/.n8n"]