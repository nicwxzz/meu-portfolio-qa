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
* Executar ações fora do fluxo esperado (ex: atualizar página durante checkout)

# 📋 Casos de Teste

## 🔐 CT-01: Acesso à página do produto

**Pré-condição:** Usuário com acesso à internet

**Passos:**
1. Acessar a URL da página do produto
2. Aguardar carregamento completo

**Resultado esperado:**
* A página deve carregar corretamente
* Todas as informações do produto devem ser exibidas (nome, descrição, preço)
* Imagens devem ser carregadas sem erro

**Resultado obtido:**
Passou

**Observações:**
Página carregou corretamente, todas as informações visíveis e imagens exibidas sem erro

**Evidência:**
![CT-01](../evidencias/CT-01-pagina-produto.png)

---

## 🛒 CT-02: Adicionar produto ao carrinho

**Pré-condição:** Página do produto carregada

**Passos:**
1. Clicar no botão "Add to Enquiry"
2. Observar o comportamento do sistema após a ação

**Resultado esperado:**
* O produto deve ser adicionado ao carrinho
* O ícone do carrinho deve ser atualizado (quantidade)
* O sistema deve apresentar feedback visual da ação (ex: mensagem ou mudança no botão)

**Resultado obtido:**
Passou

**Observações:**
O produto foi adicionado ao carrinho com sucesso. O ícone do carrinho foi atualizado corretamente e houve feedback visual da ação.

**Evidência:**
![CT-01](../evidencias/CT-02-adicionar-carrinho.png)

---

## 🛒 CT-03: Acessar o carrinho

**Pré-condição:** Produto adicionado ao carrinho

**Passos:**
1. Clicar no ícone do carrinho
2. Acessar a página do carrinho

**Resultado esperado:**
* O usuário deve ser redirecionado para a página do carrinho
* O produto adicionado deve estar listado no carrinho
* As informações do produto devem estar corretas (nome, quantidade)

**Resultado obtido:**
Passou

**Observações:**
O carrinho foi acessado com sucesso. O produto adicionado foi exibido corretamente, com nome e quantidade conforme esperado.

**Evidência:**
![CT-03](../evidencias/CT-03-acesso-carrinho.png)
