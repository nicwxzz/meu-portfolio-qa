# 🧪 Cenários de Teste

## 🔹 Página do Produto

* Validar carregamento da página do produto
* Validar exibição correta das informações (nome, descrição, preço)
* Validar imagens do produto
* Validar responsividade básica da página

## 🔹 Personalização do Produto

* Inserir texto válido no campo de personalização
* Tentar prosseguir sem preencher campos obrigatórios
* Inserir caracteres especiais
* Inserir texto muito longo (limite)

## 🔹 Carrinho

* Adicionar produto ao carrinho
* Adicionar produto sem personalização (quando obrigatório)
* Alterar quantidade do produto
* Remover produto do carrinho

## 🔹 Fluxo de Compra

* Iniciar checkout com produto no carrinho
* Preencher dados obrigatórios corretamente
* Tentar avançar com campos vazios
* Validar continuidade do fluxo até finalização

## 🔹 Cenários Negativos

* Submeter formulário com dados inválidos
* Interromper fluxo no meio do checkout
* Validar comportamento em ações inesperadas



# 📋 Casos de Teste

## 🔐 CT-01: Acesso à página do produto

**Pré-condição:** Usuário com acesso à internet

**Passos:**

1. Acessar a URL da página do produto
2. Aguardar carregamento completo

**Resultado esperado:**
A página deve carregar corretamente exibindo todas as informações do produto

---

## 📝 CT-02: Inserir personalização válida

**Pré-condição:** Página do produto carregada

**Passos:**

1. Inserir texto válido no campo de personalização
2. Verificar se o campo aceita o conteúdo

**Resultado esperado:**
O sistema deve aceitar o texto sem apresentar erros

---

## ❌ CT-03: Tentar prosseguir sem preencher personalização obrigatória

**Pré-condição:** Campo de personalização obrigatório

**Passos:**

1. Não preencher o campo
2. Tentar adicionar ao carrinho

**Resultado esperado:**
O sistema deve exibir mensagem de erro e impedir a ação

---

## 🛒 CT-04: Adicionar produto ao carrinho

**Pré-condição:** Produto configurado corretamente

**Passos:**

1. Clicar em "Adicionar ao carrinho"

**Resultado esperado:**
O produto deve ser adicionado ao carrinho com sucesso

---

## 🔄 CT-05: Alterar quantidade do produto

**Pré-condição:** Produto no carrinho

**Passos:**

1. Acessar carrinho
2. Alterar quantidade do item

**Resultado esperado:**
A quantidade deve ser atualizada corretamente

---

## 🗑️ CT-06: Remover produto do carrinho

**Pré-condição:** Produto no carrinho

**Passos:**

1. Clicar em remover item

**Resultado esperado:**
O produto deve ser removido do carrinho

---

## 💳 CT-07: Iniciar checkout

**Pré-condição:** Produto no carrinho

**Passos:**

1. Clicar em finalizar compra

**Resultado esperado:**
Usuário deve ser direcionado para a página de checkout

---

## ⚠️ CT-08: Validar campos obrigatórios no checkout

**Pré-condição:** Página de checkout aberta

**Passos:**

1. Deixar campos obrigatórios vazios
2. Tentar avançar

**Resultado esperado:**
O sistema deve exibir mensagens de validação

---

## ✅ CT-09: Finalizar compra com sucesso

**Pré-condição:** Dados válidos preenchidos

**Passos:**

1. Preencher todos os campos obrigatórios
2. Confirmar compra

**Resultado esperado:**
A compra deve ser concluída com sucesso

---

## 🚫 CT-10: Inserir dados inválidos no checkout

**Pré-condição:** Página de checkout aberta

**Passos:**

1. Inserir dados inválidos (ex: email incorreto)
2. Tentar continuar

**Resultado esperado:**
O sistema deve bloquear o avanço e exibir erro
