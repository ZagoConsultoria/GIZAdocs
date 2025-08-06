# Elicitação de Requisitos - Módulo Eletronorte

## Introdução

Este documento apresenta a elicitação de requisitos funcionais para o módulo **Eletronorte**, dedicado à automatização da coleta e gestão de dados para acompanhamento de atividades no viveiro e monitoramento ambiental na Estação Ecológica (ESEC). Os requisitos foram identificados com base no discovery realizado junto aos stakeholders e na análise das necessidades dos processos atuais de coleta manual.

## Objetivo

Definir os requisitos funcionais e não funcionais necessários para implementar um sistema integrado que permita:

- Coleta eficiente de dados diários do viveiro através de formulários digitais offline
- Monitoramento e controle de mudas por espécie com cálculos automatizados
- Organização automática de fotos e evidências por atividade e data
- Geração automática de relatórios mensais formatados para envio ao cliente
- Substituição do processo manual atual que utiliza múltiplos dispositivos e sistemas

---

## Requisitos Funcionais {#requisitos-funcionais}

| **ID**      | **Descrição**                                                                    | **Categoria**        |
| ----------- | -------------------------------------------------------------------------------- | -------------------- |
| **RF01-EL** | Interface de coleta via ZS para acompanhamento diário de atividades no viveiro   | Coleta de Dados      |
| **RF02-EL** | Registro de dados gerais (data, responsável, clima, horário)                     | Coleta de Dados      |
| **RF03-EL** | Registro de atividades de irrigação (frequência, tempo, setores)                 | Coleta de Dados      |
| **RF04-EL** | Registro de atividades de adubação (tipo, espécies, cronograma)                  | Coleta de Dados      |
| **RF05-EL** | Registro de pragas e doenças (identificação, sintomas, espécies afetadas)        | Coleta de Dados      |
| **RF06-EL** | Registro de atividades de manutenção (capina, descarte, replantio, equipamentos) | Coleta de Dados      |
| **RF07-EL** | Sistema de upload múltiplo de fotos com georreferenciamento automático           | Coleta de Dados      |
| **RF08-EL** | Sistema de favoritar fotos importantes para inclusão automática em relatórios    | Coleta de Dados      |
| **RF09-EL** | Registro de contagem e medição de mudas por espécie e setor                      | Controle de Mudas    |
| **RF10-EL** | Lista pré-definida de 17 espécies nativas com opção "Outro"                      | Controle de Mudas    |
| **RF11-EL** | Cálculo automático de médias de altura e diâmetro por espécie                    | Controle de Mudas    |
| **RF12-EL** | Histórico de medições com comparação temporal                                    | Controle de Mudas    |
| **RF13-EL** | Sistema de funcionamento offline com sincronização automática                    | Infraestrutura       |
| **RF14-EL** | Captura automática de coordenadas GPS em todos os registros                      | Infraestrutura       |
| **RF15-EL** | Backup automático local de dados com indicador de status de sincronização        | Infraestrutura       |
| **RF16-EL** | Validação automática de campos obrigatórios e condicionais                       | Infraestrutura       |
| **RF17-EL** | Integração com ZS para recebimento automático dos dados coletados                | Integração           |
| **RF18-EL** | Integração com GIZA para centralização e visualização dos dados                  | Integração           |
| **RF19-EL** | Sincronização automática com Google Drive para organização de fotos              | Integração           |
| **RF20-EL** | Análise de viabilidade de integração com sistema Mata Nativa                     | Integração           |
| **RF21-EL** | Interface de visualização com tabela filtrável para dados do viveiro             | Visualização         |
| **RF22-EL** | Filtros avançados por data, atividade, responsável e espécie                     | Visualização         |
| **RF23-EL** | Busca textual em observações e campos de texto livre                             | Visualização         |
| **RF24-EL** | Sistema de visualização de fotos por registro com download individual            | Visualização         |
| **RF25-EL** | Download de fotos em lote (favoritas e por filtros)                              | Visualização         |
| **RF26-EL** | Calendário de atividades com indicadores de status                               | Visualização         |
| **RF27-EL** | Dashboard com gráficos de crescimento de mudas por espécie                       | Dashboard/Relatórios |
| **RF28-EL** | Dashboard com indicadores de taxa de mortalidade e replantio                     | Dashboard/Relatórios |
| **RF29-EL** | Dashboard com métricas de irrigação e adubação                                   | Dashboard/Relatórios |
| **RF30-EL** | Dashboard com indicadores de pragas e doenças identificadas                      | Dashboard/Relatórios |
| **RF31-EL** | Geração automática de relatórios mensais no template padrão da Eletronorte       | Dashboard/Relatórios |
| **RF32-EL** | Inserção automática de fotos favoritadas nos campos apropriados do relatório     | Dashboard/Relatórios |
| **RF33-EL** | Interface de edição e customização do relatório antes do envio                   | Dashboard/Relatórios |
| **RF34-EL** | Exportação de relatórios                                                         | Dashboard/Relatórios |
| **RF35-EL** | Exportação de dados de mudas para Excel com formatação para tabelas dinâmicas    | Dashboard/Relatórios |
| **RF36-EL** | Exportação de coordenadas geográficas para planilhas                             | Dashboard/Relatórios |
| **RF37-EL** | Sistema de edição controlada de registros via GIZA                               | Gestão               |

## Requisitos Não Funcionais {#requisitos-nao-funcionais}

| **ID**       | **Descrição**                                                                    | **Categoria**   |
| ------------ | -------------------------------------------------------------------------------- | --------------- |
| **RNF01-EL** | Sistema deve funcionar offline em dispositivos móveis sem conexão à internet     | Disponibilidade |
| **RNF02-EL** | Sincronização automática em até 5 minutos após conectar à internet               | Performance     |
| **RNF03-EL** | Interface responsiva otimizada para tablets e smartphones Android/iOS            | Usabilidade     |
| **RNF04-EL** | Suporte para armazenamento local de até 1000 registros offline                   | Performance     |
| **RNF05-EL** | Tempo de resposta inferior a 3 segundos para todas as operações                  | Performance     |
| **RNF06-EL** | Compressão automática de fotos para otimizar armazenamento (máximo 5MB por foto) | Performance     |
| **RNF07-EL** | Interface intuitiva que não exija treinamento extensivo dos usuários             | Usabilidade     |
| **RNF08-EL** | Funcionamento com conectividade 3G ou superior quando online                     | Compatibilidade |
| **RNF09-EL** | Backup automático de dados a cada 24 horas                                       | Confiabilidade  |
| **RNF10-EL** | Criptografia de dados durante armazenamento e transmissão                        | Segurança       |
| **RNF11-EL** | Sistema de autenticação segura com controle de sessão                            | Segurança       |
| **RNF12-EL** | Resolução automática de conflitos durante sincronização                          | Confiabilidade  |
| **RNF13-EL** | Disponibilidade de 99% durante horário comercial                                 | Confiabilidade  |
| **RNF14-EL** | Suporte para múltiplos dispositivos simultâneos por usuário                      | Escalabilidade  |
| **RNF15-EL** | Arquitetura escalável para expansão futura de funcionalidades                    | Escalabilidade  |

---
