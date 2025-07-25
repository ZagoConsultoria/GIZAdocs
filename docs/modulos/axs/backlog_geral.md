# Backlog Geral - Módulo AXS

## Introdução

Este documento consolida o backlog geral do módulo AXS, incluindo os programas PRAD e Plantio. O backlog está organizado por sprints e prioridades, facilitando o planejamento de desenvolvimento e a gestão do projeto.

## Objetivo

Fornecer uma visão consolidada de todas as funcionalidades do módulo AXS, permitindo planejamento eficiente do desenvolvimento e acompanhamento do progresso das entregas.

## Backlog Consolidado por Prioridade

### Prioridade Alta

| **Item** | **Programa** | **História**                                     | **Estimativa** | **Observações**             |
| -------- | ------------ | ------------------------------------------------ | -------------- | --------------------------- |
| 1.1      | PRAD         | US01-AXS - Coleta offline no ZS com edição       | 8 pts          | Base fundamental do sistema |
| 1.2      | Plantio      | US09-AXS - Formulário padronizado para plantio   | 5 pts          | Base fundamental do sistema |
| 1.3      | Plantio      | US12-AXS - Funcionamento offline                 | 8 pts          | Essencial para campo        |
| 1.4      | Plantio      | US13-AXS - Banco parametrizado com versionamento | 13 pts         | Segurança e análises        |
| 1.5      | PRAD         | US02-AXS - Transferência automática ZS para GIZA | 8 pts          | Integração crítica          |
| 1.6      | Plantio      | US10-AXS - GPS automático por ponto              | 5 pts          | Localização essencial       |
| 1.7      | Plantio      | US14-AXS - Integração ZS, GIZA e SharePoint      | 13 pts         | Centralização de dados      |
| 1.8      | Plantio      | US11-AXS - Upload automático de fotos            | 8 pts          | Reduz trabalho manual       |
| 1.9      | PRAD         | US08-AXS - Relatórios editáveis                  | 13 pts         | Entrega de valor            |
| 1.10     | Plantio      | US19-AXS - Relatórios automatizados padrão AXS   | 13 pts         | Entrega de valor            |

### Prioridade Média

| **Item** | **Programa** | **História**                                            | **Estimativa** | **Observações**         |
| -------- | ------------ | ------------------------------------------------------- | -------------- | ----------------------- |
| 2.1      | PRAD         | US06-AXS - Dashboard com tabela filtrável               | 8 pts          | Melhora visualização    |
| 2.2      | Plantio      | US16-AXS - Dashboard de visualização                    | 8 pts          | Melhora experiência     |
| 2.3      | Plantio      | US18-AXS - Tabela filtrável e exportável                | 5 pts          | Facilita análises       |
| 2.4      | PRAD         | US03-AXS - Visualização de fotos por registro           | 5 pts          | Conveniência            |
| 2.5      | PRAD         | US04-AXS - Download de fotos por lote/individual        | 8 pts          | Funcionalidade útil     |
| 2.6      | PRAD         | US07-AXS - Análise visual (estado planta, pragas, etc.) | 13 pts         | Funcionalidade avançada |
| 2.7      | Plantio      | US15-AXS - Correção automática por IA                   | 13 pts         | Melhoria de qualidade   |
| 2.8      | Plantio      | US17-AXS - Download de fotos por lote/individual        | 5 pts          | Conveniência adicional  |

### Prioridade Baixa

| **Item** | **Programa** | **História**                                    | **Estimativa** | **Observações** |
| -------- | ------------ | ----------------------------------------------- | -------------- | --------------- |
| 3.1      | PRAD         | US05-AXS - Edição de dados por registro no GIZA | 8 pts          | Refinamento     |
| 3.2      | Plantio      | US20-AXS - Edição controlada via GIZA           | 8 pts          | Refinamento     |

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
