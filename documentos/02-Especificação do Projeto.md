# Especificações do Projeto

Este documento tem como objetivo apresentar uma visão completa e detalhada das metas, requisitos e funcionalidades que nortearão o desenvolvimento deste projeto. Ele atua como a base conceitual do projeto, oferecendo uma perspectiva ampla e organizada de todas as características planejadas para o software.


## Arquitetura e Tecnologias

Segue abaixo a tabela com as tecnologias utilizadas no desenvolvimento da aplicação.

|Função						         | Ferramenta                                                           |
|---------------------    |----------------------------------------------------------------------|
|IDE						         | Visual Studio Code                  |
|Linguagem Frontend			 | React Native											   |
|Linguagem Backend			 | Node.js													   |
|Framework Frontend			 | Expo												         |
|Framework Backend			 | Express.js												   |
|Banco de dados				   | MongoDB												     |

## Project Model Canvas

<img src="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-2-e5-proj-empext-t4-pmv-ads-2024-2-e5-personalonline/blob/main/documentos/img/project-model-canvas.png" alt="canvas">

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| Permitir que o administrador cadastre contas de alunos. | ALTA |
|RF-02| Permitir que o administrador altere os dados cadastrados das contas dos alunos. | ALTA |
|RF-03| Permitir que o administrador exclua usuários cadastrados. | ALTA |
|RF-04| Permitir que o usuário realize login através de seu e-mail e senha. | MÉDIA |
|RF-05| Permitir que o administrador faça o cadastro dos treinos. | MÉDIA |
|RF-06| Permitir o administrador associar um treino a um aluno. | MÉDIA |
|RF-07| Permitir o usuário aluno e administrador a visualização dos treinos cadastrados. | MÉDIA |
|RF-08| Permitir o administrador altere ou exclua um treino. | MÉDIA |
|RF-09| Permitir o usuário aluno a marcar os exercícios como realizados. | BAIXA |
|RF-10| Permitir que o exercício marcado como realizado seja registrado no histórico do aluno. | BAIXA |
|RF-11| Permitir que o usuário acesse o histórico de suas sessões de treino anteriores. | BAIXA |
|RF-12| Permitir que o usuário visualize e atualize suas informações pessoais, como nome, contato, foto de perfil e alteração de senha. | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| A aplicação deve ser compatível com sistemas Android e iOS | ALTA |
|RNF-02| A aplicação deve possuir interface intuitiva e fácil de usar. | MÉDIA |
|RNF-03| A aplicação deve ser capaz de processar e carregar as informações da conta do usuário de forma rápida para garantir uma experiência de usuário fluida e responsiva. | MÉDIA |

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre. |
|02| A equipe não poderá terceirizar o desenvolvimento. |
|03| O desenvolvimento deverá respeitar o orçamento acordado com o cliente. |

## Diagrama de Casos de Uso

![UML use case_page-0001](https://github.com/user-attachments/assets/acf4a270-25b1-4525-88da-78c7e45a126c)


## Modelo ER (Projeto Conceitual)

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.

Sugestão de ferramentas para geração deste artefato: LucidChart e Draw.io.

A referência abaixo irá auxiliá-lo na geração do artefato “Modelo ER”.

> - [Como fazer um diagrama entidade relacionamento | Lucidchart](https://www.lucidchart.com/pages/pt/como-fazer-um-diagrama-entidade-relacionamento)

## Projeto da Base de Dados

O projeto da base de dados corresponde à representação das entidades e relacionamentos identificadas no Modelo ER, no formato de tabelas, com colunas e chaves primárias/estrangeiras necessárias para representar corretamente as restrições de integridade.
