# Priorização de Requisitos - Monitoramento de Ruídos

## Introdução

Este documento apresenta a priorização dos requisitos funcionais do módulo de **Monitoramento de Ruídos** utilizando a técnica dos 100 dólares. A priorização foi realizada considerando o valor de negócio, urgência, complexidade de implementação e dependências técnicas, com foco no impacto da obra na fauna e área urbana.

## Objetivo

Definir a ordem de implementação dos requisitos com base em:

- Valor percebido pelo usuário final (Bruna)
- Criticidade para operação de campo
- Dependências técnicas e arquiteturais
- Viabilidade de entrega incremental

## Metodologia

A priorização foi realizada através da técnica dos 100 dólares, onde os stakeholders distribuíram pontos entre os requisitos conforme sua importância percebida. Considerou-se também:

- Análise de dependências entre requisitos
- Complexidade de implementação
- Impacto no fluxo de trabalho atual
- Necessidades regulatórias de monitoramento ambiental

## Tabela de Priorização {#tabela-priorizacao}

| **Req. ID**                                              | **Descrição do Requisito**                                                     | **Pontuação** | **Prioridade** | **Justificativa**                                                   |
| -------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------- | -------------- | ------------------------------------------------------------------- |
| [RF13-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Permitir a coleta de dados de ruído via ZS com formulário automatizado         | 15            | Alta           | Funcionalidade core para substituir processo manual                 |
| [RF14-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Registrar níveis sonoros por ponto de medição com data/hora automática         | 12            | Alta           | Essencial para rastreabilidade e conformidade regulatória           |
| [RF16-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Permitir funcionamento offline durante a coleta                                | 10            | Alta           | Crítico para trabalho em campo sem conectividade                    |
| [RF17-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Armazenar os dados em banco de dados parametrizado de forma automática         | 9             | Alta           | Base para todas as funcionalidades de análise                       |
| [RF15-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Anexar automaticamente as evidências sonoras e fotográficas ao GIZA            | 8             | Alta           | Reduz trabalho manual e garante evidências                          |
| [RF19-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Exibir dashboard no GIZA com visualização de níveis por área/período           | 7             | Média          | Importante para análise mas pode ser implementado em fase posterior |
| [RF22-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Gerar relatórios automáticos no GIZA a um clique                               | 7             | Média          | Alto valor para usuário mas depende de outras funcionalidades       |
| [RF18-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Integrar com ZS, GIZA e TimeStamp                                              | 6             | Média          | Necessário para fluxo completo                                      |
| [RF21-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Exibir dados em formato de tabela filtrável e exportável                       | 6             | Média          | Facilita análise manual dos dados                                   |
| [RF20-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Permitir download de dados e arquivos de áudio por lote ou registro individual | 5             | Média          | Útil para análise externa                                           |
| [RF23-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Permitir análise de impacto na fauna com base nos níveis registrados           | 4             | Baixa          | Funcionalidade especializada, pode ser implementada após MVP        |
| [RF24-NW](../elicitacao/ruidos.md#requisitos-funcionais) | Registrar observações sobre impacto em área urbana por ponto de coleta         | 4             | Baixa          | Importante mas não crítico para funcionalidade básica               |

## Análise de Dependências

### Alta Prioridade (Implementação Imediata)

- **RF13-NW** → Base para toda funcionalidade
- **RF14-NW** → Depende de RF13-NW
- **RF16-NW** → Requisito transversal
- **RF17-NW** → Infraestrutura necessária
- **RF15-NW** → Depende de RF13-NW e RF17-NW

### Média Prioridade (Segunda Fase)

- **RF18-NW** → Depende de RF13-NW, RF14-NW, RF17-NW
- **RF19-NW** → Depende de RF17-NW e RF18-NW
- **RF21-NW** → Depende de RF17-NW
- **RF22-NW** → Depende de RF17-NW, RF18-NW
- **RF20-NW** → Depende de RF17-NW

### Baixa Prioridade (Fases Futuras)

- **RF23-NW** → Depende de RF14-NW, RF17-NW
- **RF24-NW** → Depende de RF13-NW, RF17-NW

## Considerações Técnicas

- **Prioridade Alta**: Funcionalidades essenciais para MVP
- **Prioridade Média**: Agregam valor significativo mas podem ser implementadas incrementalmente
- **Prioridade Baixa**: Funcionalidades especializadas para versões futuras

## Próximos Passos

1. **Desenvolvimento do MVP** com requisitos de alta prioridade
2. **Validação em campo** das funcionalidades básicas
3. **Implementação incremental** dos requisitos de média prioridade
4. **Expansão funcional** com requisitos especializados
