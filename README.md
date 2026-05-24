# Entrega Técnica – Projetos de Automação de Testes

## Índice

- [Objetivo](#objetivo)

- [1. Projeto de Automação E2E com Playwright](#1-projeto-de-automação-e2e-com-playwright)
  - [Projeto](#projeto)
  - [Link do Projeto](#link-do-projeto)
  - [Objetivo do Projeto](#objetivo-do-projeto)
  - [O que foi implementado](#o-que-foi-implementado)
    - [Automação de Login](#-automação-de-login)
    - [Fluxo Completo de Checkout](#-fluxo-completo-de-checkout)
    - [Cenários Negativos](#-cenários-negativos)
    - [Estrutura e Boas Práticas](#-estrutura-e-boas-práticas)
    - [Relatórios e Evidências](#-relatórios-e-evidências)
  - [Requisitos da Avaliação Contemplados](#requisitos-da-avaliação-contemplados)

- [2. Projeto de Automação de APIs com Rest Assured](#2-projeto-de-automação-de-apis-com-rest-assured)
  - [Projeto](#projeto-1)
  - [Link do Projeto](#link-do-projeto-1)
  - [Objetivo do Projeto](#objetivo-do-projeto-1)
  - [O que foi implementado](#o-que-foi-implementado-1)
    - [Automação de Endpoints REST](#-automação-de-endpoints-rest)
    - [Validações de API](#-validações-de-api)
    - [Cenários Positivos](#-cenários-positivos)
    - [Cenários Negativos](#-cenários-negativos-1)
    - [Estrutura e Boas Práticas](#-estrutura-e-boas-práticas-1)
    - [Relatórios Automatizados](#-relatórios-automatizados)
    - [CI/CD](#-cicd)
  - [Requisitos da Avaliação Contemplados](#requisitos-da-avaliação-contemplados-1)

- [3. Projeto de Testes de Performance com K6](#3-projeto-de-testes-de-performance-com-k6)
  - [Projeto](#projeto-2)
  - [Link do Projeto](#link-do-projeto-2)
  - [Objetivo do Projeto](#objetivo-do-projeto-2)
  - [O que foi implementado](#o-que-foi-implementado-2)
    - [Testes de Carga](#-testes-de-carga)
    - [Métricas Monitoradas](#-métricas-monitoradas)
    - [Relatórios de Performance](#-relatórios-de-performance)
    - [Estrutura do Projeto](#-estrutura-do-projeto)
  - [Requisitos da Avaliação Contemplados](#requisitos-da-avaliação-contemplados-2)

- [Resumo Geral da Entrega](#resumo-geral-da-entrega)

- [Considerações Finais](#considerações-finais)

---

# Objetivo

Este documento apresenta os projetos desenvolvidos para atender aos requisitos da avaliação técnica de Automação de Testes, detalhando o que foi implementado em cada repositório, tecnologias utilizadas e quais requisitos da descrição foram contemplados.

---

# 1. Projeto de Automação E2E com Playwright

## Projeto
Playwright E-commerce OWASP Outsera E2E

## Link do Projeto
https://github.com/pimentelqe/Playwright_e-comerceOWASP_outsera_e2e

---

## Objetivo do Projeto

Automatizar fluxos End-to-End (E2E) de um e-commerce utilizando Playwright, cobrindo cenários positivos e negativos relacionados a autenticação, navegação, checkout e validações de comportamento da aplicação.

---

## O que foi implementado

### ✔ Automação de Login

Foram implementados testes automatizados contemplando:

- Login com usuário válido
- Login com senha inválida
- Login com usuário inexistente
- Validação de mensagens de erro
- Validação de campos obrigatórios

---

### ✔ Fluxo Completo de Checkout

Foi implementado um fluxo completo de compra contemplando:

- Adição de produtos ao carrinho
- Navegação entre páginas
- Preenchimento de formulários
- Finalização de compra
- Validação de sucesso da compra

---

### ✔ Cenários Negativos

Foram implementados cenários de falha esperada, incluindo:

- Dados inválidos
- Campos obrigatórios não preenchidos
- Fluxos com erro de autenticação
- Validações de mensagens de erro

---

### ✔ Estrutura e Boas Práticas

O projeto foi estruturado utilizando:

- Page Object Model (POM)
- Reutilização de componentes
- Separação de responsabilidades
- Estrutura escalável
- Testes organizados por funcionalidades

---

### ✔ Relatórios e Evidências

Foram configurados:

- Relatórios HTML do Playwright
- Captura de screenshots
- Logs de execução
- Evidências automáticas em falhas

---

## Requisitos da Avaliação Contemplados

### 2. Testes End-to-End (E2E)

✔ Login automatizado  
✔ Fluxos positivos e negativos  
✔ Navegação entre páginas  
✔ Checkout automatizado  
✔ Page Object Pattern  
✔ Relatórios completos  
✔ Evidências de falha  

---

# 2. Projeto de Automação de APIs com Rest Assured

## Projeto
Rest Assured Outsera API

## Link do Projeto
https://github.com/pimentelqe/restassured_outsera_api

---

## Objetivo do Projeto

Automatizar testes de APIs REST utilizando Rest Assured, validando múltiplos endpoints, métodos HTTP, cenários positivos e negativos e geração de relatórios automatizados.

---

## O que foi implementado

### ✔ Automação de Endpoints REST

Foram implementados testes automatizados para:

- GET
- POST
- PUT
- DELETE

---

### ✔ Validações de API

Os testes realizam validações de:

- Status codes
- Headers
- Corpo da resposta
- Estrutura da resposta
- Mensagens de erro

---

### ✔ Cenários Positivos

Foram implementados testes com:

- Payloads válidos
- Fluxos esperados
- Respostas de sucesso

---

### ✔ Cenários Negativos

Foram implementados testes contemplando:

- Payload inválido
- Campos obrigatórios ausentes
- Métodos inválidos
- Erros esperados
- Autenticação inválida

---

### ✔ Estrutura e Boas Práticas

O projeto foi estruturado utilizando:

- Organização em camadas
- Reutilização de requests
- Padronização de cenários
- Facilidade de manutenção
- Estrutura escalável

---

### ✔ Relatórios Automatizados

Foram configurados:

- Relatórios automáticos
- Logs detalhados
- Evidências de execução
- Resultados dos testes

---

### ✔ CI/CD

Integração com pipeline automatizado para:

- Execução contínua
- Execução automática após commits
- Integração em GitHub Actions

---

## Requisitos da Avaliação Contemplados

### 1. Testes Automatizados de API

✔ Testes automatizados de endpoints  
✔ Métodos GET/POST/PUT/DELETE  
✔ Testes positivos  
✔ Testes negativos  
✔ Validação de status codes  
✔ Validação de headers  
✔ Validação de body response  
✔ Relatórios automatizados  
✔ Integração CI/CD

---

# 3. Projeto de Testes de Performance com K6

## Projeto
K6 E-commerce Outsera

## Link do Projeto
https://github.com/pimentelqe/K6_e-comenrce_outsera

---

## Objetivo do Projeto

Realizar testes de carga e performance utilizando K6, simulando múltiplos usuários simultâneos e analisando o comportamento da aplicação sob carga.

---

## O que foi implementado

### ✔ Testes de Carga

Foram desenvolvidos scripts utilizando K6 para:

- Simulação de usuários simultâneos
- Execução contínua de carga
- Avaliação de estabilidade da aplicação
- Monitoramento de resposta da API

---

### ✔ Métricas Monitoradas

Foram analisadas métricas como:

- Tempo de resposta
- Throughput
- Requisições por segundo
- Tempo médio de execução
- Taxa de erro

---

### ✔ Relatórios de Performance

Foram gerados relatórios contendo:

- Resultado das execuções
- Métricas de performance
- Identificação de gargalos
- Análise de comportamento sob carga

---

### ✔ Estrutura do Projeto

O projeto foi estruturado para permitir:

- Fácil manutenção
- Escalabilidade de cenários
- Integração em pipelines CI/CD
- Reutilização de scripts

---

## Requisitos da Avaliação Contemplados

### 4. Testes Automatizados de Carga

✔ Testes com K6  
✔ Simulação de múltiplos usuários  
✔ Análise de métricas  
✔ Relatórios de performance  
✔ Identificação de gargalos

---

# Resumo Geral da Entrega

| Projeto | Objetivo Principal | Tecnologias |
|---|---|---|
| Playwright_e-comerceOWASP_outsera_e2e | Automação E2E | Playwright, JavaScript/TypeScript |
| K6_e-comenrce_outsera | Performance e carga | K6 |
| restassured_outsera_api | Automação de APIs | Java, Rest Assured |

---

# Considerações Finais

Os projetos apresentados demonstram experiência prática em:

- Automação de testes E2E
- Automação de APIs REST
- Testes de carga e performance
- Integração contínua
- Estruturação de projetos de automação
- Uso de boas práticas de desenvolvimento e testes

Além disso, os projetos foram organizados de forma modular e escalável, permitindo manutenção simples, evolução contínua e integração com pipelines CI/CD.
