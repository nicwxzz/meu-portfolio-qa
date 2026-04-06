# 📄 Plano de Testes

## 1. Objetivo

Validar o funcionamento da página de produto e do fluxo de compra de um item personalizado (Custom Greeting Card), garantindo que o usuário consiga visualizar, configurar e solicitar o produto corretamente.

---

## 2. Escopo

Serão testadas as seguintes funcionalidades:

### 🔹 Página do Produto

* Carregamento da página
* Exibição de informações do produto
* Exibição de preço
* Interação com opções de personalização (se aplicável)

### 🔹 Personalização do Produto

* Inserção de dados personalizados (texto, campos, etc)
* Validação de campos obrigatórios
* Comportamento ao inserir dados inválidos

### 🔹 Carrinho

* Adição do produto ao carrinho
* Atualização de quantidade
* Remoção do produto

### 🔹 Fluxo de Compra

* Início do processo de checkout
* Preenchimento de dados do usuário
* Continuidade do fluxo até finalização

---

## 3. Fora de escopo

Não serão contemplados neste projeto:

* Testes de performance
* Testes de carga
* Testes de segurança
* Integrações externas (pagamento real, envio logístico)

---

## 4. Estratégia de Testes

A abordagem adotada será:

* Testes manuais baseados em cenários e casos de teste
* Testes exploratórios focados na experiência do usuário
* Validação de fluxos críticos (happy path e cenários negativos)

---

## 5. Ambiente de Testes

* Aplicação web acessada via navegador
* Navegador principal: Google Chrome
* Dispositivo: Desktop

---

## 6. Critérios de entrada

* Sistema acessível
* Página de produto disponível
* Funcionalidade de carrinho operacional

---

## 7. Critérios de saída

* Execução completa dos casos de teste planejados
* Registro e documentação dos bugs encontrados
* Evidências coletadas (prints)

---

## 8. Riscos

* Instabilidade da aplicação durante os testes
* Mudanças na interface do site
* Funcionalidades limitadas por se tratar de ambiente externo ([Swag Labs][1])

---

## 9. Entregáveis

* Plano de testes
* Casos de teste
* Relatório de bugs
* Evidências dos testes

---

## 10. Fluxo crítico do sistema

O principal fluxo validado será:

1. Acessar página do produto
2. Personalizar o produto (quando aplicável)
3. Adicionar ao carrinho
4. Iniciar processo de compra

Esse fluxo é essencial pois a plataforma tem como objetivo facilitar a seleção, personalização e pedido de produtos personalizados de forma simples ([Swag Labs][1])

[1]: https://swaglabs.in/?utm_source=chatgpt.com "Swag Labs - Quality Corporate Merchandise"
