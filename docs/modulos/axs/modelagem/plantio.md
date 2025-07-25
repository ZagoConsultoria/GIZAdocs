# Histórias de Usuário - Programa Plantio AXS

## Introdução

Este documento apresenta as histórias de usuário desenvolvidas a partir dos requisitos funcionais priorizados para o programa de monitoramento de plantio da AXS. Cada história segue o formato padrão "Como [persona], eu quero [funcionalidade] para que [benefício]" e inclui critérios de aceitação específicos.

## Objetivo

Traduzir os requisitos funcionais em histórias centradas no usuário, facilitando a compreensão das necessidades e orientando o desenvolvimento da solução de forma user-centric.

## Histórias de Usuário

# Histórias de Usuário - Programa Pré-Plantio AXS

## Introdução

Durante o processo de elicitação de requisitos para o programa de plantio da AXS, foram identificadas diversas necessidades relacionadas à coleta, organização e apresentação de dados de caracterização de plantio. Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de campo e escritório.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos usuários da AXS, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

# [US09-AXS] - Coletar dados de plantio via ZS {#us09-axs}

### Tabela 1: História de Usuário – Coletar dados de plantio via ZS

| Item                         | Descrição                                                                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US09-AXS                                                                                                                                                                                                              |
| Tema                         | Coletar dados de plantio via ZS                                                                                                                                                                                       |
| Descrição                    | Eu, como técnico de campo da AXS, desejo usar um formulário padronizado no ZS para coleta de dados de plantio para que eu possa coletar informações de forma consistente e organizada.                                |
| Critérios de Aceitação       | - Formulário deve conter campos específicos de caracterização de plantio.<br>- Interface deve ser intuitiva para uso em campo.<br>- Dados devem ser validados antes do envio.<br>- Formulário deve funcionar offline. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                  |
| Status                       | Validada                                                                                                                                                                                                              |
| Rastreabilidade              | RF09-AXS                                                                                                                                                                                                              |

# [US10-AXS] - Capturar GPS automaticamente {#us10-axs}

### Tabela 2: História de Usuário – Capturar GPS automaticamente

| Item                         | Descrição                                                                                                                                                                                                     |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-AXS                                                                                                                                                                                                      |
| Tema                         | Capturar GPS automaticamente                                                                                                                                                                                  |
| Descrição                    | Eu, como técnico de campo da AXS, desejo que as coordenadas GPS sejam capturadas automaticamente para cada ponto de plantio para que eu não precise inserir manualmente a localização e evite erros.          |
| Critérios de Aceitação       | - GPS deve ser capturado automaticamente ao iniciar coleta.<br>- Precisão mínima de 3 metros.<br>- Deve funcionar mesmo com sinal GPS fraco.<br>- Coordenadas devem ser salvas junto com os dados do plantio. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                                                      |
| Rastreabilidade              | RF10-AXS                                                                                                                                                                                                      |

# [US11-AXS] - Anexar fotos automaticamente {#us11-axs}

### Tabela 3: História de Usuário – Anexar fotos automaticamente

| Item                         | Descrição                                                                                                                                                                                                                 |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-AXS                                                                                                                                                                                                                  |
| Tema                         | Anexar fotos automaticamente                                                                                                                                                                                              |
| Descrição                    | Eu, como técnico de campo da AXS, desejo que as fotos sejam anexadas automaticamente ao GIZA e SharePoint para que eu não precise organizar manualmente as evidências fotográficas.                                       |
| Critérios de Aceitação       | - Fotos devem ser vinculadas automaticamente ao registro.<br>- Upload deve ocorrer quando houver conectividade.<br>- Fotos devem manter qualidade adequada para análise.<br>- Deve haver backup automático no SharePoint. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                                                  |
| Rastreabilidade              | RF11-AXS                                                                                                                                                                                                                  |

# [US12-AXS] - Utilizar sistema offline {#us12-axs}

### Tabela 4: História de Usuário – Utilizar sistema offline

| Item                         | Descrição                                                                                                                                                                                                                                           |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-AXS                                                                                                                                                                                                                                            |
| Tema                         | Utilizar sistema offline                                                                                                                                                                                                                            |
| Descrição                    | Eu, como técnico de campo da AXS, desejo trabalhar offline durante as coletas em áreas remotas para que eu não seja limitado pela falta de conectividade no campo.                                                                                  |
| Critérios de Aceitação       | - Sistema deve funcionar completamente offline.<br>- Dados devem ser sincronizados quando conectividade retornar.<br>- Deve haver indicador visual do status de conectividade.<br>- Não deve haver perda de dados durante transição online/offline. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                                                                                            |
| Rastreabilidade              | RF12-AXS                                                                                                                                                                                                                                            |

# [US13-AXS] - Armazenar dados com versionamento {#us13-axs}

### Tabela 5: História de Usuário – Armazenar dados com versionamento

| Item                         | Descrição                                                                                                                                                                                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US13-AXS                                                                                                                                                                                          |
| Tema                         | Armazenar dados com versionamento                                                                                                                                                                 |
| Descrição                    | Eu, como analista da AXS, desejo que os dados sejam armazenados em banco parametrizado com versionamento para que eu possa realizar análises temporais e manter histórico das informações.        |
| Critérios de Aceitação       | - Dados devem ser versionados automaticamente.<br>- Deve ser possível consultar dados por período.<br>- Estrutura deve permitir análises comparativas.<br>- Backup automático deve ser realizado. |
| Prioridade Usuário           | Alta                                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                                          |
| Rastreabilidade              | RF13-AXS                                                                                                                                                                                          |

# [US14-AXS] - Integração com sistemas {#us14-axs}

### Tabela 6: História de Usuário – Integração com sistemas

| Item                         | Descrição                                                                                                                                                                                                                 |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US14-AXS                                                                                                                                                                                                                  |
| Tema                         | Integração com sistemas                                                                                                                                                                                                   |
| Descrição                    | Eu, como usuário da AXS, desejo que o sistema integre com ZS, GIZA e SharePoint para que eu tenha acesso centralizado a todas as informações.                                                                             |
| Critérios de Aceitação       | - Dados do ZS devem aparecer automaticamente no GIZA.<br>- Integração deve ser transparente para o usuário.<br>- Sincronização deve ser em tempo real quando online.<br>- Deve haver log de sincronização para auditoria. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                                                  |
| Rastreabilidade              | RF14-AXS                                                                                                                                                                                                                  |

# [US15-AXS] - Correção automática de textos {#us15-axs}

### Tabela 7: História de Usuário – Correção automática de textos

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-AXS                                                                                                                                                                                     |
| Tema                         | Correção automática de textos                                                                                                                                                                |
| Descrição                    | Eu, como analista da AXS, desejo correção automática de textos por IA nos dados coletados para que eu não precise revisar manualmente erros ortográficos.                                    |
| Critérios de Aceitação       | - Correção deve ter precisão superior a 95%.<br>- Usuário deve poder aceitar ou rejeitar correções.<br>- Deve preservar termos técnicos específicos.<br>- Log de correções deve ser mantido. |
| Prioridade Usuário           | Média                                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF15-AXS                                                                                                                                                                                     |

# [US16-AXS] - Visualizar dashboard {#us16-axs}

### Tabela 8: História de Usuário – Visualizar dashboard

| Item                         | Descrição                                                                                                                                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-AXS                                                                                                                                                                                                |
| Tema                         | Visualizar dashboard                                                                                                                                                                                    |
| Descrição                    | Eu, como gestor da AXS, desejo visualizar dados de plantio em dashboard no GIZA para que eu possa acompanhar o progresso e identificar padrões.                                                         |
| Critérios de Aceitação       | - Dashboard deve mostrar métricas principais.<br>- Visualizações devem ser interativas.<br>- Filtros por período e localização devem estar disponíveis.<br>- Dados devem ser atualizados em tempo real. |
| Prioridade Usuário           | Média                                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                                                |
| Rastreabilidade              | RF16-AXS                                                                                                                                                                                                |

# [US17-AXS] - Download de fotos {#us17-axs}

### Tabela 9: História de Usuário – Download de fotos

| Item                         | Descrição                                                                                                                                                                                           |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US17-AXS                                                                                                                                                                                            |
| Tema                         | Download de fotos                                                                                                                                                                                   |
| Descrição                    | Eu, como usuário da AXS, desejo fazer download de fotos por lote ou individual para que eu possa acessar facilmente as evidências coletadas.                                                        |
| Critérios de Aceitação       | - Download individual deve ser em um clique.<br>- Download por lote deve permitir seleção múltipla.<br>- Fotos devem manter resolução original.<br>- Deve haver indicador de progresso do download. |
| Prioridade Usuário           | Média                                                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                                                            |
| Rastreabilidade              | RF17-AXS                                                                                                                                                                                            |

# [US18-AXS] - Tabela filtrável e exportável {#us18-axs}

### Tabela 10: História de Usuário – Tabela filtrável e exportável

| Item                         | Descrição                                                                                                                                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US18-AXS                                                                                                                                                                                                |
| Tema                         | Tabela filtrável e exportável                                                                                                                                                                           |
| Descrição                    | Eu, como analista da AXS, desejo visualizar dados em tabela filtrável e exportável para que eu possa realizar análises detalhadas e compartilhar informações.                                           |
| Critérios de Aceitação       | - Tabela deve permitir filtros por múltiplos campos.<br>- Exportação deve suportar Excel e CSV.<br>- Dados exportados devem manter formatação.<br>- Filtros aplicados devem ser mantidos na exportação. |
| Prioridade Usuário           | Média                                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                                                |
| Rastreabilidade              | RF18-AXS                                                                                                                                                                                                |

# [US19-AXS] - Gerar relatórios automatizados {#us19-axs}

### Tabela 11: História de Usuário – Gerar relatórios automatizados

| Item                         | Descrição                                                                                                                                                                     |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US19-AXS                                                                                                                                                                      |
| Tema                         | Gerar relatórios automatizados                                                                                                                                                |
| Descrição                    | Eu, como gestor da AXS, desejo gerar relatórios automatizados conforme padrão AXS para que eu tenha documentação padronizada sem trabalho manual.                             |
| Critérios de Aceitação       | - Relatório deve seguir template padrão AXS.<br>- Geração deve ser em um clique.<br>- Dados devem ser atualizados automaticamente.<br>- Relatório deve ser exportável em PDF. |
| Prioridade Usuário           | Alta                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                      |
| Rastreabilidade              | RF19-AXS                                                                                                                                                                      |

# [US20-AXS] - Editar dados controladamente {#us20-axs}

### Tabela 12: História de Usuário – Editar dados controladamente

| Item                         | Descrição                                                                                                                                                                                                           |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US20-AXS                                                                                                                                                                                                            |
| Tema                         | Editar dados controladamente                                                                                                                                                                                        |
| Descrição                    | Eu, como supervisor da AXS, desejo editar dados coletados de forma controlada via GIZA para que eu possa corrigir informações quando necessário.                                                                    |
| Critérios de Aceitação       | - Edições devem ser registradas com log de auditoria.<br>- Apenas usuários autorizados podem editar.<br>- Versões anteriores devem ser preservadas.<br>- Notificação deve ser enviada para stakeholders relevantes. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                                                                            |
| Rastreabilidade              | RF20-AXS                                                                                                                                                                                                            |
