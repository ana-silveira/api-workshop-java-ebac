# workshop JAVA + Spring Boot : Escola Britânica de Artes Criativas & Tecnologia (EBAC)
 
## Fluxo básico da prática: Iniciação de um modelo de MVC [Model - View - Controller]

1. O usuário realiza uma requisição (request) ao controlador (controller) via aplicação web (API + site);
2. O controlador busca as informações no banco de dados, estas são salvas no modelo (model);
3. A informação do modelo é mapeada numa resposta (response), que é enviada de volta ao usuário por uma camada de visualização (view). 

## REST:
É um conjunto de princípios de arquitetura que atende as necessidades de aplicações Mobile e serviços WEB.
Quando um cliente faz uma solicitação utilizando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante (ou endpoint). 

Cliente <----> JSON <----> [ GET / POST / PUT / DELETE ] <----> HTTP <----> Servidor
