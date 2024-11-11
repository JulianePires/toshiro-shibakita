# Projeto Toshiro Shibakita

Este projeto consiste em uma arquitetura de microsserviços, onde cada diretório representa um microsserviço independente. Cada microsserviço será instanciado em sua própria instância EC2 e todos serão integrados utilizando Docker Swarm.

## Estrutura do Projeto

- **Microsserviço 1**: Banco de dados Mysql.
- **Microsserviço 2**: Servidor nginx com arquivo php.

## Tecnologias Utilizadas

- **Docker Swarm**: Para orquestração dos containers.
- **Amazon EC2**: Para hospedagem dos microsserviços.

## Como Executar

1. Clone o repositório.
2. Configure suas instâncias EC2.
3. Utilize Docker Swarm para integrar os microsserviços.