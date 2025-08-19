# Elicitação de Requisitos - Due Diligence Ambiental

## Introdução

Este documento apresenta a elicitação de requisitos para o **Due Diligence Ambiental**, sistema destinado à centralização e automação do processo de avaliação de conformidade ambiental de empreendimentos. O objetivo é substituir a rotina atual descentralizada por uma solução integrada que garanta controle, rastreabilidade e padronização.

## Contexto

O Due Diligence Ambiental visa:

- **Centralizar o cadastro** de empreendimentos e documentação ambiental
- **Automatizar controle de prazos** com alertas e notificações
- **Padronizar relatórios** para clientes e órgãos reguladores
- **Eliminar retrabalho** através de integração e organização
- **Garantir rastreabilidade** completa de alterações e processos

## Metodologia de Elicitação

- **Análise do discovery** realizado com stakeholder Arlon Facyneck
- **Mapeamento de problemas** do processo atual descentralizado
- **Identificação de funcionalidades** críticas para automação
- **Definição de integrações** necessárias (ArcGIS, calendário, etc.)

---

## Requisitos Funcionais

| **ID**  | **Descrição**                                                           |
| ------- | ----------------------------------------------------------------------- |
| RF01-DD | Permitir cadastro centralizado de empreendimentos com dados básicos     |
| RF02-DD | Registrar informações do proprietário e responsável pelo acompanhamento |
| RF03-DD | Capturar endereço e localização geográfica com georreferenciamento      |
| RF04-DD | Gerenciar upload de documentos (licenças, laudos, pareceres, fotos)     |
| RF05-DD | Implementar versionamento automático de documentos carregados           |
| RF06-DD | Permitir categorização de documentos por tipo e finalidade              |
| RF07-DD | Registrar condicionantes legais e status de atendimento                 |
| RF08-DD | Gerar relatórios de checklist automáticos consolidados para clientes    |
| RF09-DD | Exportar relatórios automaticamente em formato PDF                      |
| RF10-DD | Exibir tabela filtrável com todos os empreendimentos                    |
| RF11-DD | Apresentar cards organizados por status para visão rápida               |
| RF12-DD | Permitir funcionamento offline em atividades de campo                   |
| RF13-DD | Sincronizar dados automaticamente quando conectado                      |
| RF14-DD | Implementar busca avançada por múltiplos critérios                      |
| RF15-DD | Permitir filtros                                                        |
| RF16-DD | Manter log completo de alterações com usuário e timestamp               |

---

## Requisitos Não Funcionais

| **ID**   | **Descrição**                                                     |
| -------- | ----------------------------------------------------------------- |
| RNF01-DD | Interface responsiva para navegador e dispositivos móveis         |
| RNF02-DD | Suporte a navegadores Chrome, Firefox, Safari e Edge              |
| RNF03-DD | Compatibilidade com Android e iOS para aplicativo móvel           |
| RNF04-DD | Tempo de carregamento inferior a 3 segundos para telas principais |
| RNF05-DD | Suporte a 200+ usuários simultâneos                               |
| RNF06-DD | Disponibilidade de 99.5% durante horário comercial                |
| RNF07-DD | Backup automático diário com retenção de 30 dias                  |
| RNF08-DD | Criptografia de dados em trânsito e em repouso                    |
| RNF09-DD | Autenticação integrada com Active Directory corporativo           |
| RNF10-DD | Controle de acesso baseado em perfis e permissões                 |
| RNF11-DD | Auditoria completa de todas as operações realizadas               |
| RNF12-DD | Capacidade de armazenamento de 10TB para documentos               |
| RNF13-DD | Suporte a arquivos PDF, DOC, XLS, JPG, PNG até 50MB cada          |
| RNF14-DD | Integração via API REST com sistemas externos                     |
| RNF15-DD | Conformidade com LGPD para proteção de dados pessoais             |

---

## Rastreabilidade

| **Origem**                     | **Stakeholder**      | **Justificativa**                                  |
| ------------------------------ | -------------------- | -------------------------------------------------- |
| Processo descentralizado       | Arlon Facyneck       | Necessidade de centralização e padronização        |
| Perda de prazos críticos       | Equipe técnica       | Automação de alertas e controle temporal           |
| Duplicação de informações      | Usuários finais      | Sistema integrado para eliminar retrabalho         |
| Dificuldade de rastreamento    | Auditoria/Compliance | Histórico completo e rastreabilidade de alterações |
| Checagem manual de pendências  | Analistas            | Automação de acompanhamento e status               |
| Relatórios manuais demorados   | Gestores             | Geração automática de relatórios padronizados      |
| Falta de integração geográfica | Equipe de campo      | Mapa interativo e coleta georreferenciada          |

---

## Dependências Técnicas

- **Sistema de autenticação** integrado com Active Directory
- **Serviço de geolocalização** para mapeamento e coordenadas
- **API de integração** com ArcGIS Survey123
- **Serviço de calendário** para alertas e lembretes
- **Sistema de notificações** push para dispositivos móveis
- **Servidor de backup** para armazenamento seguro
- **API de geração** de PDF para relatórios

---

## Considerações de Implementação

### Priorizações Sugeridas

1. **Alta Prioridade**: RF01-DD a RF13-DD (cadastro, documentos, controle de prazos, relatórios básicos)
2. **Média Prioridade**: RF14-DD a RF23-DD (exportações, integrações, modo offline)
3. **Baixa Prioridade**: RF24-DD a RF30-DD (funcionalidades avançadas, dashboard executivo)

### Integrações Críticas

- **ArcGIS Survey123**: Para coleta estruturada em campo
- **Active Directory**: Para autenticação corporativa
- **Calendário corporativo**: Para sincronização de prazos
- **Sistema de backup**: Para garantia de dados

### Riscos Identificados

- **Complexidade de migração**: Dados existentes em planilhas separadas
- **Adoção pelos usuários**: Mudança de processo estabelecido
- **Integração geográfica**: Dependência de serviços externos
- **Conformidade regulatória**: Atendimento a múltiplos órgãos ambientais

---

## Casos de Uso Principais

### UC01: Cadastrar Novo Empreendimento

- **Ator**: Analista ambiental
- **Descrição**: Registrar novo empreendimento com dados básicos e localização
- **Requisitos**: RF01-DD, RF02-DD, RF03-DD

### UC02: Controlar Prazos de Licenças

- **Ator**: Responsável técnico
- **Descrição**: Monitorar vencimentos e receber alertas automáticos
- **Requisitos**: RF08-DD, RF09-DD, RF16-DD

### UC03: Gerar Relatório para Cliente

- **Ator**: Gestor de projeto
- **Descrição**: Emitir relatório consolidado para apresentação
- **Requisitos**: RF12-DD, RF15-DD, RF29-DD

### UC04: Coletar Dados em Campo

- **Ator**: Técnico de campo
- **Descrição**: Usar aplicativo móvel offline para coleta
- **Requisitos**: RF21-DD, RF22-DD, RF23-DD

---

## Próximos Passos

1. **Validação** dos requisitos com stakeholders
2. **Priorização** detalhada por valor de negócio
3. **Análise técnica** de viabilidade das integrações
4. **Modelagem** das histórias de usuário
5. **Definição** de critérios de aceitação
6. **Planejamento** de sprints de desenvolvimento
