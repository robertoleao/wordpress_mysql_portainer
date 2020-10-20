# wordpress_mysql_portainer
##### Só funciona com o Modo Docker Swarm no Docker Engine 1.12.0 e posteriormente. Não funciona com o projeto separado do Docker Swarm

Docker swarm

Neste compose será configurado o wordpress o mysql , o proteiner e visualizer.

O WordPress é um projeto de código aberto que você pode usar para criar sites, blogs ou aplicativos. É mais usado por blogueiros, pequenos negócios e empresas da Fortune 500 do que todas as outras opções combinadas. 

O MySQL é um sistema de gerenciamento de banco de dados, que utiliza a linguagem SQL como interface. É atualmente um dos sistemas de gerenciamento de bancos de dados mais populares da Oracle Corporation, com mais de 10 milhões de instalações pelo mundo.
Portainer simplifica o gerenciamento de contêineres nos ambientes Docker, Swarm, Kubernetes, ACI e Edge. É usado por engenheiros de software para acelerar implantações de software, solucionar problemas e simplificar a migração

O visualizar mostrara cada nó no enxame mostrará todas as tarefas em execução nele. Quando um serviço cair, ele será removido.

Para roda você precisara de um cluste de docker swarm (maneger e worker)

Tutorial

instaler o docker 
https://docs.docker.com/engine/install/ubuntu/

Clone o repositório
```
$ git clone https://github.com/robertoleao/wordpress_mysql_portainer.git
```
Na pasta do projeto executer
```
$ docker stack deploy -c docker-compose.yaml app
```
