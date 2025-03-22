# Bugs Reportados - E-commerce

## 📌 Descrição
Este documento apresenta o registro de bugs encontrados durante os testes do sistema de e-commerce fictício.

---

## 🐞 Bug 1

ID: BUG-001

Título: Carrinho não atualiza valor total após alteração de quantidade

Severidade: Alta

Status: Aberto

Descrição: Ao alterar a quantidade de um produto no carrinho, o valor total exibido não é atualizado automaticamente.

Passos para reproduzir:
1. Acessar o carrinho com um produto adicionado  
2. Alterar a quantidade do produto  
3. Verificar o valor total

Resultado Esperado: O valor total do carrinho deve ser recalculado e atualizado automaticamente após a alteração da quantidade.

---

## 🐞 Bug 2

ID: BUG-002

Título: Formulário de cadastro permite envio com campos em branco

Severidade: Média

Status: Aberto

Descrição: O sistema permite que o usuário envie o formulário de cadastro mesmo com campos obrigatórios em branco.

Passos para reproduzir:
1. Acessar página de cadastro  
2. Deixar campos obrigatórios em branco  
3. Clicar em "Cadastrar"

Resultado Esperado: O sistema deve bloquear o envio do formulário e exibir mensagens de erro para os campos obrigatórios.

---

## 🐞 Bug 3

ID: BUG-003

Título: Mensagem de erro de login aparece cortada em telas pequenas

Severidade: Baixa

Status: Aberto

Descrição: A mensagem de erro "E-mail ou senha inválidos" no login aparece cortada em dispositivos com resolução menor que 400px.

Passos para reproduzir:
1. Acessar página de login em um dispositivo com resolução pequena  
2. Informar dados inválidos e clicar em "Entrar"  
3. Observar a mensagem de erro exibida

Resultado Esperado: A mensagem de erro deve se ajustar corretamente à tela, sendo exibida de forma completa.

---

## 🐞 Bug 4

ID: BUG-004

Título: Checkout permite finalizar compra sem selecionar método de pagamento

Severidade: Alta

Status: Aberto

Descrição: O sistema permite concluir a compra sem que o usuário selecione um método de pagamento.

Passos para reproduzir:
1. Acessar o carrinho com produtos adicionados  
2. Ir para o checkout  
3. Preencher dados de entrega  
4. Não selecionar método de pagamento  
5. Confirmar pedido

Resultado Esperado: O sistema deve exigir a seleção de um método de pagamento antes de finalizar a compra.

---
