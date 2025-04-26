FROM docker.n8n.io/n8nio/n8n:latest

ENV \
    ## db 
    - DB_TYPE=postgresdb && \
    - DB_POSTGRESDB_DATABASE=postgres && \
    - DB_POSTGRESDB_HOST=postgres-n8n && \
    - DB_POSTGRESDB_PORT=5432 && \
    - DB_POSTGRESDB_USER=postgres && \       
    - DB_POSTGRESDB_PASSWORD=df434243f7154ba519dc9fdab2fa2b90 && \
    ## n8n                         
    - N8N_HOST=n8n.local && \
    - N8N_PORT=5678 && \                    
    - N8N_PROTOCOL=http && \                        
    - N8N_RUNNERS_ENABLED=true && \
    - NODE_ENV=production && \             
    - WEBHOOK_URL=http://n8n.local:5678 && \
    - TZ=America/Sao_Paulo && \
    - GENERIC_TIMEZONE=America/Sao_Paulo
    
VOLUME ["/home/node/.n8n"]