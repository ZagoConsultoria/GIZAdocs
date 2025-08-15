# Elicitação de Requisitos - Visão Analítica de Tecnologia

## Introdução

Este documento apresenta a elicitação de requisitos para a **Visão Analítica de Tecnologia**, sistema destinado à centralização e análise de indicadores de produto para as plataformas GIZA e ZS. O objetivo é substituir planilhas espalhadas por uma solução confiável e integrada de Business Intelligence.

## Contexto

A visão analítica de tecnologia visa:

- **Centralizar indicadores** de produto em sistema único
- **Aumentar confiabilidade** dos dados coletados
- **Substituir limitações** do Power BI atual
- **Automatizar coleta** de métricas de uso
- **Fornecer insights** para melhoria contínua dos produtos

## Metodologia de Elicitação

- **Análise de problemas** das soluções atuais em planilhas
- **Identificação de limitações** do Power BI
- **Definição de métricas** críticas de produto
- **Mapeamento de fontes** de dados existentes

---

## Requisitos Funcionais

| **ID**    | **Descrição**                                                             |
| --------- | ------------------------------------------------------------------------- |
| RF01-TN | Implementar botão "Enviar Feedback" em todas as páginas e módulos do GIZA |
| RF02-TN | Coletar NPS automaticamente sem interferência externa                     |
| RF03-TN | Rastrear usuários únicos ativos por módulo baseado nos logs do GIZA       |
| RF04-TN | Calcular e exibir distribuição de uso por funcionalidade                  |
| RF05-TN | Monitorar taxa de sucesso de fluxos críticos de trabalho                  |
| RF06-TN | Registrar abandono e conclusão de tarefas automaticamente                 |
| RF07-TN | Capturar tempo de conclusão de tarefas no ZS como metadado                |
| RF08-TN | Calcular tempo líquido excluindo pausas e interrupções                    |
| RF09-TN | Calcular relação DAU/MAU (frequência de uso) automaticamente              |
| RF10-TN | Exibir métricas de aderência do produto em percentual                     |
| RF11-TN | Migrar dados de planilhas existentes via ETL automatizado                 |
| RF12-TN | Preservar histórico de dados durante migração                             |
| RF13-TN | Fornecer dashboard unificado para visualização de todos os KPIs           |
| RF14-TN | Permitir filtros por período, módulo e usuário                            |
| RF15-TN | Exportar relatórios em múltiplos formatos                                 |
| RF16-TN | Configurar alertas para métricas críticas                                 |

---

## Requisitos Não Funcionais

| **ID**     | **Descrição**                                                      |
| ---------- | ------------------------------------------------------------------ |
| RNF01-TN | Processamento assíncrono sem impacto na performance do GIZA        |
| RNF02-TN | Tempo de resposta inferior a 2 segundos para dashboards            |
| RNF03-TN | Suporte a 1000+ usuários simultâneos sem degradação                |
| RNF04-TN | SLA de 99.5% de uptime para disponibilidade dos dados              |
| RNF05-TN | Backup automático diário com recovery em menos de 1 hora           |
| RNF06-TN | Anonização de dados pessoais sensíveis conforme LGPD               |
| RNF07-TN | Criptografia em trânsito e repouso para segurança dos dados        |
| RNF08-TN | Auditoria de acesso aos dados para compliance                      |
| RNF09-TN | Arquitetura horizontal escalável para crescimento                  |
| RNF10-TN | Otimização automática de queries para performance                  |
| RNF11-TN | Interface intuitiva com tempo de aprendizado inferior a 30 minutos |
| RNF12-TN | Suporte responsivo a diferentes dispositivos                       |

---

## Rastreabilidade

| **Origem**            | **Stakeholder**   | **Justificativa**                              |
| --------------------- | ----------------- | ---------------------------------------------- |
| Problemas atuais      | Equipe de Produto | Necessidade de centralização e confiabilidade  |
| Limitações Power BI   | Analistas de BI   | Busca por solução mais robusta e integrada     |
| Métricas de produto   | Product Managers  | Necessidade de insights para tomada de decisão |
| Logs existentes       | Equipe de TI      | Aproveitamento da infraestrutura atual         |
| Feedback dos usuários | Usuários finais   | Melhoria contínua baseada em dados reais       |

---

## Dependências Técnicas

- **GIZA**: Sistema principal onde serão implementados os coletores
- **ZS (Zago Survey)**: Fonte de dados de tempo de conclusão de tarefas
- **Logs do GIZA**: Base para métricas de usuários ativos e navegação
- **Power BI atual**: Sistema a ser substituído gradualmente
- **Planilhas existentes**: Fontes de dados para migração inicial

---

## Considerações de Implementação

### Priorizações Sugeridas

1. **Alta Prioridade**: RF01-TECH, RF02-TECH, RF03-TECH, RF13-TN (funcionalidades básicas de coleta e visualização)
2. **Média Prioridade**: RF04-TECH, RF05-TECH, RF09-TECH, RF11-TN (métricas avançadas e migração)
3. **Baixa Prioridade**: RF15-TECH, RF16-TN (funcionalidades complementares)

### Riscos Identificados

- **Volume de dados**: Logs extensos podem impactar performance se não otimizados
- **Migração complexa**: Dados espalhados em planilhas podem ter inconsistências
- **Adoção do usuário**: Necessário treinamento para nova interface
- **Privacidade**: Coleta de dados de uso deve respeitar LGPD

---

## Próximos Passos

1. **Validação** dos requisitos com stakeholders
2. **Priorização** detalhada dos requisitos
3. **Modelagem** das histórias de usuário
4. **Definição de critérios** de aceitação
