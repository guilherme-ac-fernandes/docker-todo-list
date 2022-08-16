# Docker Todo List 🐳

Projeto para aplicar os conhecimentos de conteinerização de aplicações e a criação de conexão entre o `front-end`, `back-end` e `testes`.  

* Projeto desenvolvido utilizando Docker

### Comandos
Os comandos a seguir consiste na aplicações do conhecimento de docker, os comandos estão presentes no diretório `./docker/docker-commands`:

| Comando | Descrição |
|---|---|
| `1` | Criar um container utilizando a imagem `alpine` na versão `3.12` de forma interativa sem execução, nomeando como `01container` |
| `2` | Realizar a inicialização do container `01container` |
| `3` | Listar todos os container, realizando a filtragem pelo nome `01container` |
| `4` | Executar o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele |
| `5` | Remover o container `01container` |
| `6` | Realizar apenas o download da imagem `nginx` com a versão `1.21.3-alpine` |
| `7` | Inicializar um novo container com a imagem `nginx` na versão `1.21.3-alpine`, onde deve ser: em segundo plano, nomeando-o como `02images` e rodando na porta 3000 |
| `8` | Parar o container `02images` |
| `9` | Gerar um build a partir do DockerFile do back-end nomeando a imagem como `todobackend` |
| `10` | Gerar um build a partir do DockerFile do front-end nomeando a imagem como `todofrontend`  |
| `11` | Gerar um build a partir do DockerFile dos testes nomeando a imagem como `todotests` |
| `12` | Criar um docker-compose de forma a criar a comunicação entre o `back-end`, `front-end` e `testes` |
