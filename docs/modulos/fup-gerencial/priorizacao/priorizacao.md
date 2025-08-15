# Priorização de Requisitos - FUP Gerencial

## Introdução

Este documento apresenta a priorização dos requisitos elicitados para o **FUP Gerencial**, organizados por categorias de prioridade baseadas no valor de negócio, complexidade de implementação e dependências técnicas identificadas durante o processo de discovery.

## Critérios de Priorização

- **Valor de Negócio**: Impacto direto na resolução do problema principal
- **Complexidade**: Esforço técnico necessário para implementação
- **Dependências**: Requisitos que são pré-requisitos para outros
- **Risco**: Incertezas técnicas ou de adoção pelos usuários

---

## MVP (Produto Mínimo Viável)

### Funcionalidades Essenciais - Sprint 1

| **Requisito** | **Descrição**                        | **Justificativa**                                |
| ------------- | ------------------------------------ | ------------------------------------------------ |
| RF01-FUP      | Criação de novo preenchimento FUP    | Base fundamental do sistema                      |
| RF02-FUP      | Fluxo assistido com blocos temáticos | Core da experiência do usuário                   |
| RF03-FUP      | Bloco financeiro                     | Uma das dimensões principais de avaliação        |
| RF04-FUP      | Bloco de gestão de entregas          | Dimensão crítica para acompanhamento de projetos |
| RF08-FUP      | Salvamento automático                | Evita perda de dados e melhora experiência       |
| RF13-FUP      | Dashboard com indicadores de farol   | Principal valor visual da solução                |
| RF14-FUP      | Cálculo automático da cor do farol   | Automatização essencial para o dashboard         |

**Meta do MVP**: Sistema funcional com fluxo básico e visualização inicial dos resultados.

---

## Alta Prioridade - Sprint 2

| **Requisito** | **Descrição**                       | **Justificativa**                             |
| ------------- | ----------------------------------- | --------------------------------------------- |
| RF05-FUP      | Bloco de gestão da qualidade        | Completa as dimensões principais de avaliação |
| RF10-FUP      | Geração de relatório em PDF         | Entregável importante para documentação       |
| RF11-FUP      | Organização do relatório por blocos | Estruturação necessária para usabilidade      |
| RF15-FUP      | Filtro por PO no dashboard          | Funcionalidade básica de navegação            |
| RF16-FUP      | Filtro por projeto no dashboard     | Funcionalidade básica de navegação            |
| RF19-FUP      | Associação projeto/PO/data          | Metadados essenciais para organização         |

**Meta da Sprint 2**: Sistema completo com as funcionalidades principais para uso em produção.

---

## Média Prioridade - Sprint 3

| **Requisito** | **Descrição**                        | **Justificativa**                        |
| ------------- | ------------------------------------ | ---------------------------------------- |
| RF06-FUP      | Bloco de nível de qualidade          | Dimensão adicional importante            |
| RF07-FUP      | Bloco de nível tecnológico           | Completa todas as dimensões do discovery |
| RF12-FUP      | Histórico de relatórios por projeto  | Funcionalidade de valor agregado         |
| RF17-FUP      | Filtro por período/data              | Análise temporal importante              |
| RF20-FUP      | Visualização da evolução de projetos | Insights de tendência ao longo do tempo  |

**Meta da Sprint 3**: Sistema enriquecido com todas as dimensões e capacidade de análise temporal.

---

## Baixa Prioridade - Sprint 4+

| **Requisito** | **Descrição**                           | **Justificativa**                                   |
| ------------- | --------------------------------------- | --------------------------------------------------- |
| RF09-FUP      | Lógica condicional baseada em respostas | Funcionalidade avançada, não essencial inicialmente |
| RF18-FUP      | Drill-down em faróis para detalhes      | Nice-to-have para análise aprofundada               |

**Meta das Sprints 4+**: Funcionalidades avançadas para otimização da experiência do usuário.

---

## Requisitos Não Funcionais por Prioridade

### Sprint 1 (MVP)

| **Requisito** | **Descrição**                       |
| ------------- | ----------------------------------- |
| RNF01-FUP     | Interface intuitiva                 |
| RNF02-FUP     | Tempo de preenchimento < 15 minutos |
| RNF03-FUP     | Dashboard carrega em < 3 segundos   |

### Sprint 2

| **Requisito** | **Descrição**                       |
| ------------- | ----------------------------------- |
| RNF04-FUP     | Relatórios PDF em < 10 segundos     |
| RNF05-FUP     | Suporte a 100+ usuários simultâneos |
| RNF10-FUP     | Acesso baseado em perfil de usuário |

### Sprint 3+

| **Requisito** | **Descrição**                           |
| ------------- | --------------------------------------- |
| RNF06-FUP     | 99% disponibilidade                     |
| RNF07-FUP     | Backup automático diário                |
| RNF08-FUP     | Flexibilidade para modificação do fluxo |
| RNF09-FUP     | Auditoria de alterações                 |

---

## Matriz de Dependências

```
Sprint 1 (MVP)
├── RF01-FUP (base) → RF02-FUP → RF03-FUP, RF04-FUP
├── RF08-FUP (suporte ao fluxo)
└── RF13-FUP ← RF14-FUP (dashboard básico)

Sprint 2
├── RF05-FUP (completa dimensões)
├── RF10-FUP → RF11-FUP (relatórios)
├── RF15-FUP, RF16-FUP (filtros básicos)
└── RF19-FUP (metadados)

Sprint 3
├── RF06-FUP, RF07-FUP (dimensões finais)
├── RF12-FUP (histórico)
├── RF17-FUP (filtro temporal)
└── RF20-FUP (evolução temporal)

Sprint 4+
├── RF09-FUP (lógica avançada)
└── RF18-FUP (drill-down)
```

---

## Critérios de Sucesso por Sprint

### Sprint 1

- [ ] PO consegue criar e preencher um FUP básico
- [ ] Dashboard exibe faróis para projetos preenchidos
- [ ] Sistema funciona para 10 usuários simultâneos

### Sprint 2

- [ ] Todas as dimensões principais estão disponíveis
- [ ] Relatórios PDF são gerados com qualidade
- [ ] Filtros básicos funcionam corretamente

### Sprint 3

- [ ] Sistema completo com todas as dimensões
- [ ] Análise temporal está disponível
- [ ] Performance atende aos requisitos não funcionais

### Sprint 4+

- [ ] Funcionalidades avançadas implementadas
- [ ] Sistema otimizado para produção
- [ ] Métricas de adoção positivas
