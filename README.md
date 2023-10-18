<h1 align="center"> Microsserviços Java com Spring Boot e Spring Cloud </h1>

<h3>Conteudos abordados:</h3> 
- Feign para requisições de API entre microsserviços

- Ribbon para balanceamento de carga
  
- Servidor Eureka para registro dos microsserviços
- API Gateway Zuul para roteamento e autorização
- Hystrix para tolerância a falhas
- OAuth e JWT para autenticação e autorização
- Servidor de configuração centralizada com dados em repositório Git
- Geração de containers Docker para os microsserviços e bases de dados


Para: gerar a build via power shell adm; gerar Dockerfile em cada microsserviço; gerar a imagem docker (necessário especificar a porta, nome do container e rede). 
Será necessário consultar os comandos no GitHub do professor Nelio atraves do link: https://github.com/acenelio/ms-course

<h3> Comandos auxiliares Docker: </h3>
- Validar quais containers estão sendo executados (via powershell adm):
docker ps

- Para verificar quais containers estão ou não em execução:
docker ps -a

- Verificar logs
docker logs -f nome-img-do-banco (EXEMPLO: hr-user-pg12)

- Pausar uma instância de um container:
docker stop id-do-container

Para todas as requisições, foi utilizado o software <b>Postman</b>
