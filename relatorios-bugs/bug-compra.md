# Relatório de Bug - Funcionalidade de Compras

## Descrição:
Ao tentar finalizar uma compra sem adicionar um produto ao carrinho, o sistema permite prosseguir com o checkout, resultando em uma compra sem itens.

## Passos para Reproduzir:
1. Acesse o site [Saucedemo](https://www.saucedemo.com/).
2. Faça login com o usuário `standard_user` e senha `secret_sauce`.
3. Clique no ícone do carrinho no canto superior direito (sem adicionar nenhum produto).
4. Na página do carrinho, clique no botão **Checkout**.
5. Preencha os campos:
   - First Name: `Teste`
   - Last Name: `Compra`
   - ZIP Code: `12345`
6. Clique no botão **Continue**.
7. Na página de revisão, clique no botão **Finish**.

## Comportamento Esperado:
- O sistema deve exibir uma mensagem de erro informando que o carrinho está vazio e não permitir prosseguir com o checkout.

## Comportamento Observado:
- O sistema permite finalizar a compra sem itens no carrinho, exibindo a mensagem "Thank you for your order!".

## Evidência:
![Compra sem itens no carrinho](/evidencias/bug-compra.png)
