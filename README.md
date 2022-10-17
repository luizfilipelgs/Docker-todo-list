# Boas-vindas ao repositório do projeto Docker Todo List!



## 👨‍💻 O que foi desenvolvido

1. **_Conteinerizar_** aplicações;
2. Criar uma conexão entre elas;
3. Orquestrar seu funcionamento.

Temos [uma aplicação full-stack](docker/todo-app) neste repositório: um **aplicativo de tarefas**! Esta aplicação precisa ser conteinerizada para funcionar. Foi desenvolvido os arquivos de configuração para cada frente específica: `Front-end`, `Back-end` e, no nosso caso, para um aplicativo de `teste` que valida se as aplicações estão se comunicando.

Foi criado as imagens para as aplicações e configuradas com o `docker-compose`. Para isto, utilizei uma série de comandos do `docker` com diferentes níveis de complexidade, cada comando foi escrito em seu próprio arquivo para serem avaliados pelos testes da Trybe.


## Requisitos obrigatórios do projeto

### Comandos docker

- [x] 1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12`

- [x] 2. Inicie o container `01container`


- [x] 3. Liste os containers filtrando pelo nome `01container`

- [x] 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

- [x] 5. Remova o container `01container`

- [x] 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container

- [x] 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro

- [x] 8. Pare o container `02images` que está em andamento

- [x] 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`

- [x] 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`

- [x] 11. Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`

## Requisito bônus do projeto

### Docker-compose

- [x] 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar
