# Casos de Teste - Carrinho de Compras e Checkout

## 📌 Descrição
Este documento apresenta os casos de teste para as funcionalidades de **Carrinho de Compras** e **Checkout** no e-commerce fictício.

---

## 🛒 Carrinho de Compras

## 📌 Caso 1

ID: CARRINHO-1

Caso de Teste: Adicionar produto ao carrinho

Pré-condição: Usuário logado ou não logado

Passos:

1. Acessar página de um produto  
2. Clicar em "Adicionar ao carrinho"

Resultado Esperado: Produto adicionado ao carrinho com sucesso

---

## 📌 Caso 2

ID: CARRINHO-2

Caso de Teste: Remover produto do carrinho

Pré-condição: Carrinho com pelo menos um produto

Passos:

1. Acessar o carrinho  
2. Clicar em "Remover" no produto desejado

Resultado Esperado: Produto removido do carrinho com sucesso

---

## 📌 Caso 3

ID: CARRINHO-3

Caso de Teste: Alterar quantidade de produto no carrinho

Pré-condição: Carrinho com pelo menos um produto

Passos:

1. Acessar o carrinho  
2. Alterar a quantidade do produto para um valor válido  
3. Confirmar alteração

Resultado Esperado: Quantidade atualizada e total recalculado corretamente

---

## 📌 Caso 4

ID: CARRINHO-4

Caso de Teste: Visualizar valor total do carrinho

Pré-condição: Carrinho com produtos adicionados

Passos:

1. Acessar o carrinho

Resultado Esperado: Exibir valor total correto baseado na quantidade e preço dos produtos

---

## 💳 Checkout

## 📌 Caso 1

ID: CHECKOUT-1

Caso de Teste: Finalizar compra com dados válidos

Pré-condição: Carrinho com produtos e usuário logado

Passos:

1. Acessar o carrinho  
2. Clicar em "Finalizar compra"  
3. Preencher dados de pagamento e entrega corretamente  
4. Confirmar pedido

Resultado Esperado: Pedido finalizado com sucesso e exibição de confirmação de compra

---

## 📌 Caso 2

ID: CHECKOUT-2

Caso de Teste: Finalizar compra sem dados de entrega

Pré-condição: Carrinho com produtos e usuário logado

Passos:

1. Acessar o carrinho  
2. Clicar em "Finalizar compra"  
3. Deixar dados de entrega em branco  
4. Confirmar pedido

Resultado Esperado: Exibir mensagem de erro "Dados de entrega obrigatórios"

---

## 📌 Caso 3

ID: CHECKOUT-3

Caso de Teste: Finalizar compra com pagamento recusado

Pré-condição: Carrinho com produtos e usuário logado

Passos:

1. Acessar o carrinho  
2. Clicar em "Finalizar compra"  
3. Informar dados de cartão inválidos  
4. Confirmar pedido

Resultado Esperado: Exibir mensagem de erro "Pagamento não autorizado"

---

## 📌 Caso 4

ID: CHECKOUT-4

Caso de Teste: Finalizar compra sem estar logado

Pré-condição: Carrinho com produtos

Passos:

1. Acessar o carrinho  
2. Clicar em "Finalizar compra"

Resultado Esperado: Usuário é redirecionado para a página de login ou cadastro antes de prosseguir

---
