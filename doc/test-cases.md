# Casos de Teste (Test Cases) - SauceDemo

## CT-01: O usuário consegue realizar o cadastro com sucesso 
**Objetivo:** Verificar se um usuário válido consegue ser cadastrado na área Sign up.
- **Pré-condição:** Estar na página inicial "https://sauce-demo.myshopify.com".
- **Passos:**
  1. Acessar o link "Sign up" no menu inicial.
  2. Completar o campo "First Name".
  3. Completar o campo "Last Name".
  4. Completar o campo "Email Adress" (Ex: Email Adress: teste@email.com).
  5. Completar o campo "Password"(Ex: Password: 1234!).
  6. Clicar no botão [Create].
- **Resultado Esperado:** O usuário deve ser redirecionado para a home page.

---

## CT-02: O usuário consegue adicionar um item ao My Cart 
**Objetivo:** Verificar se um usuário válido consegue adicionar um item ao My Cart.
- **Pré-condição:** Ter feito o Log in no site "https://sauce-demo.myshopify.com".
- **Passos:**
  1. Clicar em um dos itens presentes na "Home Page".
  2. Clicar no botão [ADD TO CART].
  3. Clicar no link "My Cart".
  4. Clicar no botão [CHECK OUT].
  5. Completar os campos de endereço.
  6. Completar os campos de pagamento.
  7. Clicar no botão [Pay now].
- **Resultado Esperado:** O usuário deve conseguir efetuar a compra.

---

## CT-03: O usuário consegue adicionar um item a Wish list 
**Objetivo:** Verificar se um usuário válido consegue adicionar um item a Wis list.
- **Pré-condição:** Ter feito o Log in no site "https://sauce-demo.myshopify.com".
- **Passos:**
  1. Clicar em um dos itens presentes na "Home Page".
  2. Clicar no link de adicionar a Wish list.
- **Resultado Esperado:** O usuário deve conseguir colocar o item na Wish list.

---

## CT-04: O usuário consegue indicar um amigo pelo link "Refer a friend". 
**Objetivo:** Verificar se um usuário válido consegue indicar um amigo pelo link "Refer a friend".
- **Pré-condição:** Ter feito o Log in no site "https://sauce-demo.myshopify.com".
- **Passos:**
  1. Clicar no link "Refer a friend" presente na "Home Page".
- **Resultado Esperado:** O usuário deve conseguir indicar um amigo pelo link "Refer a friend".

---
