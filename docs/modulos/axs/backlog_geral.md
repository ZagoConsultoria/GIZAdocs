# Backlog Geral - Módulo AXS

## Introdução

Este documento consolida o backlog geral do módulo AXS, incluindo os programas PRAD e Plantio. O backlog está organizado por epics baseados no ciclo de vida dos dados (coleta, armazenamento, tratamento, distribuição) e prioridades, facilitando o planejamento de desenvolvimento e a gestão do projeto.

## Objetivo

Fornecer uma visão consolidada de todas as funcionalidades do módulo AXS, permitindo planejamento eficiente do desenvolvimento e acompanhamento do progresso das entregas organizadas por fase do ciclo de dados.

## Backlog Consolidado por Epic

### Epic 1: Coleta

**Objetivo**: Funcionalidades de coleta de dados em campo

| **Item** | **Programa** | **História**                        | **Prioridade** | **Estimativa** | **Observações**             |
| -------- | ------------ | ----------------------------------- | -------------- | -------------- | --------------------------- |
| US01-AXS | PRAD         | Coleta offline no ZS com edição     | Alta           | 8 pts          | Base fundamental do sistema |
| US09-AXS | Plantio      | Formulário padronizado para plantio | Alta           | 5 pts          | Base fundamental do sistema |
| US12-AXS | Plantio      | Funcionamento offline               | Alta           | 8 pts          | Essencial para campo        |
| US10-AXS | Plantio      | GPS automático por ponto            | Alta           | 5 pts          | Localização essencial       |
| US11-AXS | Plantio      | Upload automático de fotos          | Alta           | 8 pts          | Reduz trabalho manual       |
| US15-AXS | Plantio      | Correção automática por IA          | Média          | 13 pts         | Melhoria de qualidade       |

### Epic 2: Armazenamento

**Objetivo**: Estruturas de dados e persistência

| **Item** | **Programa** | **História**                          | **Prioridade** | **Estimativa** | **Observações**        |
| -------- | ------------ | ------------------------------------- | -------------- | -------------- | ---------------------- |
| US13-AXS | Plantio      | Banco parametrizado com versionamento | Alta           | 13 pts         | Segurança e análises   |
| US02-AXS | PRAD         | Transferência automática ZS para GIZA | Alta           | 8 pts          | Integração crítica     |
| US14-AXS | Plantio      | Integração ZS, GIZA e SharePoint      | Alta           | 13 pts         | Centralização de dados |

### Epic 3: Tratamento

**Objetivo**: Processamento e análise de dados coletados

| **Item** | **Programa** | **História**                                 | **Prioridade** | **Estimativa** | **Observações**         |
| -------- | ------------ | -------------------------------------------- | -------------- | -------------- | ----------------------- |
| US07-AXS | PRAD         | Análise visual (estado planta, pragas, etc.) | Média          | 13 pts         | Funcionalidade avançada |

### Epic 4: Distribuição

**Objetivo**: Visualização, relatórios e compartilhamento de dados

| **Item** | **Programa** | **História**                          | **Prioridade** | **Estimativa** | **Observações**        |
| -------- | ------------ | ------------------------------------- | -------------- | -------------- | ---------------------- |
| US08-AXS | PRAD         | Relatórios editáveis                  | Alta           | 13 pts         | Entrega de valor       |
| US19-AXS | Plantio      | Relatórios automatizados padrão AXS   | Alta           | 13 pts         | Entrega de valor       |
| US06-AXS | PRAD         | Dashboard com tabela filtrável        | Média          | 8 pts          | Melhora visualização   |
| US16-AXS | Plantio      | Dashboard de visualização             | Média          | 8 pts          | Melhora experiência    |
| US18-AXS | Plantio      | Tabela filtrável e exportável         | Média          | 5 pts          | Facilita análises      |
| US03-AXS | PRAD         | Visualização de fotos por registro    | Média          | 5 pts          | Conveniência           |
| US04-AXS | PRAD         | Download de fotos por lote/individual | Média          | 8 pts          | Funcionalidade útil    |
| US17-AXS | Plantio      | Download de fotos por lote/individual | Média          | 5 pts          | Conveniência adicional |
| US05-AXS | PRAD         | Edição de dados por registro no GIZA  | Baixa          | 8 pts          | Refinamento            |
| US20-AXS | Plantio      | Edição controlada via GIZA            | Baixa          | 8 pts          | Refinamento            |

## Consolidação de Requisitos Similares

### Requisitos Funcionais Consolidados

| **Req. ID** | **Descrição**                                     | **Programas Beneficiados** | **Justificativa**                                              |
| ----------- | ------------------------------------------------- | -------------------------- | -------------------------------------------------------------- |
| RFC01-AXS   | Interface genérica de coleta via ZS parametrizada | PRAD, Plantio              | Sistema único pode atender ambos com configurações específicas |
| RFC02-AXS   | Sistema de trabalho offline com sincronização     | PRAD, Plantio              | Funcionalidade idêntica para ambos os programas                |
| RFC03-AXS   | Upload automático de evidências fotográficas      | PRAD, Plantio              | Mesmo mecanismo de upload, diferindo apenas na organização     |
| RFC04-AXS   | Sistema de download de fotos (lote/individual)    | PRAD, Plantio              | Interface comum para download de evidências                    |
| RFC05-AXS   | Tabela genérica filtrável e exportável            | PRAD, Plantio              | Mesma funcionalidade, diferindo apenas nas colunas específicas |
| RFC06-AXS   | Sistema de edição controlada via GIZA             | PRAD, Plantio              | Controles de edição similares para ambos os programas          |

## Notas de Implementação

- Priorizar desenvolvimento de componentes consolidados para maximizar reutilização
- Funcionalidades de alta prioridade devem ser implementadas primeiro
- Funcionalidades de visualização e relatórios entregam valor imediato
- Refinamentos e edições podem ser implementados posteriormente
- Considerar implementação de RFC antes das histórias específicas para otimizar desenvolvimento
