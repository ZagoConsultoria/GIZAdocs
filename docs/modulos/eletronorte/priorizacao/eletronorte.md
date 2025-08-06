# Priorização de Requisitos - Módulo Eletronorte

## Introdução

Este documento apresenta a priorização dos requisitos funcionais e não funcionais do módulo **Eletronorte**, organizados por níveis de prioridade com base na criticidade para o funcionamento do sistema e valor de negócio. A priorização considera a coleta de dados do viveiro como funcionalidade core mais crítica, seguida por controle de mudas, visualização básica e, por último, funcionalidades de dashboard avançadas.

## Objetivo

Definir a ordem de implementação dos requisitos do sistema Eletronorte, garantindo que as funcionalidades mais críticas sejam desenvolvidas primeiro, permitindo entregas incrementais de valor para os usuários e substituindo efetivamente o processo manual atual.

---

## Priorização dos Requisitos {#tabela-priorizacao}

### Prioridade 1 - Crítica (MVP)

| **ID**       | **Descrição**                                                                    | **Tipo**      | **Categoria**     |
| ------------ | -------------------------------------------------------------------------------- | ------------- | ----------------- |
| **RF01-EL**  | Interface de coleta via ZS para acompanhamento diário de atividades no viveiro   | Funcional     | Coleta de Dados   |
| **RF02-EL**  | Registro de dados gerais (data, responsável, clima, horário)                     | Funcional     | Coleta de Dados   |
| **RF03-EL**  | Registro de atividades de irrigação (frequência, tempo, setores)                 | Funcional     | Coleta de Dados   |
| **RF04-EL**  | Registro de atividades de adubação (tipo, espécies, cronograma)                  | Funcional     | Coleta de Dados   |
| **RF05-EL**  | Registro de pragas e doenças (identificação, sintomas, espécies afetadas)        | Funcional     | Coleta de Dados   |
| **RF06-EL**  | Registro de atividades de manutenção (capina, descarte, replantio, equipamentos) | Funcional     | Coleta de Dados   |
| **RF07-EL**  | Sistema de upload múltiplo de fotos com georreferenciamento automático           | Funcional     | Coleta de Dados   |
| **RF09-EL**  | Registro de contagem e medição de mudas por espécie e setor                      | Funcional     | Controle de Mudas |
| **RF10-EL**  | Lista pré-definida de 17 espécies nativas com opção "Outro"                      | Funcional     | Controle de Mudas |
| **RF13-EL**  | Sistema de funcionamento offline com sincronização automática                    | Funcional     | Infraestrutura    |
| **RF14-EL**  | Captura automática de coordenadas GPS em todos os registros                      | Funcional     | Infraestrutura    |
| **RF16-EL**  | Validação automática de campos obrigatórios e condicionais                       | Funcional     | Infraestrutura    |
| **RF17-EL**  | Integração com ZS para recebimento automático dos dados coletados                | Funcional     | Integração        |
| **RF18-EL**  | Integração com GIZA para centralização e visualização dos dados                  | Funcional     | Integração        |
| **RNF01-EL** | Sistema deve funcionar offline em dispositivos móveis sem conexão à internet     | Não Funcional | Disponibilidade   |
| **RNF03-EL** | Interface responsiva otimizada para tablets e smartphones Android/iOS            | Não Funcional | Usabilidade       |
| **RNF07-EL** | Interface intuitiva que não exija treinamento extensivo dos usuários             | Não Funcional | Usabilidade       |
| **RNF10-EL** | Criptografia de dados durante armazenamento e transmissão                        | Não Funcional | Segurança         |

### Prioridade 2 - Alta

| **ID**       | **Descrição**                                                                 | **Tipo**      | **Categoria**        |
| ------------ | ----------------------------------------------------------------------------- | ------------- | -------------------- |
| **RF08-EL**  | Sistema de favoritar fotos importantes para inclusão automática em relatórios | Funcional     | Coleta de Dados      |
| **RF11-EL**  | Cálculo automático de médias de altura e diâmetro por espécie                 | Funcional     | Controle de Mudas    |
| **RF12-EL**  | Histórico de medições com comparação temporal                                 | Funcional     | Controle de Mudas    |
| **RF15-EL**  | Backup automático local de dados com indicador de status de sincronização     | Funcional     | Infraestrutura       |
| **RF19-EL**  | Sincronização automática com Google Drive para organização de fotos           | Funcional     | Integração           |
| **RF21-EL**  | Interface de visualização com tabela filtrável para dados do viveiro          | Funcional     | Visualização         |
| **RF22-EL**  | Filtros avançados por data, atividade, responsável e espécie                  | Funcional     | Visualização         |
| **RF31-EL**  | Geração automática de relatórios mensais no template padrão da Eletronorte    | Funcional     | Dashboard/Relatórios |
| **RF32-EL**  | Inserção automática de fotos favoritadas nos campos apropriados do relatório  | Funcional     | Dashboard/Relatórios |
| **RF35-EL**  | Exportação de dados de mudas para Excel com formatação para tabelas dinâmicas | Funcional     | Dashboard/Relatórios |
| **RNF02-EL** | Sincronização automática em até 5 minutos após conectar à internet            | Não Funcional | Performance          |
| **RNF05-EL** | Tempo de resposta inferior a 3 segundos para todas as operações               | Não Funcional | Performance          |
| **RNF09-EL** | Backup automático de dados a cada 24 horas                                    | Não Funcional | Confiabilidade       |
| **RNF11-EL** | Sistema de autenticação segura com controle de sessão                         | Não Funcional | Segurança            |

### Prioridade 3 - Média

| **ID**       | **Descrição**                                                                    | **Tipo**      | **Categoria**        |
| ------------ | -------------------------------------------------------------------------------- | ------------- | -------------------- |
| **RF20-EL**  | Análise de viabilidade de integração com sistema Mata Nativa                     | Funcional     | Integração           |
| **RF23-EL**  | Busca textual em observações e campos de texto livre                             | Funcional     | Visualização         |
| **RF24-EL**  | Sistema de visualização de fotos por registro com download individual            | Funcional     | Visualização         |
| **RF25-EL**  | Download de fotos em lote (favoritas e por filtros)                              | Funcional     | Visualização         |
| **RF33-EL**  | Interface de edição e customização do relatório antes do envio                   | Funcional     | Dashboard/Relatórios |
| **RF34-EL**  | Exportação de relatórios                                                         | Funcional     | Dashboard/Relatórios |
| **RF36-EL**  | Exportação de coordenadas geográficas para planilhas                             | Funcional     | Dashboard/Relatórios |
| **RF37-EL**  | Sistema de edição controlada de registros via GIZA                               | Funcional     | Gestão               |
| **RNF04-EL** | Suporte para armazenamento local de até 1000 registros offline                   | Não Funcional | Performance          |
| **RNF06-EL** | Compressão automática de fotos para otimizar armazenamento (máximo 5MB por foto) | Não Funcional | Performance          |
| **RNF08-EL** | Funcionamento com conectividade 3G ou superior quando online                     | Não Funcional | Compatibilidade      |
| **RNF12-EL** | Resolução automática de conflitos durante sincronização                          | Não Funcional | Confiabilidade       |
| **RNF13-EL** | Disponibilidade de 99% durante horário comercial                                 | Não Funcional | Confiabilidade       |

### Prioridade 4 - Baixa (Dashboards e Funcionalidades Avançadas)

| **ID**       | **Descrição**                                                 | **Tipo**      | **Categoria**        |
| ------------ | ------------------------------------------------------------- | ------------- | -------------------- |
| **RF26-EL**  | Calendário de atividades com indicadores de status            | Funcional     | Visualização         |
| **RF27-EL**  | Dashboard com gráficos de crescimento de mudas por espécie    | Funcional     | Dashboard/Relatórios |
| **RF28-EL**  | Dashboard com indicadores de taxa de mortalidade e replantio  | Funcional     | Dashboard/Relatórios |
| **RF29-EL**  | Dashboard com métricas de irrigação e adubação                | Funcional     | Dashboard/Relatórios |
| **RF30-EL**  | Dashboard com indicadores de pragas e doenças identificadas   | Funcional     | Dashboard/Relatórios |
| **RNF14-EL** | Suporte para múltiplos dispositivos simultâneos por usuário   | Não Funcional | Escalabilidade       |
| **RNF15-EL** | Arquitetura escalável para expansão futura de funcionalidades | Não Funcional | Escalabilidade       |

---

## Resumo por Prioridade

| **Prioridade** | **Funcionalidade Principal**                       | **Quantidade de Requisitos** | **% do Total** |
| -------------- | -------------------------------------------------- | ---------------------------- | -------------- |
| **Crítica**    | Coleta de dados e funcionalidades essenciais       | 18                           | 48.6%          |
| **Alta**       | Controle de mudas e relatórios básicos             | 14                           | 37.8%          |
| **Média**      | Funcionalidades complementares e performance       | 13                           | 35.1%          |
| **Baixa**      | Dashboards avançados e funcionalidades secundárias | 7                            | 18.9%          |

### Distribuição por Categoria (Prioridade Crítica e Alta)

| **Categoria**                 | **Quantidade** | **% MVP+Alta** |
| ----------------------------- | -------------- | -------------- |
| **Coleta de Dados**           | 8              | 25.0%          |
| **Controle de Mudas**         | 4              | 12.5%          |
| **Infraestrutura**            | 3              | 9.4%           |
| **Integração**                | 3              | 9.4%           |
| **Visualização**              | 2              | 6.3%           |
| **Dashboard/Relatórios**      | 6              | 18.8%          |
| **Requisitos Não Funcionais** | 6              | 18.8%          |

---

## Justificativas de Priorização

### MVP (Prioridade Crítica)

- **Coleta de dados offline**: Core do sistema, substituindo o processo manual atual
- **Registros básicos**: Dados essenciais para operação diária do viveiro
- **Controle de mudas**: Funcionalidade principal específica da Eletronorte
- **Infraestrutura básica**: GPS, validação e funcionamento offline
- **Integração ZS/GIZA**: Essencial para funcionamento do ecossistema

### Alta Prioridade

- **Sistema de fotos**: Diferencial importante para relatórios
- **Cálculos automáticos**: Substituindo processos manuais do Mata Nativa
- **Relatórios automáticos**: Principal entrega para o cliente
- **Visualização básica**: Interface para validação e consulta

### Média Prioridade

- **Funcionalidades complementares**: Melhoram usabilidade mas não são essenciais
- **Performance e confiabilidade**: Importantes para produção
- **Edição de dados**: Funcionalidade de correção e ajustes

### Baixa Prioridade

- **Dashboards avançados**: Valor agregado mas não essencial para MVP
- **Escalabilidade**: Importante para crescimento futuro
- **Funcionalidades secundárias**: Nice-to-have para versões futuras
