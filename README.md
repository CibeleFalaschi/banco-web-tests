# Projeto de Testes Automatizados - Banco Web

## 🎯 Objetivo

Este repositório contém automações de testes da aplicação **Banco Web** desenvolvidas durante a Mentoria 2.0 do Julio de Lima. O propósito é demonstrar como estruturar e executar validações utilizando **Cypress** com JavaScript, adotando comandos customizados, geração de relatórios e organização de cenário de teste.

## 🧩 Componentes do Projeto

- **Cypress**: framework principal de automação de interface.
- **Mocha e Mochawesome**: utilizados para geração de relatórios (via `cypress-mochawesome-reporter`).
- **Custom commands**: abstrações em `cypress/support/commands` para ações recorrentes (`login`, `transferências`, etc.).
- **Fixtures**: dados de teste (e.g., credenciais) em `cypress/fixtures`.
- **Tests (e2e)**: especificações de cenários em `cypress/e2e` (`login.cy.js`, `transferencias.cy.js`).
-
> As aplicações **API** e **Web** devem estar em execução para os testes funcionarem.

- **e2e/**: contém os arquivos de especificação de cenários reais. Cada `.cy.js` corresponde a um fluxo testado.
- **fixtures/**: armazena dados estáticos consumidos pelos testes, reduzindo duplicação e facilitando manutenção.
- **support/commands/**: comandos reutilizáveis que encapsulam ações repetitivas (e.g., executar login, navegar até página de transferências).
- **reports/**: saída de relatórios HTML e recursos estáticos gerados ao final dos testes.
- **screenshots/ videos/**: capturas de tela e gravações de execução, feitas automaticamente pelo Cypress em caso de falhas ou quando configurado.



