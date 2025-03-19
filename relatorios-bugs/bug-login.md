# Relatório de Bug - Funcionalidade de Login

## Descrição:
Ao tentar fazer login sem preencher o campo de senha, a mensagem de erro não é exibida corretamente.

## Passos para Reproduzir:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Insira o usuário `standard_user`.
3. Deixe o campo de senha vazio.
4. Clique no botão "Login".

## Comportamento Esperado:
- Uma mensagem de erro deve ser exibida: "Epic sadface: Password is required".

## Comportamento Observado:
- Nenhuma mensagem de erro é exibida.

## Evidência:
![Bug no login](/evidencias/bug-login.png)
