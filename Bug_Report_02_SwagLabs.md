# 🐞 Bug Report 02 - Swag Labs

Título: A alteração de quantidade de produto no carrinho de compra não funciona

**Ambiente de Teste:** 
- **URL:** https://www.saucedemo.com/inventory.html
- **Navegador:** Google Chrome (versão mais recente)
- **S.O:** Windows

Passos:
1. Acesse o site https://www.saucedemo.com/
2. Faça login com um usuário válido (ex: `standard_user` ou `problem_user`)
3. Na página da lista de produtos, escolha um ou mais produtos e clique no botão "Add to cart"
4. Clique no ícone do carrinho no canto superior direito da tela.
5. Na nova página que abriu, tente editar inserindo uma quantia maior que 1 na coluna `QTY` da listagem de produtos.

Esperado:
- O cliente deveria poder decidir quantas unidades do mesmo produto gostaria de comprar (ex: alterar para 2 ou mais).

Resultado Atual:
- O cliente não consegue alterar a quantidade e comprar mais de uma unidade do mesmo produto caso queira. O campo `QTY` não permite edição.

Prioridade: Alta (Isso pode impactar no volume de vendas ou o cliente pode desistir da compra por sugerir que o site possui problemas técnicos).

Severidade: Maior (Funcionalidade importante não inclusa na página, mas não impede a finalização da compra de 1 item).

Evidências: 
- 1 vídeo anexo salvo na pasta com o nome: `Swag Labs qty cart.mp4`
