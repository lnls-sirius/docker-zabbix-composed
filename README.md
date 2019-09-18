Docker image default configurations for Zabbix Agent server
================================

## Run Instructions

### Run container in swarm mode (preferred method)

    docker stack deploy --compose-file=zabbix-agent-stack.yml zabbix

### Run container in compose mode

    docker-compose up -d
