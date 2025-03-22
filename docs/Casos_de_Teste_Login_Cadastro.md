# Casos de Teste - Login e Cadastro de Usuário

## Descrição
Este documento apresenta os casos de teste para as funcionalidades de **Login** e **Cadastro de Usuário** no e-commerce fictício.

---

## 🔐 Login

## 📌 Caso 1

ID: USUARIO-LOGIN-1

Caso de Teste: Login com credenciais válidas

Pré-condição: Usuário cadastrado no sistema

Passos:

1. Acessar página de login  
2. Informar e-mail e senha válidos  
3. Clicar em "Entrar"

Resultado Esperado: Usuário é autenticado e redirecionado para a página inicial

---

## 📌 Caso 2

ID: USUARIO-LOGIN-2

Caso de Teste: Login com e-mail inválido

Pré-condição: -

Passos:

1. Acessar página de login  
2. Informar e-mail inválido  
3. Clicar em "Entrar"

Resultado Esperado: Exibir mensagem de erro "E-mail ou senha inválidos"

---

## 📌 Caso 3

ID: USUARIO-LOGIN-3

Caso de Teste: Login com senha incorreta

Pré-condição: Usuário cadastrado no sistema

Passos:

1. Acessar página de login  
2. Informar e-mail válido e senha incorreta  
3. Clicar em "Entrar"

Resultado Esperado: Exibir mensagem de erro "E-mail ou senha inválidos"

---

## 📌 Caso 4

ID: USUARIO-LOGIN-4

Caso de Teste: Login com campos obrigatórios em branco

Pré-condição: -

Passos:

1. Acessar página de login  
2. Deixar e-mail e senha em branco  
3. Clicar em "Entrar"

Resultado Esperado: Exibir mensagem de erro "Campos obrigatórios não preenchidos"

---

## 👤 Cadastro de Usuário

## 📌 Caso 1

ID: USUARIO-CAD-1

Caso de Teste: Cadastro com dados válidos

Pré-condição: -

Passos:

1. Acessar página de cadastro  
2. Preencher todos os campos obrigatórios corretamente  
3. Clicar em "Cadastrar"

Resultado Esperado: Usuário cadastrado com sucesso e redirecionado para página inicial

---

## 📌 Caso 2

ID: USUARIO-CAD-2

Caso de Teste: Cadastro com e-mail já existente

Pré-condição: E-mail já cadastrado no sistema

Passos:

1. Acessar página de cadastro  
2. Informar e-mail já cadastrado  
3. Clicar em "Cadastrar"

Resultado Esperado: Exibir mensagem de erro "E-mail já cadastrado"

---

## 📌 Caso 3

ID: USUARIO-CAD-3

Caso de Teste: Cadastro com senha e confirmação diferentes

Pré-condição: -

Passos:

1. Acessar página de cadastro  
2. Informar senha e confirmação de senha diferentes  
3. Clicar em "Cadastrar"

Resultado Esperado: Exibir mensagem de erro "Senhas não coincidem"

---

## 📌 Caso 4

ID: USUARIO-CAD-4

Caso de Teste: Cadastro com campos obrigatórios em branco

Pré-condição: -

Passos:

1. Acessar página de cadastro  
2. Deixar campos obrigatórios em branco  
3. Clicar em "Cadastrar"

Resultado Esperado: Exibir mensagem de erro "Campos obrigatórios não preenchidos"

---


