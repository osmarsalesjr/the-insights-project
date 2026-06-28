Crie uma base Airtable para gestão visual de riscos de um produto SaaS com IA Generativa.

Objetivo: representar uma Matriz de Riscos visual, profissional e adequada para Product Management.

Crie 1 tabela principal chamada: Matriz de Riscos

Campos:

* ID (text)
* Risco (long text)
* Categoria (single select): Técnico, IA/ML, Segurança, Operacional, Negócio, Dados
* Probabilidade (single select): Baixa, Média, Alta
* Impacto (single select): Baixo, Médio, Alto, Crítico
* Plano de Mitigação (long text)
* Responsável (single line text)
* Status (single select): Monitorando, Mitigando, Resolvido
* Criticidade (single select): Baixa, Média, Alta, Crítica

Configure cores nos Single Select:

Probabilidade:

* Baixa = Verde
* Média = Amarelo
* Alta = Vermelho

Impacto / Criticidade:

* Baixo = Verde
* Médio = Amarelo
* Alto = Laranja
* Crítico / Crítica = Vermelho escuro

Status:

* Monitorando = Azul
* Mitigando = Laranja
* Resolvido = Verde

Popule com os registros:

RSK-01 | Baixa qualidade dos dados | Dados | Alta | Alto | Pipeline de validação e limpeza | Engenharia de Dados | Monitorando | Alta
RSK-02 | Classificação incorreta da IA | IA/ML | Média | Alto | Calibrar modelo | Time IA | Monitorando | Alta
RSK-03 | Alucinação da IA | IA/ML | Média | Alto | Human-in-the-loop | Time IA | Monitorando | Alta
RSK-04 | Vazamento de dados sensíveis | Segurança | Baixa | Crítico | Criptografia e controle de acesso | Segurança da Informação | Monitorando | Crítica
RSK-05 | Alto custo de inferência | Técnico | Média | Alto | Cache e otimização | Engenharia de Plataforma | Monitorando | Alta
RSK-06 | Resistência de adoção | Negócio | Média | Médio | Treinamento | Product Manager | Monitorando | Média
RSK-07 | Indisponibilidade da infraestrutura | Operacional | Baixa | Alto | Redundância | DevOps | Monitorando | Alta
RSK-08 | Drift de modelo | IA/ML | Média | Alto | Re-treinamento periódico | Time IA | Monitorando | Alta
RSK-09 | Falha em integração CRM | Técnico | Média | Médio | Testes de integração | Backend | Monitorando | Média
RSK-10 | Baixa escalabilidade | Técnico | Média | Alto | Arquitetura escalável | Arquitetura de Software | Monitorando | Alta

Crie views:

1. Todos os Riscos
2. Riscos Críticos
3. Agrupado por Categoria
4. Kanban por Status
5. Heatmap agrupado por Impacto e Probabilidade

Crie também uma Interface / Dashboard executiva com:

* Card mostrando total de riscos
* Card mostrando riscos críticos
* Gráfico por categoria
* Gráfico por criticidade
* Heatmap visual de risco

Use layout limpo, moderno e altamente visual, adequado para screenshots executivos.
