# 📌 Projeto de Testes QA - SwagLabs

## 📖 Sobre o projeto
Este repositório contém o planejamento, a documentação e a execução de testes manuais realizados no site SwagLabs, uma plataforma de e-commerce focada em produtos personalizados.
O objetivo do projeto é simular um ambiente real de garantia de qualidade (QA), aplicando técnicas de testes para validar funcionalidades e identificar falhas no sistema.

---

## 🎯 Objetivo
Garantir a qualidade do sistema por meio da validação das principais funcionalidades do site, incluindo navegação, comportamento do carrinho e integridade dos dados inseridos em formulários.

---

## 🧪 Escopo dos testes
Os testes contemplam os seguintes fluxos:
* Navegação entre páginas
* Visualização de produtos
* Carrinho de compras
* Preenchimento e envio de formulário (enquiry)
* Validação de campos (nome, email, telefone e mensagem)

---

## 🧪 Tipos de testes aplicados
* Testes funcionais
* Testes exploratórios
* Testes positivos e negativos
* Testes de validação de dados

---

## ❌ Fora de escopo
* Testes de performance
* Testes de carga
* Testes de segurança
* Testes automatizados (fase futura)

---

## 🛠 Abordagem de testes
* Testes manuais baseados em casos de teste estruturados
* Execução prática com coleta de evidências (prints e vídeos)
* Análise exploratória para identificação de falhas não previstas

---

## 🐞 Principais achados
Durante a execução dos testes, foram identificados alguns problemas, como:
* Inconsistência na renderização do carrinho vazio
* Falha de validação no campo de nome (aceita valores numéricos)

Todos os defeitos estão documentados em:
```bash
/documentos/relatorio-de-bugs.md
```

---

## 🤖 Automação de testes
A automação será implementada futuramente utilizando ferramentas como Cypress ou Playwright, com foco nos fluxos críticos da aplicação.

---

## 📂 Estrutura do repositório
* `/documentos` → Plano de testes, casos de teste e relatório de bugs
* `/evidencias` → Capturas de tela e vídeos dos testes executados
* `/automacao` → Scripts de automação (em desenvolvimento)

---

## 📊 Status do projeto
✔ Planejamento concluído
✔ Casos de teste executados
✔ Bugs documentados
🚧 Automação em desenvolvimento

---

## 📌 Conclusão
O projeto permitiu aplicar na prática conceitos fundamentais de QA, como criação de cenários, execução de testes, validação de dados e identificação de falhas, simulando um ambiente real de testes em uma aplicação web.

---

## 👤 Autor
Nicolas Oliveira
