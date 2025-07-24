# Monitoramento de Ruídos

## Introdução

Esta documentação tem como objetivo registrar e organizar os requisitos levantados durante as reuniões de elicitação para o módulo de **Monitoramento de Ruídos** do aplicativo em desenvolvimento. A funcionalidade será utilizada para registrar medições de níveis sonoros em campo, acompanhar o impacto da obra na fauna e na área urbana, com integração posterior à plataforma GIZA.

## Objetivo

Construir um sistema capaz de:

- Coletar dados de campo relacionados a níveis de ruído e impacto sonoro;
- Acompanhar o impacto da obra na fauna e na área urbana;
- Visualizar as medições de maneira clara e filtrável;
- Permitir exportações (dados e relatórios) para análise de impacto ambiental;
- Operar offline e em dispositivos móveis.

## Metodologia

A elicitação de requisitos foi realizada com base em:

- Reuniões com stakeholders do projeto (Bruna e Daniella);
- Análise dos fluxos de trabalho atuais;
- Observação de processos similares de monitoramento ambiental;
- Identificação de lacunas no processo atual de coleta e organização de dados de ruído.

## Stakeholders

### 👩‍💻 Usuários

- **Usuários finais**: Bruna
- **Influenciadores e tomadores de decisão**: Daniella
- **Visão/Impacto no Cliente**: Acompanhar o impacto da obra na fauna e na área urbana

### Requisitos Funcionais {#requisitos-funcionais}

| **ID**  | **Requisito Funcional**                                                         |
| ------- | ------------------------------------------------------------------------------- |
| RF13-NW | Permitir a coleta de dados de ruído via ZS com formulário automatizado.         |
| RF14-NW | Registrar níveis sonoros por ponto de medição com data/hora automática.         |
| RF15-NW | Anexar automaticamente as evidências sonoras e fotográficas ao GIZA.            |
| RF16-NW | Permitir funcionamento offline durante a coleta.                                |
| RF17-NW | Armazenar os dados em banco de dados parametrizado de forma automática.         |
| RF18-NW | Integrar com ZS, GIZA e TimeStamp.                                              |
| RF19-NW | Exibir dashboard no GIZA com visualização de níveis por área/período.           |
| RF20-NW | Permitir download de dados e arquivos de áudio por lote ou registro individual. |
| RF21-NW | Exibir dados em formato de tabela filtrável e exportável.                       |
| RF22-NW | Gerar relatórios automáticos no GIZA a um clique.                               |
| RF23-NW | Permitir análise de impacto na fauna com base nos níveis registrados.           |
| RF24-NW | Registrar observações sobre impacto em área urbana por ponto de coleta.         |

### Requisitos Não Funcionais {#requisitos-nao-funcionais}

| **ID**   | **Requisito Não Funcional**                                                                |
| -------- | ------------------------------------------------------------------------------------------ |
| RNF06-NW | Interface intuitiva e adequada para usuário com nível 5/10 de conhecimento em informática. |
| RNF07-NW | Evitar perda de dados e falhas de funcionamento durante medições.                          |
| RNF08-NW | Garantir desempenho estável, inclusive no modo offline.                                    |
| RNF09-NW | Instalação possível no celular e acesso também via navegador.                              |
| RNF10-NW | Garantir segurança e sigilo dos dados de impacto ambiental.                                |
| RNF11-NW | Suportar gravação e armazenamento de arquivos de áudio de alta qualidade.                  |

## Análise de Dores e Soluções

### 💼 Resumo e Priorização de dores

| **Etapa**     | **Possível Solução**                          | **Benefícios 🥰**                                                              | **Riscos ⛔**                                                                                               |
| ------------- | --------------------------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| Coleta        | Criar formulário no aplicativo de coleta - ZS | Coleta de dados automatizada                                                   | -                                                                                                           |
| Armazenamento | Construção do Banco de dados parametrizado    | Armazenamento automático sem necessidade de subir as fotos e dados manualmente | -                                                                                                           |
| Distribuição  | Geração automática de relatórios no GIZA      | Relatório a um clique                                                          | Hoje os relatórios têm mais de um programa junto o que pode gerar um baixo uso dos novos relatórios criados |

## Observações

- A visualização de níveis de ruído pode seguir padrões de monitoramento ambiental com alertas para valores críticos.
- Integração com sistemas de medição de ruído existentes deve ser considerada.
- Consideração especial para impacto na fauna local durante diferentes períodos do dia.

## Próximos Passos

1. **Criação de protótipos das telas** com base nos formulários de coleta de ruído;
2. **Validação dos requisitos** com usuários finais (Bruna e Daniella);
3. **Definição da arquitetura de dados** para armazenamento de arquivos de áudio;
4. **Implementação do módulo de coleta em campo**;
5. **Testes de integração com GIZA** para geração automática de relatórios;
6. **Planejamento do fluxo de análise de impacto** na fauna e área urbana.
