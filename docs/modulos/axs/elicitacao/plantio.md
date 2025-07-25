# Elicitação de Requisitos - Programa Pré-Plantio AXS

## Introdução

Este documento apresenta os requisitos funcionais e não funcionais identificados para o programa de monitoramento de plantio da AXS. A elicitação foi baseada em entrevistas exploratórias com usuários de campo, análise de processos atuais e identificação de dores e necessidades específicas relacionadas à coleta, armazenamento, tratamento e distribuição de dados de caracterização de plantio.

## Objetivo

Definir requisitos claros e precisos para o desenvolvimento de uma solução integrada que automatize e otimize o processo de coleta e gestão de dados de plantio, desde a caracterização em campo até a geração de relatórios automatizados, visando reduzir o trabalho manual e aumentar a qualidade e segurança dos dados coletados.

## Requisitos Funcionais

| **ID**   | **Descrição**                                                                           | **Prioridade** | **Fonte**                   |
| -------- | --------------------------------------------------------------------------------------- | -------------- | --------------------------- |
| RF09-AXS | Permitir coleta de dados de caracterização de plantio via ZS com formulário padronizado | Alta           | Entrevistas com usuários    |
| RF10-AXS | Registrar informações de plantio por ponto com coordenadas GPS automáticas              | Alta           | Necessidade de campo        |
| RF11-AXS | Anexar automaticamente evidências fotográficas do plantio ao GIZA e SharePoint          | Alta           | Processo atual manual       |
| RF12-AXS | Permitir funcionamento offline durante coletas em áreas remotas                         | Alta           | Limitações de conectividade |
| RF13-AXS | Armazenar dados em banco parametrizado com versionamento para análise temporal          | Alta           | Análises futuras            |
| RF14-AXS | Integrar com ZS, GIZA e SharePoint para centralização de dados                          | Alta           | Integração de sistemas      |
| RF15-AXS | Aplicar correção automática de textos por inteligência artificial                       | Média          | Redução de trabalho manual  |
| RF16-AXS | Exibir dashboard no GIZA com visualização de dados de plantio                           | Média          | Visualização centralizada   |
| RF17-AXS | Permitir download de fotos por lote ou registro individual                              | Média          | Facilitar acesso aos dados  |
| RF18-AXS | Exibir dados em formato de tabela filtrável e exportável                                | Média          | Análise e exportação        |
| RF19-AXS | Gerar relatórios automatizados conforme padrão AXS                                      | Alta           | Automatização de relatórios |
| RF20-AXS | Permitir edição controlada de dados coletados via interface GIZA                        | Baixa          | Correções pontuais          |

## Requisitos Não Funcionais

| **ID**    | **Descrição**                                                                     | **Prioridade** | **Categoria**   |
| --------- | --------------------------------------------------------------------------------- | -------------- | --------------- |
| RNF06-AXS | Interface intuitiva adequada para usuários com conhecimento básico em informática | Alta           | Usabilidade     |
| RNF07-AXS | Garantir segurança e integridade dos dados coletados                              | Alta           | Segurança       |
| RNF08-AXS | Sistema deve funcionar offline com sincronização automática                       | Alta           | Confiabilidade  |
| RNF09-AXS | Performance estável durante uso em campo e visualizações no GIZA                  | Média          | Performance     |
| RNF10-AXS | Compatibilidade com dispositivos móveis e acesso via navegador                    | Média          | Compatibilidade |
| RNF11-AXS | Correção automática deve ter taxa de acerto superior a 95%                        | Média          | Qualidade       |

## Glossário

- **ZS**: Sistema de coleta de dados em campo
- **GIZA**: Plataforma de visualização e gestão de dados
- **SharePoint**: Sistema de armazenamento e compartilhamento de documentos
- **Caracterização de plantio**: Processo de documentação e análise das condições e características do plantio realizado
- **Formulário padronizado**: Estrutura definida para coleta consistente de dados de plantio
