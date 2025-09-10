# TripleTen_Analyst_QA_Sprint_03_Teste_de_aplicativos_Web

# 📌 Sprint 03 - Curso de QA - Roberth Guimaro

Este repositório contém os materiais da **Sprint 03** do Curso de Quality Assurance (QA), com foco em **testes de aplicativos web**, desde fundamentos técnicos até a aplicação prática em um projeto real.  

---

## 🎯 Objetivo da Sprint  
Capacitar a compreenção a arquitetura de aplicações web, realizar testes de interface e compatibilidade, aplicar técnicas avançadas de teste e validar projetos em cenários reais.  

---

## 📚 Conteúdo Abordado  

### Fundamentos de Aplicativos Web  
- Arquitetura **cliente-servidor** (front-end vs back-end).  
- Protocolos **HTTP** e **HTTPS**.  
- Uso das **ferramentas DevTools** do navegador.  
- Mecanismos de armazenamento: **cookies**, **cache** e **local storage**.  

### Teste de Interface de Usuário  
- Identificação e validação de elementos (botões, links, formulários, inputs).  
- Uso do **Figma** para comparar design vs implementação.  
- Testes **visuais** (layout) e **funcionais**.  

### Testes Multiplataforma  
- Diferenças entre **desktop vs mobile** e sistemas operacionais.  
- Criação de **matrizes de compatibilidade**.  
- Estratégias para otimizar cobertura de testes.  

### Design Web Responsivo  
- Diferença entre **design adaptável** e **responsivo**.  
- Técnicas de teste usando **DevTools** e **dispositivos reais**.  
- Seleção de resoluções apropriadas para validação.  

### Técnicas Avançadas  
- **Tabelas de decisão** para cenários complexos.  
- **Pairwise Testing** para reduzir combinações de entrada.  
- Revisão de **particionamento de equivalência** e **análise de valores-limite**.  

---

## 🧪 Projeto Prático  
Durante esta sprint, foi realizado o **teste completo da funcionalidade de compartilhamento de carros do Urban Routes**, aplicando todos os conceitos estudados em um **cenário real de QA**.  

---

## Estrutura do Repositório

/
├── 01 - Checklist do layout/
│   └── Checklist_e_testes_layout.xlsx ← Casos de teste e checklist aplicados ao layout
│
├── 02 - Checklist método de pagamento/
│   ├── Adicionar_cartão_conjunto_valor_intervalo.xlsx ← Casos de teste para valores/intervalos de cartões
│   └── Checklist_e_testes_metodo_de_pagamento.xlsx ← Checklist e casos de teste do método de pagamento
│
├── 03 - Casos de teste para o botão RESERVAR/
│   ├── Botao_reservar_conjunto_valor_intervalo.xlsx ← Casos de teste para intervalos de valores
│   └── Casos_de_testes_botao_reservar.xlsx ← Casos de teste detalhados para o botão RESERVAR
│
├── 04 - Casos de teste para locação/
│   └── Casos_de_testes_locação.xlsx ← Casos de teste para funcionalidade de locação
│
├── Design_carsharing_link.txt ← Link para referência de design
├── Requisitos_carsharing_link.txt ← Link para os requisitos
├── Tabela_de_decisao_carsharing.xlsx ← Tabelas de decisão aplicadas ao carsharing
│
└── README.md ← Documentação atual

## Como usar

1. Navegue pela pasta correspondente ao tópico que deseja analisar:
   - `01 - Checklist do layout/` → abra `Checklist_e_testes_layout.xlsx` para ver os checklists e casos de teste visuais.
   - `02 - Checklist método de pagamento/` → abra as planilhas `Adicionar_cartão_conjunto_valor_intervalo.xlsx` e `Checklist_e_testes_metodo_de_pagamento.xlsx`.
   - `03 - Casos de teste para o botão RESERVAR/` → abra `Botao_reservar_conjunto_valor_intervalo.xlsx` e `Casos_de_testes_botao_reservar.xlsx`.
   - `04 - Casos de teste para locação/` → abra `Casos_de_testes_locação.xlsx`.

2. Verificando e filtrando casos de teste (guia geral):
   - Procure colunas típicas: `ID`, `Título`/`Descrição`, `Pré-condições`, `Passos`, `Resultado esperado`, `Status`.
   - Use filtros (por `Status` ou `ID`) para acompanhar execução e pendências.
   - Ao reportar um bug, relacione sempre o `Test Case ID` com o `Bug ID`.

3. Evidências e relatórios:
   - Toda evidência deve ficar na coluna `link para relatório`, onde será direcionado ao `Jira`, onde estará todas as evidências do `bug` relacionado.

4. Uso dos links de design e requisitos:
   - `Design_carsharing_link.txt` → abra o link para comparar o Figma/design com a implementação.
   - `Requisitos_carsharing_link.txt` → abra o link para revisar requisitos que devem ser cobertos pelos testes.
   - Sempre valide que cada requisito possui pelo menos 1 caso de teste associado (rastreabilidade).

5. Tabela de decisão e mapeamento:
   - Abra `Tabela_de_decisao_carsharing.xlsx` para ver combinações/decisões aplicadas.
