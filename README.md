## Next.js Fullstack Docker

Este projeto tem como objetivo demonstrar a criação de uma aplicação fullstack utilizando Next.js e Postgres, com todo o ambiente configurado via Docker Compose e variáveis de ambiente. Além disso, o projeto passa por um processo de refatoração para aprimorar a qualidade do código, e explora as vantagens de usar um ORM (Object-Relational Mapping), no caso o Prisma, para facilitar a interação com o banco de dados e gerenciar migrações e queries de forma mais simples e organizada.

Principais Características
	- Configuração via Docker Compose:
Todo o ambiente, incluindo o banco de dados Postgres e a aplicação Next.js, é orquestrado pelo Docker Compose. Isso garante uma configuração padronizada e fácil de replicar, independente da máquina de desenvolvimento.
	- Variáveis de Ambiente:
O uso de variáveis de ambiente simplifica a mudança de configurações, como as credenciais do banco de dados, sem precisar alterar o código-fonte. Isso torna o projeto mais seguro, portável e fácil de manter.
	-	Refatoração de Código:
O projeto parte de uma base existente e é aprimorado através de técnicas de refatoração, resultando em um código mais legível, sustentável e escalável.
	-	Vantagens de um ORM (Prisma):
	-	Abstração do Acesso ao Banco de Dados: Em vez de escrever queries SQL diretamente, o ORM fornece uma camada de abstração em JavaScript/TypeScript.
	-	Migrations Automatizadas: Gerenciamento de migrações de banco de dados de forma mais simples e coesa, facilitando a evolução do esquema de dados ao longo do tempo.
	-	Tipagem e Autocompletar: Ao usar o Prisma, é possível ter autocompletar e checagem de tipos, reduzindo erros e aumentando a produtividade.
	-	Portabilidade: Mudanças de bancos de dados tornam-se mais fáceis, pois o código é menos acoplado a um SQL específico.
	-	Queries e Migrations com Prisma:
O projeto demonstra a criação e execução de migrações, além de operações CRUD, tudo gerenciado pelo Prisma. Isso torna o desenvolvimento mais ágil e seguro, reduzindo a probabilidade de erros manuais nas queries.
	-	Aplicação Fullstack com Next.js e Postgres:
A aplicação une o poder do Next.js (renderização do lado do servidor, otimização de performance e rotas simplificadas) com um banco de dados robusto (Postgres), possibilitando construir funcionalidades complexas, persistência de dados e uma experiência completa em um só stack.
