# Casos de Teste - Funcionalidade de Login

## Cenário 1: Login com credenciais válidas

### Passos:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Insira o usuário `standard_user`.
3. Insira a senha `secret_sauce`.
4. Clique no botão "Login".

### Resultado Esperado:
- O usuário deve ser redirecionado para a página de produtos.

### Evidência:
![Login com sucesso](/evidencias/login-sucesso.png)

---

## Cenário 2: Login com credenciais inválidas

### Passos:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Insira o usuário `usuario_invalido`.
3. Insira a senha `senha_invalida`.
4. Clique no botão "Login".

### Resultado Esperado:
- Uma mensagem de erro deve ser exibida: "Epic sadface: Username and password do not match any user in this service".

### Evidência:
![Login falhou](/evidencias/login-falha.png)

