Relatório de Sessão Exploratória

Projeto: Swag Labs  
Data: 30/03/2026  
QA: Nataly R  
Duração da Sessão: 10 minutos  

Test Charter (Missão de Teste)
-O que testar: Carrinho (Checkout).
-Como testar: Seguir a compra preenchendo o campo 'First Name' de 'Your Information' em branco, testando também outros usuários e entradas maliciosas ou apenas com espaços.
-O que descobrir: Se é possível concluir a compra sem fornecer informações importantes de entrega.

---

Anotações da Execução
- Loguei com o usuário `standard_user`, adicionei uma camisa no carrinho.
- Fui para o checkout, e tentei prosseguir com o campo `First Name` preenchido apenas com o número ' 2', deixando o campo `Last Name` sem preenchimento.
- Cliquei em 'Continue' (Checkout) e a tela seguiu para finalizar a compra normalmente.

Problemas / Bugs Encontrados
- Problema 1 (Comportamento Esperado):** Se eu não preencho nada nos 2 campos de nome (first e last), uma mensagem de erro informa "Error: Last Name is required" ou similar. (Neste caso, o sistema validou corretamente a falta dos campos).
- Problema 2 (BUG CRÍTICO!): A compra seguiu normalmente mesmo faltando informação importante (Sobrenome em branco e Primeiro Nome contendo apenas um número). Isso impactaria criticamente a entrega do produto, causando prejuízo logístico.

Ideias e Riscos (Futuro)
- Testar se é possível seguir a compra com um CEP (Zip Code) inválido, contendo letras, ou apenas espaços.
