# Histórias de Usuário - Visão Analítica de Tecnologia

## Introdução

Durante o processo de elicitação de requisitos para a **Visão Analítica de Tecnologia**, foram identificadas diversas necessidades relacionadas à centralização, coleta e análise de indicadores de produto para as plataformas GIZA e ZS. Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de monitoramento e análise de dados.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos stakeholders (Product Managers, Analistas de BI, Equipe de TI), as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

---

## Histórias de Usuário

---

# [US01-TN] - Coletar feedback via botão integrado {#us01-tn}

### Tabela 1: História de Usuário – Coletar feedback via botão integrado

| Item                         | Descrição                                                                                                                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-TN                                                                                                                                                                                                                                                          |
| Tema                         | Coletar feedback via botão integrado                                                                                                                                                                                                                             |
| Descrição                    | Eu, como usuário do GIZA, desejo ter um botão "Enviar Feedback" em todas as páginas para avaliar rapidamente minha experiência e contribuir com melhorias no sistema.                                                                                            |
| Critérios de Aceitação       | - Botão deve estar presente em todas as páginas do GIZA.<br>- Modal deve incluir escala NPS (0-10) e campo para comentários.<br>- Envio deve ser direto para dashboard sem intermediários.<br>- Sistema deve identificar automaticamente usuário e módulo atual. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                                                                                                         |
| Rastreabilidade              | RF01-TN, RF02-TN                                                                                                                                                                                                                                                 |

---

# [US02-TN] - Monitorar usuários ativos por módulo {#us02-tn}

### Tabela 2: História de Usuário – Monitorar usuários ativos por módulo

| Item                         | Descrição                                                                                                                                                                                                                                                                          |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-TN                                                                                                                                                                                                                                                                            |
| Tema                         | Monitorar usuários ativos por módulo                                                                                                                                                                                                                                               |
| Descrição                    | Eu, como Product Manager, desejo visualizar quantos usuários únicos estão ativos em cada módulo para entender a distribuição de uso e focar melhorias nas áreas mais utilizadas.                                                                                                   |
| Critérios de Aceitação       | - Sistema deve rastrear automaticamente login/logout por módulo.<br>- Dashboard deve exibir contagem de usuários únicos diários (DAU) e mensais (MAU).<br>- Dados devem ser segmentados por módulo/funcionalidade.<br>- Relatórios de distribuição de uso devem estar disponíveis. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                                                                                                                                           |
| Rastreabilidade              | RF03-TN, RF04-TN                                                                                                                                                                                                                                                                   |

---

# [US03-TN] - Acompanhar taxa de sucesso de tarefas {#us03-tn}

### Tabela 3: História de Usuário – Acompanhar taxa de sucesso de tarefas

| Item                         | Descrição                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US03-TN                                                                                                                                                                                                                                                                                                                                          |
| Tema                         | Acompanhar taxa de sucesso de tarefas                                                                                                                                                                                                                                                                                                            |
| Descrição                    | Eu, como Analista de BI, desejo monitorar o percentual de usuários que completam com sucesso fluxos críticos de trabalho para identificar pontos de melhoria na interface e processos.                                                                                                                                                           |
| Critérios de Aceitação       | - Sistema deve definir pontos de início e fim de cada fluxo crítico.<br>- Registro automático de abandono/conclusão deve ser implementado.<br>- Cálculo automático de taxa de sucesso deve estar disponível.<br>- Alertas para taxas abaixo de threshold definido devem ser configurados.<br>- Relatórios por fluxo e período devem ser gerados. |
| Prioridade Usuário           | Média                                                                                                                                                                                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                                                                                                                                                                                         |
| Rastreabilidade              | RF05-TN, RF06-TN                                                                                                                                                                                                                                                                                                                                 |

---

# [US04-TN] - Medir tempo de conclusão de tarefas {#us04-tn}

### Tabela 4: História de Usuário – Medir tempo de conclusão de tarefas

| Item                         | Descrição                                                                                                                                                                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-TN                                                                                                                                                                                                                                                                                                                          |
| Tema                         | Medir tempo de conclusão de tarefas                                                                                                                                                                                                                                                                                              |
| Descrição                    | Eu, como Product Manager, desejo medir o tempo médio que usuários levam para completar tarefas específicas no ZS e GIZA para quantificar ganhos de produtividade das melhorias implementadas.                                                                                                                                    |
| Critérios de Aceitação       | - Timestamp automático de início/fim de tarefa deve ser capturado.<br>- Cálculo de tempo líquido (excluindo pausas) deve ser implementado.<br>- Envio como metadado junto com formulários do ZS deve funcionar.<br>- Benchmark por tipo de tarefa deve estar disponível.<br>- Relatórios de evolução temporal devem ser gerados. |
| Prioridade Usuário           | Média                                                                                                                                                                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                                                                                                                                                                         |
| Rastreabilidade              | RF07-TN, RF08-TN                                                                                                                                                                                                                                                                                                                 |

---

# [US05-TN] - Visualizar métricas de aderência do produto {#us05-tn}

### Tabela 5: História de Usuário – Visualizar métricas de aderência do produto

| Item                         | Descrição                                                                                                                                                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US05-TN                                                                                                                                                                                                                                                                                    |
| Tema                         | Visualizar métricas de aderência do produto                                                                                                                                                                                                                                                |
| Descrição                    | Eu, como Product Manager, desejo visualizar a relação DAU/MAU (frequência de uso) para entender o quão integrado o GIZA está na rotina de trabalho dos usuários e identificar padrões de uso.                                                                                              |
| Critérios de Aceitação       | - Cálculo automático da relação DAU/MAU deve ser implementado.<br>- Visualização em percentual deve estar disponível.<br>- Comparação histórica deve ser possível.<br>- Segmentação por usuário/módulo deve ser oferecida.<br>- Alertas para quedas significativas devem ser configurados. |
| Prioridade Usuário           | Média                                                                                                                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                                                                                                                   |
| Rastreabilidade              | RF09-TN, RF10-TN                                                                                                                                                                                                                                                                           |

---

# [US06-TN] - Migrar dados de planilhas existentes {#us06-tn}

### Tabela 6: História de Usuário – Migrar dados de planilhas existentes

| Item                         | Descrição                                                                                                                                                                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-TN                                                                                                                                                                                                                                                                                                           |
| Tema                         | Migrar dados de planilhas existentes                                                                                                                                                                                                                                                                              |
| Descrição                    | Eu, como Analista de BI, desejo migrar todos os indicadores de planilhas espalhadas para o sistema GIZA para centralizar os dados e eliminar inconsistências das fontes atuais.                                                                                                                                   |
| Critérios de Aceitação       | - ETL automatizado das fontes existentes deve ser implementado.<br>- Validação de integridade dos dados deve ser realizada.<br>- Histórico deve ser preservado durante a migração.<br>- Interface unificada de consulta deve ser disponibilizada.<br>- Backup automático dos dados migrados deve ser configurado. |
| Prioridade Usuário           | Média                                                                                                                                                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                                                                                                                                                          |
| Rastreabilidade              | RF11-TN, RF12-TN                                                                                                                                                                                                                                                                                                  |

---

# [US07-TN] - Acessar dashboard unificado de KPIs {#us07-tn}

### Tabela 7: História de Usuário – Acessar dashboard unificado de KPIs

| Item                         | Descrição                                                                                                                                                                                                                                                                                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-TN                                                                                                                                                                                                                                                                                           |
| Tema                         | Acessar dashboard unificado de KPIs                                                                                                                                                                                                                                                               |
| Descrição                    | Eu, como stakeholder, desejo ter acesso a um dashboard único que consolide todos os indicadores de produto para facilitar a tomada de decisões baseada em dados centralizados.                                                                                                                    |
| Critérios de Aceitação       | - Visão consolidada de todos os KPIs deve estar disponível.<br>- Filtros por período, módulo e usuário devem ser implementados.<br>- Exportação de relatórios deve ser possível.<br>- Alertas configuráveis devem ser oferecidos.<br>- Acesso baseado em perfil de usuário deve ser implementado. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                                                                                                                                          |
| Rastreabilidade              | RF13-TN, RF14-TN, RF15-TN, RF16-TN                                                                                                                                                                                                                                                                |

---

## Considerações de Implementação

### Ordem Sugerida de Desenvolvimento

1. **Sprint 1**: US01-TN, US07-TN (Feedback integrado e dashboard básico)
2. **Sprint 2**: US02-TN, US06-TN (Monitoramento de usuários e migração de dados)
3. **Sprint 3**: US03-TN, US04-TN (Taxa de sucesso e tempo de conclusão)
4. **Sprint 4**: US05-TN (Métricas de aderência e refinamentos)

### Dependências Identificadas

- **US01-TN** é pré-requisito para coleta de feedback em tempo real
- **US06-TN** deve ser executada antes de **US07-TN** para ter dados históricos
- **US02-TN** é base para **US05-TN** (cálculo DAU/MAU)

### Critérios de Definição de Pronto

- Funcionalidade implementada e testada
- Interface validada com usuários finais
- Documentação técnica atualizada
- Métricas de performance dentro dos requisitos não funcionais
- Testes de segurança e privacidade aprovados
