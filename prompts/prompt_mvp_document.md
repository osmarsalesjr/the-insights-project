Você é um Product Manager sênior especializado em Product Discovery, Product Strategy e Product Backlog Management.

Com base no contexto abaixo, crie uma base Airtable completa para documentar e visualizar o MVP de um produto digital.

# Contexto do Produto

Estamos desenvolvendo uma plataforma SaaS baseada em Inteligência Artificial Generativa para analisar grandes volumes de interações de atendimento ao cliente, incluindo:

* Tickets de suporte
* Chats
* E-mails

A solução deve transformar dados não estruturados em insights estratégicos, ajudando gestores a identificar padrões, detectar incidentes críticos e priorizar ações.

O objetivo principal do produto é:

Reduzir o tempo de análise manual e melhorar a velocidade de tomada de decisão.

---

# Objetivo da Base Airtable

Criar um artefato visual de Product Management representando o Documento de MVP do produto.

A base deve ser organizada para funcionar como um backlog priorizado de MVP.

---

# Estrutura da Base

Crie as seguintes tabelas:

## 1. Tabela Principal — Backlog do MVP

Crie os campos abaixo:

### ID

Tipo: Single line text
Exemplo:

* MVP-01
* MVP-02

### Funcionalidade

Tipo: Single line text

### Descrição

Tipo: Long text

### Prioridade

Tipo: Single select

Opções:

* Essencial
* Importante
* Desejável
* Fora do Escopo

### Justificativa de Negócio

Tipo: Long text

### Critérios de Aceitação

Tipo: Long text

### Dependências

Tipo: Linked record (auto-relacionamento com a própria tabela)

### Status

Tipo: Single select

Opções:

* Não iniciado
* Em análise
* Planejado
* Validado

### Complexidade Técnica

Tipo: Single select

Opções:

* Baixa
* Média
* Alta

### Valor de Negócio

Tipo: Single select

Opções:

* Baixo
* Médio
* Alto
* Crítico

---

# Registros Iniciais da Tabela Backlog

Popule automaticamente com os seguintes registros:

## MVP-01

Funcionalidade: Ingestão de Dados
Descrição: Importar dados via CSV ou API
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Média
Valor de Negócio: Crítico

Critérios de Aceitação:

* Sistema aceita upload CSV
* API suporta ingestão
* Processa 10000 registros por lote

---

## MVP-02

Funcionalidade: Processamento Textual
Descrição: Limpeza e normalização dos textos
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Média
Valor de Negócio: Alto

---

## MVP-03

Funcionalidade: Classificação de Temas
Descrição: Classificação automática por IA
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Alta
Valor de Negócio: Crítico

---

## MVP-04

Funcionalidade: Priorização por Criticidade
Descrição: Score baseado em urgência e impacto
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Alta
Valor de Negócio: Crítico

---

## MVP-05

Funcionalidade: Dashboard de Insights
Descrição: Painel visual de indicadores
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Média
Valor de Negócio: Alto

---

## MVP-06

Funcionalidade: Resumos Executivos
Descrição: Síntese automática de insights
Prioridade: Essencial
Status: Planejado
Complexidade Técnica: Média
Valor de Negócio: Alto

---

## MVP-07

Funcionalidade: Alertas Automatizados
Prioridade: Importante

## MVP-08

Funcionalidade: Filtros Avançados
Prioridade: Importante

## MVP-09

Funcionalidade: Histórico Comparativo
Prioridade: Importante

## MVP-10

Funcionalidade: Recomendação de Ações
Prioridade: Desejável

## MVP-11

Funcionalidade: Predição de Incidentes
Prioridade: Desejável

---

## 2. Tabela — Métricas de Validação

Criar campos:

### Métrica

### Meta

### Valor Atual

### Status

Popular com:

* Redução de tempo de análise | 50% | 0 | Não iniciado
* Taxa de adoção | 70% | 0 | Não iniciado
* Precisão da classificação | 80% | 0 | Não iniciado
* Tempo de geração de insights | < 5 minutos | N/A | Não iniciado

---

# Views necessárias

Crie as seguintes visualizações:

## View 1 — Backlog Completo

Mostrar todos os registros

## View 2 — Funcionalidades Essenciais

Filtrar:
Prioridade = Essencial

## View 3 — Priorização por Valor

Ordenar por:
Valor de Negócio DESC

## View 4 — Kanban por Status

Agrupar por:
Status

## View 5 — Roadmap Simplificado

Agrupar por:
Prioridade

---

# Requisitos Visuais

A base deve parecer um artefato real de Product Management usado por startups ou equipes de produto.

Priorize:

* Layout limpo
* Campos bem organizados
* Boa legibilidade
* Estrutura adequada para screenshots acadêmicos
* Visual profissional

Não simplifique a estrutura. Gere a base completa.
