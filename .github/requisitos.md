# Requisitos do Sistema

Requisitos funcionais, não funcionais e regras de negócios para um sistema web simples de organização de tarefas denominado 'FlowTask'

## Requisitos Funcionais

- RF01 - Tela de Cadastro
  - Nome de Usuário, E-mail e Senha
- RF02 - Tela de Login
  - E-mail e Senha
- RF03 - Tela de Tarefas
  - Cada tarefa é registrada pelo usuário que a criou
- RF04 - Autenticação de Usuário
  - Autenticação realizada com JWT

## Requisitos não Funcionais

- RNF01 - Segurança de Senha
  - Senha criptografada com bcrypt
- RNF02 - Tempo de Autenticação
  - Token JWT com tempo de expiração de uma hora

##Regras de Negócio

- RG01 - Tamanho do Nome de Usuário
  - O nome de usuário não deve ultrapssar 10 caracteres
- RG02 - Senha de Usuário
  - A senha deve ter, no mínimo, 3 caracteres maiúsculas
