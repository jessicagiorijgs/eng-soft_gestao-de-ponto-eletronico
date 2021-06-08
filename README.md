## Disciplina: Engenharia de Software - I

### Tema: Gestão de ponto eletrônico (ponto-oka)

### Descrição:
A portaria 373, de 2011, do Ministério do Trabalho e Emprego permite o Controle de Ponto por formas alternativas (como aplicativos de controle de ponto). Assim, surgiu a idéia de um aplicativo web simples em que empresas podem beneficiar do controle eletrônico (legal) sobre a jornada de trabalho dos colaboradores, comprovando portanto, de forma efetiva e legal as horas trabalhadas, extras e intervalos intrajornada, evitando assim uma das principais causas de processos trabalhistas. Todos os dados são 100% acessíveis de qualquer lugar, a qualquer hora e podem ser utilizados como prova em casos judiciais.

### Objetivo: 
Sistema web para Controle de Ponto de colaboradores (funcionários).

### Grupo:
  * Christian Vieira (2014106325)
  * Délisson Junio (2015004119)
  * Gabriel Gouvea (2019026150)
  * Jéssica Giori Silva (2017013301)
  * Luiz Felipe Rocha (2017051386)

### Tecnologias:
  #### Backend:
    Docker
    NodeJS
    MongoDB
    RabbitMQ
    Github Actions
  #### Frontend:
    HTML, CSS
    VueJS
### Organização:
    Azure Devops: https://dev.azure.com/jessicagiori/Engenharia%20de%20Software/_backlogs/backlog/Engenharia%20de%20Software%20Team/Epics

### Backlog do Produto:
#### Features:
  1. Cadastro e login de colaboradores e administradores
  2. Registro e alterações de registro de ponto (apontamento de horas)
  3. Extração/exportação de relatórios de pontos (diário, semanal, quinzenal, mensal, intervalo)
  4. Requisição e aprovação de horas extras
  5. Justificativa de ajuste (ausência, atraso, etc) 
  6. Localização do usuário
  7. Relatório sintético (banco de horas, horas extras, faltas e atrasos, absenteísmo 
  
### Backlog da Sprint:

##### Feature 1: Cadastro e login de colaboradores e administradores. Responsável: 
###### Historia 1:

##### Feature 2: Registro e alterações de registro de ponto (apontamento de horas). Responsável: 
###### Historia 1:

##### Feature 3: Requisição e aprovação de horas extras. Responsável: 
###### Historia 1:

##### Feature 4: Justificativa de ajuste (ausência, atraso, etc). Responsável: 
###### Historia 1:

##### Feature 1: Cadastro e login de colaboradores e administradores.
##### Responsável: Délisson Junio

###### Historia 1: Como um usuário, eu gostaria de fazer login no sistema.
    Task 1: Criar tabelas de usuários no banco de dados
    Task 2: Criar tela de login
    Task 3: Receber credenciais do usuário
    Task 4: Validar credenciais no banco de dados
    Task 5: Permitir a entrada do usuário caso as credenciais sejam válidas

###### Historia 2: Como um administrador, eu gostaria de cadastrar um novo colaborador.
    Task 1: Criar tela de cadastro de novo perfil
    Task 2: Armazenar perfil no sistema
    Task 3: Gerar credenciais iniciais
    Task 4: Transmitir credenciais por e-mail

###### Historia 3: Como um usuário, eu gostaria de recuperar meu acesso em caso de perda de credenciais.
    Task 1: Criar botão "esqueci minha senha"
    Task 2: Criar tela de recuperação de credenciais
    Task 3: Receber dados do usuário
    Task 4: Enviar e-mail de verificação
    Task 5: Validar identidade do usuário
    Task 6: Criar tela de escolha de nova senha
    Task 7: Armazenar a nova senha no sistema

###### Historia 4: Como um administrador, eu gostaria visualizar uma lista dos colaboradores no sistema.
    Task 1: Criar tela de listagem de colaboradores com nome e função
    Task 2: Criar tela de visualização de colaborador individual com nome, função, e-mail e telefone

###### Historia 5: Como um administrador, eu gostaria de alterar dados do perfil de outro usuário.
    Task 1: Criar tela de edição de perfil de usuário
    Task 2: Preencher dados na tela com informações do banco de dados
    Task 3: Permitir a edição dos dados
    Task 4: Receber dados alterados e armazenar as novas informações no banco de dados

##### Feature 5: Construção de um Relatório Sintético. Responsável: Jéssica Giori
###### Historia 1: Como um gestor, eu gostaria de consultar o banco de horas do meu departamento utilizando como filtros: período, funcionário ou cargo.
    Task 1: Fazer modelagem do relatório
    Task 2: Modelar query
    Task 3: Implementar relatório
    Task 4: Limitar visualização para o usuário administrador
    Task 5: Fazer commit
    Task 6: Validar

###### Historia 2: Como um gestor, eu gostaria de gerar um relatório de horas extras do meu departamento utilizando como filtros: período, funcionário ou cargo.
    Task 1: Fazer modelagem do relatório
    Task 2: Modelar query
    Task 3: Implementar relatório
    Task 4: Limitar visualização para o usuário administrador
    Task 5: Fazer commit
    Task 6: Validar

###### Historia 3: Como um gestor, eu gostaria de consultar as faltas do meu departamento utilizando como filtros: período, funcionário ou cargo.
    Task 1: Fazer modelagem do relatório
    Task 2: Modelar query
    Task 3: Implementar relatório
    Task 4: Limitar visualização para o usuário administrador
    Task 5: Fazer commit
    Task 6: Validar

###### Historia 4: Como um gestor, eu gostaria de consultar os atrasos ocorridos no meu departamento utilizando como filtros: período, funcionário ou cargo.
    Task 1: Fazer modelagem do relatório
    Task 2: Modelar query
    Task 3: Implementar relatório
    Task 4: Limitar visualização para o usuário administrador
    Task 5: Fazer commit
    Task 6: Validar

###### Historia 5: Como um gestor, eu gostaria de gerar um relatório de absenteísmo do meu departamento utilizando como filtros: período, funcionário ou cargo.
    Task 1: Fazer modelagem do relatório
    Task 2: Modelar query
    Task 3: Implementar relatório
    Task 4: Limitar visualização para o usuário administrador
    Task 5: Fazer commit
    Task 6: Validar
