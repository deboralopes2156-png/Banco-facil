🚀 Nome do Projeto: Banco Fácil

Squad (Equipe):

Integrante 1: Débora – Programadora

Integrante 2: Guilherme – Designer

Integrante 3: Sara – Testadora

Integrante 4: Júlia – Analista de Sistemas

Integrante 5: Manuella – Documentação e Suporte

⸻

🎯 1. Visão do Produto

O programa resolve o problema de pessoas que precisam controlar seu dinheiro de forma simples e rápida.

Com esse sistema, o usuário poderá criar uma conta bancária, depositar dinheiro, sacar dinheiro e consultar seu saldo pelo terminal.

⸻

📦 2. O MVP (Minimum Viable Product)

✔ Criar conta bancária

✔ Depositar dinheiro

✔ Consultar saldo

⸻

🚫 3. Fora de Escopo

❌ Não terá aplicativo para celular

❌ Não terá cartão de crédito

❌ Não terá sistema de empréstimos

❌ Não terá interface gráfica

⸻

⚙️ 4. Arquitetura e Lógica

Variáveis:

* nome_usuario (String)
* saldo (Float)
* valor_deposito (Float)
* valor_saque (Float)

Condicionais (If/Else):

* Se o saque for maior que o saldo → mostrar erro
* Se o valor do depósito for inválido → mostrar erro
* Se a conta não existir → avisar o usuário

Loops (While/For):

* O menu principal ficará repetindo até o usuário escolher sair
* Permitir várias operações seguidas no sistema
