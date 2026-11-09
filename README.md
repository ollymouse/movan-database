# MOVAN — Banco de Dados

Projeto acadêmico desenvolvido como parte do Trabalho de Conclusão de Curso (TCC), com foco na modelagem e implementação de um banco de dados relacional para um sistema de gerenciamento de transporte escolar.

## Sobre o projeto

O MOVAN tem como proposta organizar informações relacionadas ao transporte escolar, permitindo o gerenciamento de alunos, responsáveis, motoristas, escolas, rotas, contratos, mensalidades e movimentações financeiras.

Este repositório apresenta a estrutura do banco de dados desenvolvido para o projeto, incluindo sua modelagem, definição das tabelas, relacionamentos, restrições e consultas SQL.

## Tecnologias utilizadas

- **PostgreSQL** — Sistema de gerenciamento de banco de dados relacional.
- **Neon Database** — Hospedagem do banco de dados em nuvem.
- **SQL** — Linguagem utilizada na definição e consulta dos dados.

## Modelagem do banco de dados

O banco foi estruturado com entidades relacionadas aos principais módulos do sistema.

Entre as funcionalidades contempladas pela modelagem estão:

- Cadastro de alunos, responsáveis e motoristas.
- Cadastro de escolas e turnos escolares.
- Organização de rotas e pontos de embarque.
- Gerenciamento de contratos e assinaturas.
- Controle de mensalidades.
- Registro de movimentações financeiras.
- Configuração de regras financeiras.
- Gerenciamento de cláusulas e documentos contratuais.

## Organização dos arquivos SQL

| Arquivo | Descrição |
|---|---|
| `01_schema.sql` | Definição da estrutura do banco de dados, incluindo tabelas, tipos, relacionamentos e restrições. |
| `02_queries.sql` | Consultas SQL demonstrativas para exploração das informações do banco. |

## Recursos implementados

- Modelagem relacional.
- Definição de chaves primárias e estrangeiras.
- Utilização de tipos enumerados (ENUM).
- Restrições de integridade e validação de dados.
- Índices para otimização de consultas.
- Views para consulta e organização de informações.
- Relacionamentos entre entidades.
- Consultas utilizando JOIN, GROUP BY, ORDER BY e funções de agregação.

## Como utilizar

1. Instale o PostgreSQL.
2. Crie um banco de dados local para testes.
3. Importe o arquivo `sql/01_schema.sql` para criar a estrutura.
4. Execute as consultas presentes em `sql/02_queries.sql`.

**Observação:** o arquivo de estrutura contém definições SQL do banco original. Verifique eventuais referências a usuários, permissões e extensões antes de executá-lo em outro ambiente.

## Contexto acadêmico

Projeto desenvolvido no contexto do Trabalho de Conclusão de Curso (TCC), como parte do desenvolvimento do sistema MOVAN.

**Responsabilidade neste repositório:** modelagem, estruturação e implementação do banco de dados relacional.


