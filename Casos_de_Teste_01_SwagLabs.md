Casos de Teste 01 - Swag Labs
Módulo: Carrinho e Checkout
Autor: Natt (QA)

---

ID: CT-001 
Título: Adicionar produto ao carrinho e concluir a compra com sucesso (End-to-End)
Pré-condições: O usuário deve estar logado no sistema e na página de inventário.

Passos: 
1. Clicar no botão 'Add to cart' do produto escolhido.
2. Clicar no ícone de carrinho no canto superior direito da tela.
3. Na tela do carrinho, clicar no botão verde 'Checkout'.
4. Preencher os campos 'First Name', 'Last Name' e 'Postal Code'.
5. Clicar no botão verde 'Continue'.
6. Conferir as informações da compra na tela de Overview e clicar no botão 'Finish'.
Resultado Esperado: O sistema deve exibir a tela de confirmação ("Checkout: Complete!") contendo a mensagem "Thank you for your order! Your order has been dispatched...".

---

ID:CT-002 
Título: Tentar avançar no checkout sem preencher os dados obrigatórios do cliente (Caminho Triste)
Pré-condições: O usuário deve estar logado e com pelo menos um item no carrinho.
Passos:
1. Acessar o ícone do carrinho e clicar em 'Checkout'.
2. Na tela de dados (Your Information), deixar os campos 'First Name', 'Last Name' e 'Postal Code' em branco.
3. Clicar no botão 'Continue'.
Resultado Esperado: O sistema não deve avançar para a próxima tela e deve exibir uma mensagem de erro vermelha informando que o campo é obrigatório (Ex: "Error: First Name is required").
