# 🐞 Bug Report 01 - Swag Labs

Título: A ordenação por preço (Low to High / High to Low) não funciona corretamente

**Ambiente de Teste:** 
- **URL:** https://www.saucedemo.com/inventory.html
- Navegador: Google Chrome (versão mais recente)
- S.O: Windows

Passos:
1. Acesse o site https://www.saucedemo.com/
2. Faça login com um usuário válido (ex: `standard_user` ou `problem_user`)
3. Na página da lista de produtos (Inventory), localize o dropdown de filtros no canto superior direito.
4. Selecione a opção "Price (low to high)".
5. Observe a lista de produtos e veja a ordem dos preços.
6. Altere a opção para "Price (high to low)".
7. Observe novamente a ordem dos preços.

Esperado:
- "Price (low to high)": Os produtos deveriam ser organizados do menor valor para o maior.
- "Price (high to low)": Os produtos deveriam ser organizados do maior valor para o menor.

Resultado Atual:
Os produtos não são reordenados conforme a seleção do filtro. A listagem de preços continua incorreta e não segue a ordem matemática selecionada.

Prioridade: Alta (A ordenação de preços é um recurso crítico em e-commerce).

Severidade: Maior (Funcionalidade principal de filtro quebrada, mas não impede a finalização da compra).

Evidências: 
-1 foto anexa
