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

| **Requisito Consolidado** | **Origem**                                             | **Justificativa da Consolidação**                                                                      |
| ------------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| **RF01C-NW**              | RF01-NW (Emissões), RF13-NW (Ruídos), RF25-NW (Erosão) | Interface genérica de coleta via ZS parametrizada por tipo de monitoramento (emissões, ruídos, erosão) |
| **RF02C-NW**              | RF04-NW (Emissões), RF16-NW (Ruídos), RF28-NW (Erosão) | Funcionalidade transversal de trabalho offline idêntica para todos os programas                        |
| **RF03C-NW**              | RF03-NW (Emissões), RF15-NW (Ruídos), RF27-NW (Erosão) | Mesmo mecanismo de upload automático, diferindo apenas no tipo de arquivo/evidência                    |
| **RF04C-NW**              | RF05-NW (Emissões), RF17-NW (Ruídos), RF29-NW (Erosão) | Banco de dados unificado com versionamento para múltiplos tipos de monitoramento                       |
| **RF05C-NW**              | RF06-NW (Emissões), RF18-NW (Ruídos), RF30-NW (Erosão) | Integração com ZS, GIZA e TimeStamp comum aos três programas                                           |
| **RF06C-NW**              | RF08-NW (Emissões), RF20-NW (Ruídos), RF32-NW (Erosão) | Interface comum para download, parametrizada por tipo de conteúdo                                      |
| **RF07C-NW**              | RF09-NW (Emissões), RF21-NW (Ruídos), RF33-NW (Erosão) | Tabela genérica filtrável e exportável, parametrizada por colunas específicas                          |
| **RF08C-NW**              | RF11-NW (Emissões), RF22-NW (Ruídos), RF34-NW (Erosão) | Sistema unificado de geração de relatórios conforme padrões regulatórios                               |

### Backlog Consolidado por Epic

## Epic 1: Coleta

**Objetivo**: Funcionalidades de coleta de dados em campo

| **Item** | **Descrição**                                            | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | -------------------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF01C-NW | Interface genérica de coleta via ZS (parametrizada)      | Alta           | 8                | Emissões, Ruídos, Erosão   |
| RF02-NW  | Ficha específica para CO₂, CO e SO₂ por ponto            | Alta           | 5                | Emissões                   |
| RF14-NW  | Registro de níveis sonoros com timestamp                 | Alta           | 5                | Ruídos                     |
| RF26-NW  | Medições de perda de solo com GPS automático             | Alta           | 8                | Erosão                     |
| RF02C-NW | Sistema de trabalho offline com sincronização            | Alta           | 13               | Emissões, Ruídos, Erosão   |
| RF03C-NW | Upload automático de evidências (fotos/áudio/topografia) | Alta           | 8                | Emissões, Ruídos, Erosão   |
| RF12-NW  | Inserção manual de dados complementares (Emissões)       | Baixa          | 3                | Emissões                   |

## Epic 2: Armazenamento

**Objetivo**: Estruturas de dados e persistência

| **Item** | **Descrição**                                                      | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | ------------------------------------------------------------------ | -------------- | ---------------- | -------------------------- |
| RF04C-NW | Banco de dados parametrizado para múltiplos tipos de monitoramento | Alta           | 8                | Emissões, Ruídos, Erosão   |
| RF05C-NW | Integração com ZS, GIZA e TimeStamp                                | Alta           | 13               | Emissões, Ruídos, Erosão   |

## Epic 3: Tratamento

**Objetivo**: Processamento e análise de dados coletados

| **Item** | **Descrição**                            | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | ---------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF23-NW  | Análise de impacto na fauna (Ruídos)     | Baixa          | 13               | Ruídos                     |
| RF35-NW  | Análise de tendência temporal da erosão  | Baixa          | 21               | Erosão                     |
| RF36-NW  | Eficácia de medidas mitigadoras (Erosão) | Baixa          | 8                | Erosão                     |

## Epic 4: Distribuição

**Objetivo**: Visualização, relatórios e compartilhamento de dados

| **Item** | **Descrição**                                 | **Prioridade** | **Story Points** | **Programas Beneficiados** |
| -------- | --------------------------------------------- | -------------- | ---------------- | -------------------------- |
| RF07C-NW | Tabela genérica filtrável e exportável        | Média          | 5                | Emissões, Ruídos, Erosão   |
| RF07-NW  | Dashboard com farol de cor para emissões      | Média          | 8                | Emissões                   |
| RF19-NW  | Dashboard de níveis de ruído por área/período | Média          | 8                | Ruídos                     |
| RF31-NW  | Mapa de calor com níveis de erosão por área   | Média          | 8                | Erosão                     |
| RF06C-NW | Sistema de download por lote e individual     | Média          | 5                | Emissões, Ruídos, Erosão   |
| RF08C-NW | Sistema unificado de geração de relatórios    | Média          | 8                | Emissões, Ruídos, Erosão   |
| RF10-NW  | Exportação para Excel (Emissões)              | Média          | 5                | Emissões                   |
| RF24-NW  | Registro de impacto em área urbana (Ruídos)   | Baixa          | 5                | Ruídos                     |

## Backlog Detalhado por Prioridade

### **Alta Prioridade - MVP**

| **Item** | **Descrição**                     | **Epic**      | **Story Points** | **Programa**             |
| -------- | --------------------------------- | ------------- | ---------------- | ------------------------ |
| RF01C-NW | Interface genérica de coleta      | Coleta        | 8                | Emissões, Ruídos, Erosão |
| RF02C-NW | Sistema offline com sincronização | Coleta        | 13               | Emissões, Ruídos, Erosão |
| RF04C-NW | Banco de dados parametrizado      | Armazenamento | 8                | Emissões, Ruídos, Erosão |
| RF05C-NW | Integração ZS/GIZA/TimeStamp      | Armazenamento | 13               | Emissões, Ruídos, Erosão |
| RF02-NW  | Ficha CO₂, CO e SO₂               | Coleta        | 5                | Emissões                 |
| RF14-NW  | Registro níveis sonoros           | Coleta        | 5                | Ruídos                   |
| RF26-NW  | Medições de perda de solo         | Coleta        | 8                | Erosão                   |

### **Média Prioridade - Funcionalidades Completas**

| **Item** | **Descrição**                     | **Epic**     | **Story Points** | **Programa**             |
| -------- | --------------------------------- | ------------ | ---------------- | ------------------------ |
| RF03C-NW | Upload automático evidências      | Coleta       | 8                | Emissões, Ruídos, Erosão |
| RF07C-NW | Tabela filtrável e exportável     | Distribuição | 5                | Emissões, Ruídos, Erosão |
| RF06C-NW | Sistema de download               | Distribuição | 5                | Emissões, Ruídos, Erosão |
| RF08C-NW | Geração de relatórios unificada   | Distribuição | 8                | Emissões, Ruídos, Erosão |
| RF07-NW  | Dashboard farol de cor (Emissões) | Distribuição | 8                | Emissões                 |
| RF19-NW  | Dashboard níveis de ruído         | Distribuição | 8                | Ruídos                   |
| RF31-NW  | Mapa de calor erosão              | Distribuição | 8                | Erosão                   |
| RF10-NW  | Exportação Excel                  | Distribuição | 5                | Emissões                 |

### **Baixa Prioridade - Otimizações**

| **Item** | **Descrição**                   | **Epic**     | **Story Points** | **Programa** |
| -------- | ------------------------------- | ------------ | ---------------- | ------------ |
| RF12-NW  | Dados complementares (Emissões) | Coleta       | 3                | Emissões     |
| RF23-NW  | Análise impacto fauna           | Tratamento   | 13               | Ruídos       |
| RF24-NW  | Impacto área urbana             | Distribuição | 5                | Ruídos       |
| RF35-NW  | Análise temporal erosão         | Tratamento   | 21               | Erosão       |
| RF36-NW  | Eficácia medidas mitigadoras    | Tratamento   | 8                | Erosão       |
