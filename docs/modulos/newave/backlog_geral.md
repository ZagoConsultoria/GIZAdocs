# Backlog Geral - Módulo Newave

## Introdução

Este documento apresenta o backlog consolidado do módulo Newave, integrando os programas de **Monitoramento de Emissões Atmosféricas** e **Monitoramento de Ruídos**. O backlog foi organizado identificando requisitos similares entre programas, propondo consolidações quando possível, e priorizando funcionalidades com base no valor de negócio e dependências técnicas.

## Objetivo

Estabelecer um roadmap unificado que:

- Maximize o reuso de componentes entre programas
- Minimize redundâncias de desenvolvimento
- Otimize a sequência de entregas
- Garanta consistência de experiência do usuário

## Metodologia de Consolidação

### Critérios para Consolidação de Requisitos

1. **Funcionalidade Base Idêntica**: Requisitos que realizam exatamente a mesma operação
2. **Interface Comum**: Requisitos que podem compartilhar a mesma interface com parametrização
3. **Arquitetura Compartilhada**: Requisitos que utilizam os mesmos componentes técnicos

### Codificação de Requisitos Consolidados

Os requisitos consolidados seguem o padrão **RF0XC-NW**, onde:

- **RF**: Requisito Funcional
- **0X**: Número sequencial (01, 02, 03, etc.)
- **C**: Indica que é um requisito **Consolidado**
- **NW**: Módulo Newave

Exemplo: **RF01C-NW** = Primeiro requisito funcional consolidado do módulo Newave

## Análise de Requisitos Similares e Consolidações

### Requisitos Consolidados

| **Requisito Consolidado** | **Origem**                           | **Justificativa da Consolidação**                                                                                       |
| ------------------------- | ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| **RF01C-NW**              | RF01-NW (Emissões), RF13-NW (Ruídos) | Ambos implementam coleta via ZS com formulário. Pode ser uma interface genérica parametrizada por tipo de monitoramento |
| **RF02C-NW**              | RF04-NW (Emissões), RF16-NW (Ruídos) | Funcionalidade transversal idêntica para ambos os programas                                                             |
| **RF03C-NW**              | RF03-NW (Emissões), RF15-NW (Ruídos) | Mesmo mecanismo de upload automático, diferindo apenas no tipo de arquivo                                               |
| **RF04C-NW**              | RF05-NW (Emissões), RF17-NW (Ruídos) | Mesmo banco de dados pode atender ambos com estrutura parametrizada                                                     |
| **RF05C-NW**              | RF06-NW (Emissões), RF18-NW (Ruídos) | Integração ZS/GIZA/TimeStamp é comum aos dois programas                                                                 |
| **RF06C-NW**              | RF08-NW (Emissões), RF20-NW (Ruídos) | Interface comum para download, parametrizada por tipo de conteúdo                                                       |
| **RF07C-NW**              | RF09-NW (Emissões), RF21-NW (Ruídos) | Mesma funcionalidade de tabela, diferindo apenas nas colunas específicas                                                |

### Backlog Consolidado por Epic

## Epic 1: Infraestrutura Base

**Objetivo**: Estabelecer fundações técnicas comuns

| **Item** | **Descrição**                                                      | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | ------------------------------------------------------------------ | -------------- | ---------------- | -------------------------- |
| RF02C-NW | Sistema de trabalho offline com sincronização                      | Alta           | 13               | Emissões, Ruídos           |
| RF04C-NW | Banco de dados parametrizado para múltiplos tipos de monitoramento | Alta           | 8                | Emissões, Ruídos           |
| RF05C-NW | Integração com ZS, GIZA e TimeStamp                                | Alta           | 13               | Emissões, Ruídos           |

## Epic 2: Coleta de Dados

**Objetivo**: Funcionalidades core de coleta em campo

| **Item** | **Descrição**                                       | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | --------------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF01C-NW | Interface genérica de coleta via ZS (parametrizada) | Alta           | 8                | Emissões, Ruídos           |
| RF02-NW  | Ficha específica para CO₂, CO e SO₂ por ponto       | Alta           | 5                | Emissões                   |
| RF14-NW  | Registro de níveis sonoros com timestamp            | Alta           | 5                | Ruídos                     |
| RF03C-NW | Upload automático de evidências (fotos/áudio)       | Alta           | 8                | Emissões, Ruídos           |

## Epic 3: Visualização e Dashboard

**Objetivo**: Interfaces de visualização e monitoramento

| **Item** | **Descrição**                                 | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | --------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF07C-NW | Tabela genérica filtrável e exportável        | Média          | 5                | Emissões, Ruídos           |
| RF07-NW  | Dashboard com farol de cor para emissões      | Média          | 8                | Emissões                   |
| RF19-NW  | Dashboard de níveis de ruído por área/período | Média          | 8                | Ruídos                     |
| RF06C-NW | Sistema de download por lote e individual     | Média          | 5                | Emissões, Ruídos           |

## Epic 2: Coleta de Dados

**Objetivo**: Funcionalidades core de coleta em campo

| **Item**                | **Descrição**                                       | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| ----------------------- | --------------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF-NW-COLETA-OFFLINE    | Interface genérica de coleta via ZS (parametrizada) | Alta           | 8                | Emissões, Ruídos           |
| RF02-NW                 | Ficha específica para CO₂, CO e SO₂ por ponto       | Alta           | 5                | Emissões                   |
| RF14-NW                 | Registro de níveis sonoros com timestamp            | Alta           | 5                | Ruídos                     |
| RF-NW-ANEXAR-EVIDENCIAS | Upload automático de evidências (fotos/áudio)       | Alta           | 8                | Emissões, Ruídos           |

## Epic 3: Visualização e Dashboard

**Objetivo**: Interfaces de visualização e monitoramento

| **Item**                | **Descrição**                                 | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| ----------------------- | --------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF-NW-TABELA-FILTRAVEL  | Tabela genérica filtrável e exportável        | Média          | 5                | Emissões, Ruídos           |
| RF07-NW                 | Dashboard com farol de cor para emissões      | Média          | 8                | Emissões                   |
| RF19-NW                 | Dashboard de níveis de ruído por área/período | Média          | 8                | Ruídos                     |
| RF-NW-DOWNLOAD-ARQUIVOS | Sistema de download por lote e individual     | Média          | 5                | Emissões, Ruídos           |

## Epic 4: Relatórios e Exportação

**Objetivo**: Geração automática de relatórios

| **Item** | **Descrição**                            | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | ---------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF10-NW  | Exportação para Excel (Emissões)         | Média          | 5                | Emissões                   |
| RF22-NW  | Relatórios automáticos no GIZA (Ruídos)  | Média          | 8                | Ruídos                     |
| RF11-NW  | Relatórios padrão regulatório (Emissões) | Baixa          | 8                | Emissões                   |
| RF12-NW  | Inserção manual de dados complementares  | Baixa          | 3                | Emissões                   |

## Epic 5: Análises Especializadas

**Objetivo**: Funcionalidades avançadas de análise

| **Item** | **Descrição**                      | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | ---------------------------------- | -------------- | ---------------- | -------------------------- |
| RF23-NW  | Análise de impacto na fauna        | Baixa          | 13               | Ruídos                     |
| RF24-NW  | Registro de impacto em área urbana | Baixa          | 5                | Ruídos                     |

## Riscos e Mitigações

| **Risco**                               | **Probabilidade** | **Impacto** | **Mitigação**                                           |
| --------------------------------------- | ----------------- | ----------- | ------------------------------------------------------- |
| Over-engineering da solução genérica    | Média             | Alto        | Implementar MVP específico primeiro, generalizar depois |
| Conflitos de requisitos entre programas | Baixa             | Médio       | Validação contínua com stakeholders de ambos programas  |
| Dependências técnicas complexas         | Média             | Alto        | Arquitetura modular com baixo acoplamento               |

## Métricas de Sucesso

- **Reuso de Código**: Meta de 60% de componentes compartilhados
- **Velocidade de Desenvolvimento**: Redução de 30% no time-to-market do segundo programa
- **Satisfação do Usuário**: Score NPS > 8 para interface unificada
- **Qualidade**: Redução de 25% em bugs relacionados a funcionalidades similares

## Próximos Passos

1. **Validação do Backlog** com stakeholders de ambos os programas
2. **Definição da Arquitetura** para suportar consolidações propostas
3. **Prototipagem** das interfaces genéricas identificadas
4. **Planejamento Detalhado** das próximas entregas
