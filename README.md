# platform.pokerber



# Arquitetura do Projeto Pokerber

O projeto **Pokerber** é uma plataforma desenvolvida para permitir que os usuários registrem seus jogos de poker entre amigos e criem torneios. Utilizamos Jenkins, Docker, Swagger e Kubernetes para garantir escalabilidade, flexibilidade e facilidade de manutenção.

## 1. Jenkins

Utilizamos **Jenkins** para automatizar o processo de integração contínua (CI) e entrega contínua (CD). Ele compila, testa e implanta o aplicativo de forma automatizada, garantindo que cada alteração no código-fonte seja rapidamente integrada e entregue.

## 2. Docker

**Docker** é usado para criar contêineres que empacotam a aplicação e suas dependências, garantindo um ambiente consistente em diferentes sistemas. Isso facilita a portabilidade e o isolamento dos serviços.

## 3. Swagger

**Swagger** é utilizado para documentar a API do Pokerber. Ele gera documentação interativa, facilitando o entendimento e o teste das APIs pelos desenvolvedores.

## 4. Kubernetes

**Kubernetes** orquestra os contêineres Docker, gerenciando a implantação, escalonamento e operações de contêineres em clusters. Ele garante alta disponibilidade e permite escalabilidade automática com base na demanda do tráfego.

## Fluxo de Trabalho

1. **Desenvolvimento e Teste**: Código versionado em um repositório Git.
2. **Integração Contínua (CI)**: Jenkins compila, testa e cria imagens Docker.
3. **Entrega Contínua (CD)**: Jenkins envia as imagens Docker para um registro de contêiner.
4. **Implantação**: Kubernetes implanta as imagens Docker no cluster.
5. **Monitoramento e Manutenção**: Kubernetes monitora e ajusta os contêineres automaticamente.

## Conclusão

A arquitetura do Pokerber, utilizando Jenkins, Docker, Swagger e Kubernetes, oferece uma plataforma robusta, escalável e de fácil manutenção, permitindo que a equipe de desenvolvimento se concentre em melhorar a experiência do usuário.


## Links dos repositorios realizados
| **Microserviço**                     | **Descrição**                                             | **Link**                                                                                                                                |
|--------------------------------------|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **platform.pokerber.auth**           | Autenticação e autorização.                               | [Auth](https://github.com/Enzoq2202/platform.pokerber.auth)                                                                             |
| **platform.pokerber.auth-resource**  | Recursos relacionados à autenticação.                     | [Auth-Resource](https://github.com/Enzoq2202/platform.pokerber.auth-resource)                                                           |
| **platform.pokerber.account**        | Gerenciamento de contas de usuários.                      | [Account](https://github.com/Enzoq2202/platform.pokerber.account)                                                                       |
| **platform.pokerber.account-resource**| Recursos relacionados a contas de usuários.               | [Account-Resource](https://github.com/Enzoq2202/platform.pokerber.account-resource)                                                     |
| **platform.pokerber.discovery**      | Serviço de descoberta.                                    | [Discovery](https://github.com/Enzoq2202/platform.pokerber.discovery)                                                                   |
| **platform.pokerber.gateway**        | Gateway API.                                              | [Gateway](https://github.com/Enzoq2202/platform.pokerber.gateway)                                                                       |
| **platform.pokerber.winrecord**      | Gerenciamento de registros de vitórias.                   | [WinRecord](https://github.com/Enzoq2202/platform.pokerber.winrecord)                                                                   |
| **platform.pokerber.winrecord-resource** | Recursos relacionados a registros de vitórias.         | [WinRecord-Resource](https://github.com/Enzoq2202/platform.pokerber.winrecord-resource)                                                 |
| **platform.pokerber.tournamentmanager** | Gerenciamento de torneios.                              | [TournamentManager](https://github.com/Enzoq2202/platform.pokerber.tournamentmanager)                                                   |
| **platform.pokerber.tournamentmanager-resource** | Recursos relacionados a torneios.                       | [TournamentManager-Resource](https://github.com/Enzoq2202/platform.pokerber.tournamentmanager-resource)                                 |
| **platform.pokerber.ops**            | Operações e monitoramento.                                | [Ops](https://github.com/Enzoq2202/platform.pokerber.ops)                                                                               |
| **platform.pokerber.docker-api**     | API Docker.                                               | [Docker-API](https://github.com/Enzoq2202/platform.pokerber.docker-api)                                                                 |
| **platform.pokerber.redis**          | Cache Redis.                                              | [Redis](https://github.com/Eduardosmb/platform.pokerber.redis)                                                                          |
| **platform.pokerber.db**             | Banco de dados.                                           | [DataBase](https://github.com/Eduardosmb/platform.pokerber.db)                                                                          |
| **Apresentação do projeto**          | Apresentação do projeto na plataforma Canva.              | [Apresentação](https://www.canva.com/design/DAGGGXLnmVs/KKME0AYe1xUHW4zEkc6RXg/edit?utm_content=DAGGGXLnmVs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) |
