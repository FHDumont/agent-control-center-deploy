# Agent Control Center

O Agent Control Center lista os agentes do AppDynamics, mostra suas configurações de execução e realiza a atualização de versão.

## Requerimentos

- Docker
- Docker-compose

## Instalação e Configuração

1. Clone o repositório "agent-control-center-deploy" usando o comando `git clone <repoUrl>`
2. Execute: docker-compose up -d

## Como Usar

Após iniciar a execução do Agent Control Center, acesse no Navegador Web o endereço http://localhost.

No menu lateral, clique em AppDynamics > Agents. Todos os agentes do ambiente da AppDynamics serão listados.

![01](https://github.com/FHDumont/agent-control-center-deploy/blob/main/images/01.agents.png?raw=true)

Para atualizar a versão do agente, clique no "play" correspondendo ao agente

Informe a nova versão do agente e a chave de acesso ao servidor, depois clique em "Create Task".

![02](https://github.com/FHDumont/agent-control-center-deploy/blob/main/images/02.createTask.png?raw=true)

Será criada a tarefa do ansible que está preparado para fazer a atualização de versão do agente.

![03](https://github.com/FHDumont/agent-control-center-deploy/blob/main/images/03.tasks.png?raw=true)

![04](https://github.com/FHDumont/agent-control-center-deploy/blob/main/images/04.health.png?raw=true)
