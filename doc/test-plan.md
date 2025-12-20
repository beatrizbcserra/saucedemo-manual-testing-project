# 📋 Plano de Teste: SauceDemo E-commerce

---

## 1. Introdução
Este documento descreve a estratégia de teste para a aplicação SauceDemo. O objetivo é garantir que as funcionalidades
principais de login, navegação e compra estejam operando conforme o esperado, garantindo uma experiência de usuário sem falhas.

---

## 2. Escopo dos Testes

### 2.1. Funcionalidades Inclusas:
- **Autenticação:** Login com diferentes perfis de usuário (sucesso, bloqueado, erro).
- **Inventário:** Visualização de produtos, detalhes e filtros.
- **Carrinho:** Adição, remoção e persistência de itens.
- **Checkout:** Fluxo completo de inserção de dados e finalização de pedido.

### 2.2. Funcionalidades Fora de Escopo:
- Testes de Performance e Carga.
- Testes de Segurança (Penetration Testing).
- Integrações de pagamento reais (o site usa apenas simulação).

---

## 3. Estratégia de Teste
Os testes serão executados inicialmente de forma **Manual**, seguindo a técnica de **Testes de Caixa Preta** (Black Box Testing). 

**Níveis de Teste:**
- Teste de Sistema (Funcional).
- Teste de Regressão (após futuras automações).

---

## 4. Ambiente de Teste
- **Dispositivo:** Notebook (Windows)
- **Navegadores:** Firefox (146.0 (64-bits)).
- **URL:** https://sauce-demo.myshopify.com/

---

## 5. Critérios de Aceite e Passagem
- 100% dos Casos de Teste críticos devem passar.
- Nenhum bug de severidade "Crítica" ou "Alta" deve estar aberto no momento da entrega.
- O fluxo de checkout deve ser concluído sem erros de script na console.

---

## 6. Ferramentas
- **GitHub Issues:** Para reporte e rastreio de defeitos.
- **Markdown:** Para documentação técnica.

---
**Data de Criação:** Dezembro de 2025
**Responsável:** Beatriz Serra
