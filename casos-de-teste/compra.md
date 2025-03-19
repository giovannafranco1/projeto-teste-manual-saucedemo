# Casos de Teste - Funcionalidade de Compras

## Cenário 1: Adicionar um produto ao carrinho e finalizar a compra

### Passos:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Faça login com o usuário `standard_user` e senha `secret_sauce`.
3. Na página de produtos, clique no botão **Add to cart** ao lado do produto "Sauce Labs Backpack".
4. Clique no ícone do carrinho no canto superior direito.
5. Na página do carrinho, clique no botão **Checkout**.
6. Preencha os campos:
   - First Name: `Teste`
   - Last Name: `Compra`
   - ZIP Code: `12345`
7. Clique no botão **Continue**.
8. Na página de revisão, clique no botão **Finish**.

### Resultado Esperado:
- A compra deve ser finalizada com sucesso, e a mensagem "Thank you for your order!" deve ser exibida.

### Evidência:
![Compra finalizada com sucesso](/evidencias/compra-sucesso.png)

---

## Cenário 2: Tentar finalizar a compra sem preencher os dados de entrega

### Passos:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Faça login com o usuário `standard_user` e senha `secret_sauce`.
3. Na página de produtos, clique no botão **Add to cart** ao lado do produto "Sauce Labs Backpack".
4. Clique no ícone do carrinho no canto superior direito.
5. Na página do carrinho, clique no botão **Checkout**.
6. Deixe todos os campos em branco e clique no botão **Continue**.

### Resultado Esperado:
- Uma mensagem de erro deve ser exibida: "Error: First Name is required".

### Evidência:
![Erro ao finalizar compra](/evidencias/compra-erro.png)
