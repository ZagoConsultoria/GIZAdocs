# Histórias de Usuário - Módulo Due Diligence Ambiental

## Introdução

Durante o processo de elicitação de requisitos para o módulo **Due Diligence Ambiental**, foram identificadas diversas necessidades relacionadas à centralização do processo de avaliação de conformidade ambiental, gestão documental integrada e automação de relatórios. Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de due diligence ambiental.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos analistas ambientais, coordenadores de projeto e gestores, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

---

## Histórias de Usuário

---

# [US01-DD] - Cadastrar novo empreendimento {#us01-dd}

### Tabela 1: História de Usuário – Cadastrar novo empreendimento

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-DD                                                                                                                                                                                      |
| Tema                         | Cadastrar novo empreendimento                                                                                                                                                                |
| Descrição                    | Eu, como analista ambiental, desejo cadastrar um novo empreendimento com dados básicos para centralizar as informações de due diligence de forma padronizada.                                |
| Critérios de Aceitação       | - Deve haver formulário de cadastro acessível.<br>- Sistema deve capturar dados básicos do empreendimento.<br>- Validação de campos obrigatórios.<br>- Confirmação de cadastro com ID único. |
| Prioridade Usuário           | Alta                                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF01-DD                                                                                                                                                                                      |

---

# [US02-DD] - Registrar informações do proprietário {#us02-dd}

### Tabela 2: História de Usuário – Registrar informações do proprietário

| Item                         | Descrição                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-DD                                                                                                                                                                           |
| Tema                         | Registrar informações do proprietário                                                                                                                                             |
| Descrição                    | Eu, como analista ambiental, desejo registrar informações do proprietário e responsável pelo acompanhamento para manter contatos organizados e rastreáveis.                       |
| Critérios de Aceitação       | - Campos para dados do proprietário disponíveis.<br>- Registro do responsável pelo acompanhamento.<br>- Validação de formatos de contato.<br>- Histórico de responsáveis mantido. |
| Prioridade Usuário           | Alta                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                          |
| Rastreabilidade              | RF02-DD                                                                                                                                                                           |

---

# [US03-DD] - Capturar localização geográfica {#us03-dd}

### Tabela 3: História de Usuário – Capturar localização geográfica

| Item                         | Descrição                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-DD                                                                                                                                                           |
| Tema                         | Capturar localização geográfica                                                                                                                                   |
| Descrição                    | Eu, como analista ambiental, desejo capturar endereço e localização geográfica com georreferenciamento para localizar precisamente os empreendimentos avaliados.  |
| Critérios de Aceitação       | - Campo de endereço com validação.<br>- Captura de coordenadas geográficas.<br>- Integração com mapas para visualização.<br>- Validação de coordenadas inseridas. |
| Prioridade Usuário           | Alta                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                          |
| Rastreabilidade              | RF03-DD                                                                                                                                                           |

---

# [US04-DD] - Fazer upload de documentos {#us04-dd}

### Tabela 4: História de Usuário – Fazer upload de documentos

| Item                         | Descrição                                                                                                                                                               |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-DD                                                                                                                                                                 |
| Tema                         | Fazer upload de documentos                                                                                                                                              |
| Descrição                    | Eu, como analista ambiental, desejo fazer upload de documentos (licenças, laudos, pareceres, fotos) para centralizar toda a documentação relacionada ao empreendimento. |
| Critérios de Aceitação       | - Interface de upload intuitiva.<br>- Suporte a múltiplos tipos de arquivo.<br>- Validação de tamanho e formato.<br>- Organização por empreendimento.                   |
| Prioridade Usuário           | Alta                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                |
| Rastreabilidade              | RF04-DD                                                                                                                                                                 |

---

# [US05-DD] - Usar versionamento de documentos {#us05-dd}

### Tabela 5: História de Usuário – Usar versionamento de documentos

| Item                         | Descrição                                                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-DD                                                                                                                                                   |
| Tema                         | Usar versionamento de documentos                                                                                                                          |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema implemente versionamento automático de documentos para manter histórico de alterações e atualizações.   |
| Critérios de Aceitação       | - Versionamento automático ao fazer upload.<br>- Histórico de versões acessível.<br>- Comparação entre versões disponível.<br>- Controle de versão ativa. |
| Prioridade Usuário           | Média                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                  |
| Rastreabilidade              | RF05-DD                                                                                                                                                   |

---

# [US06-DD] - Categorizar documentos {#us06-dd}

### Tabela 6: História de Usuário – Categorizar documentos

| Item                         | Descrição                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-DD                                                                                                                                                               |
| Tema                         | Categorizar documentos                                                                                                                                                |
| Descrição                    | Eu, como analista ambiental, desejo categorizar documentos por tipo e finalidade para organizar melhor a documentação e facilitar buscas específicas.                 |
| Critérios de Aceitação       | - Sistema de categorias predefinidas disponível.<br>- Possibilidade de criar novas categorias.<br>- Filtro por categoria funcional.<br>- Organização visual por tipo. |
| Prioridade Usuário           | Média                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                              |
| Rastreabilidade              | RF06-DD                                                                                                                                                               |

---

# [US07-DD] - Registrar condicionantes legais {#us07-dd}

### Tabela 7: História de Usuário – Registrar condicionantes legais

| Item                         | Descrição                                                                                                                                                       |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-DD                                                                                                                                                         |
| Tema                         | Registrar condicionantes legais                                                                                                                                 |
| Descrição                    | Eu, como analista ambiental, desejo registrar condicionantes legais e status de atendimento para acompanhar o cumprimento das exigências regulamentares.        |
| Critérios de Aceitação       | - Formulário para registro de condicionantes.<br>- Status de atendimento atualizável.<br>- Farol visual de cumprimento.<br>- Histórico de alterações de status. |
| Prioridade Usuário           | Alta                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                        |
| Rastreabilidade              | RF07-DD                                                                                                                                                         |

---

# [US08-DD] - Gerar relatórios de checklist {#us08-dd}

### Tabela 8: História de Usuário – Gerar relatórios de checklist

| Item                         | Descrição                                                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US08-DD                                                                                                                                                                                    |
| Tema                         | Gerar relatórios de checklist                                                                                                                                                              |
| Descrição                    | Eu, como coordenador de projeto, desejo gerar relatórios de checklist automáticos consolidados para clientes para padronizar entregas e agilizar processos.                                |
| Critérios de Aceitação       | - Geração automática de relatórios baseados no checklist.<br>- Template padronizado para clientes.<br>- Dados consolidados por empreendimento.<br>- Personalização por cliente disponível. |
| Prioridade Usuário           | Alta                                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                                   |
| Rastreabilidade              | RF08-DD                                                                                                                                                                                    |

---

# [US09-DD] - Exportar relatórios em PDF {#us09-dd}

### Tabela 9: História de Usuário – Exportar relatórios em PDF

| Item                         | Descrição                                                                                                                                                                |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US09-DD                                                                                                                                                                  |
| Tema                         | Exportar relatórios em PDF                                                                                                                                               |
| Descrição                    | Eu, como coordenador de projeto, desejo exportar relatórios automaticamente em formato PDF para compartilhar com clientes e órgãos de forma profissional.                |
| Critérios de Aceitação       | - Exportação automática em PDF funcional.<br>- Layout profissional e padronizado.<br>- Geração rápida (menos de 10 segundos).<br>- Download ou visualização disponíveis. |
| Prioridade Usuário           | Alta                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                 |
| Rastreabilidade              | RF09-DD                                                                                                                                                                  |

---

# [US10-DD] - Visualizar tabela filtrável {#us10-dd}

### Tabela 10: História de Usuário – Visualizar tabela filtrável

| Item                         | Descrição                                                                                                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-DD                                                                                                                                                                                |
| Tema                         | Visualizar tabela filtrável                                                                                                                                                            |
| Descrição                    | Eu, como gestor, desejo visualizar tabela filtrável com todos os empreendimentos para ter visão consolidada e facilitar análises comparativas.                                         |
| Critérios de Aceitação       | - Tabela com todos os empreendimentos exibida.<br>- Filtros por múltiplos critérios disponíveis.<br>- Ordenação por colunas funcional.<br>- Performance adequada para grandes volumes. |
| Prioridade Usuário           | Alta                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                               |
| Rastreabilidade              | RF10-DD                                                                                                                                                                                |

---

# [US11-DD] - Visualizar cards por status {#us11-dd}

### Tabela 11: História de Usuário – Visualizar cards por status

| Item                         | Descrição                                                                                                                                                               |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-DD                                                                                                                                                                 |
| Tema                         | Visualizar cards por status                                                                                                                                             |
| Descrição                    | Eu, como gestor, desejo visualizar cards organizados por status para ter visão rápida do andamento dos empreendimentos e identificar prioridades.                       |
| Critérios de Aceitação       | - Cards visuais organizados por status.<br>- Cores diferenciadas por categoria de status.<br>- Informações resumidas em cada card.<br>- Navegação rápida para detalhes. |
| Prioridade Usuário           | Média                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                |
| Rastreabilidade              | RF11-DD                                                                                                                                                                 |

---

# [US12-DD] - Usar sistema offline {#us12-dd}

### Tabela 12: História de Usuário – Usar sistema offline

| Item                         | Descrição                                                                                                                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-DD                                                                                                                                                                    |
| Tema                         | Usar sistema offline                                                                                                                                                       |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema funcione offline em atividades de campo para coletar dados mesmo sem conexão com a internet.                             |
| Critérios de Aceitação       | - Funcionalidade offline para coleta de dados.<br>- Armazenamento local temporário.<br>- Interface responsiva em dispositivos móveis.<br>- Indicador de status de conexão. |
| Prioridade Usuário           | Alta                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                   |
| Rastreabilidade              | RF12-DD                                                                                                                                                                    |

---

# [US13-DD] - Sincronizar dados automaticamente {#us13-dd}

### Tabela 13: História de Usuário – Sincronizar dados automaticamente

| Item                         | Descrição                                                                                                                                                                |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US13-DD                                                                                                                                                                  |
| Tema                         | Sincronizar dados automaticamente                                                                                                                                        |
| Descrição                    | Eu, como analista ambiental, desejo que os dados sejam sincronizados automaticamente quando conectado para garantir integridade e atualização das informações coletadas. |
| Critérios de Aceitação       | - Sincronização automática ao detectar conexão.<br>- Resolução de conflitos de dados.<br>- Indicador de progresso da sincronização.<br>- Notificação de sucesso/erro.    |
| Prioridade Usuário           | Alta                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                 |
| Rastreabilidade              | RF13-DD                                                                                                                                                                  |

---

# [US14-DD] - Realizar busca avançada {#us14-dd}

### Tabela 14: História de Usuário – Realizar busca avançada

| Item                         | Descrição                                                                                                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US14-DD                                                                                                                                                            |
| Tema                         | Realizar busca avançada                                                                                                                                            |
| Descrição                    | Eu, como usuário do sistema, desejo implementar busca avançada por múltiplos critérios para localizar rapidamente empreendimentos e documentos específicos.        |
| Critérios de Aceitação       | - Busca por múltiplos campos simultaneamente.<br>- Filtros combinados disponíveis.<br>- Resultados relevantes e ordenados.<br>- Busca em texto completo funcional. |
| Prioridade Usuário           | Média                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                           |
| Rastreabilidade              | RF14-DD                                                                                                                                                            |

---

# [US15-DD] - Aplicar filtros no sistema {#us15-dd}

### Tabela 15: História de Usuário – Aplicar filtros no sistema

| Item                         | Descrição                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-DD                                                                                                                                                                          |
| Tema                         | Aplicar filtros no sistema                                                                                                                                                       |
| Descrição                    | Eu, como usuário do sistema, desejo aplicar filtros nas listagens para visualizar subconjuntos específicos de dados conforme necessidades de análise.                            |
| Critérios de Aceitação       | - Filtros por status, localização, responsável disponíveis.<br>- Filtros salvos para reutilização.<br>- Combinação de múltiplos filtros.<br>- Performance adequada na filtragem. |
| Prioridade Usuário           | Média                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                         |
| Rastreabilidade              | RF15-DD                                                                                                                                                                          |

---

# [US16-DD] - Acessar log de alterações {#us16-dd}

### Tabela 16: História de Usuário – Acessar log de alterações

| Item                         | Descrição                                                                                                                                                            |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-DD                                                                                                                                                              |
| Tema                         | Acessar log de alterações                                                                                                                                            |
| Descrição                    | Eu, como auditor/gestor, desejo acessar log completo de alterações com usuário e timestamp para garantir rastreabilidade e transparência em auditorias.              |
| Critérios de Aceitação       | - Log completo de todas as alterações registrado.<br>- Informações de usuário e timestamp.<br>- Filtro por período e usuário.<br>- Exportação do log para auditoria. |
| Prioridade Usuário           | Média                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                             |
| Rastreabilidade              | RF16-DD                                                                                                                                                              |
