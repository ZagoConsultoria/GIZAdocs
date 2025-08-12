# Histórias de Usuário - Módulo Recursos Hídricos (304)

## Introdução
Durante o processo de elicitação de requisitos para o módulo **Recursos Hídricos (304)**, foram identificadas necessidades relacionadas à coleta digital de dados de campo, organização de evidências, processamento de resultados laboratoriais e automação de relatórios. Com base nos requisitos elicitados, estas histórias de usuário descrevem, de forma clara e objetiva, as funcionalidades que o sistema deve oferecer.

## Objetivo
Apresentar as histórias de usuário que orientarão o desenvolvimento incremental do módulo Recursos Hídricos, garantindo entregas de valor progressivas e a substituição de processos manuais por automação.

---

## Histórias de Usuário

---

# [US01-304] - Coletar dados de campo via ZS {#us01-304}

### Tabela 1: História de Usuário – Coletar dados de campo via ZS

| Item                         | Descrição                                                                                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-304                                                                                                                                               |
| Tema                         | Coleta digital de dados de campo                                                                                                                      |
| Descrição                    | Eu, como técnico de campo, desejo registrar dados de campo diretamente no ZS, substituindo fichas manuais em papel, para garantir padronização e agilidade no processo de coleta. |
| Critérios de Aceitação       | - Formulário digital disponível no ZS.<br>- Captura de foto e metadados (data, hora, GPS).<br>- Funcionamento offline com armazenamento local.<br>- Campos obrigatórios sinalizados. |
| Prioridade Usuário           | Alta                                                                                                                                                  |
| Status                       | Validada                                                                                                                                              |
| Rastreabilidade              | RF01-304                                                                                                                                              |

---

# [US02-304] - Organizar fotos automaticamente {#us02-304}

### Tabela 2: História de Usuário – Organizar fotos automaticamente

| Item                         | Descrição                                                                                                                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US02-304                                                                                                                                                              |
| Tema                         | Organização automática de fotos                                                                                                                                        |
| Descrição                    | Eu, como técnico de campo, desejo que as fotos capturadas sejam organizadas automaticamente em pastas por ponto de coleta no sistema, para facilitar a gestão e consulta posterior. |
| Critérios de Aceitação       | - Fotos vinculadas ao ponto de coleta correto.<br>- Estrutura de pastas gerada automaticamente.<br>- Associação de metadados (data, hora, GPS).<br>- Feedback de sucesso ao usuário. | 
| Prioridade Usuário           | Alta                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                            |
| Rastreabilidade              | RF02-304                                                                                                                                                            |

---

# [US03-304] - Importar resultados de laboratório {#us03-304}

### Tabela 3: História de Usuário – Importar resultados de laboratório

| Item                         | Descrição                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-304                                                                                                                                                         |
| Tema                         | Processamento automático de PDFs laboratoriais                                                                                                                  |
| Descrição                    | Eu, como analista de dados, desejo importar automaticamente resultados de laboratório em formato PDF e extrair parâmetros para tabelas no sistema, para eliminar processos manuais de digitação. |
| Critérios de Aceitação       | - PDF carregado e processado com sucesso.<br>- Parâmetros extraídos e tabulados.<br>- Validação de valores dentro de faixas esperadas.<br>- Notificação de erros de importação. | 
| Prioridade Usuário           | Alta                                                                                                                                                           |
| Status                       | Validada                                                                                                                                                       |
| Rastreabilidade              | RF03-304                                                                                                                                                       |

---

# [US04-304] - Gerar tabelas comparativas {#us04-304}

### Tabela 4: História de Usuário – Gerar tabelas comparativas

| Item                         | Descrição                                                                                                                                                                                                                                                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-304                                                                                                                                                                                                                                                                  |
| Tema                         | Comparação automática de parâmetros                                                                                                                                                                                                                                        |
| Descrição                    | Eu, como analista de relatórios, desejo gerar tabelas comparativas de parâmetros em diferentes campanhas e em relação à campanha de background, para facilitar a análise de tendências sem manipulação manual de dados.                                                   |
| Critérios de Aceitação       | - Tabelas geradas para campanhas selecionadas.<br>- Inclusão de campanha de background.<br>- Destaque de variações percentuais.<br>- Exportação de tabela pronta para visualização.                                                                                         | 
| Prioridade Usuário           | Alta                                                                                                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                                                                                                  |
| Rastreabilidade              | RF04-304                                                                                                                                                                                                                                                                  |

---

# [US05-304] - Gerar relatórios automáticos {#us05-304}

### Tabela 5: História de Usuário – Gerar relatórios automáticos

| Item                         | Descrição                                                                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-304                                                                                                                                                                                                       |
| Tema                         | Relatórios automáticos no GISA                                                                                                                                                                                  |
| Descrição                    | Eu, como coordenador técnico, desejo gerar relatórios automáticos no GISA contendo gráficos, tabelas e indicadores, para ter uma visão consolidada dos resultados sem necessidade de montagem manual de documentos. |
| Critérios de Aceitação       | - Relatório gerado via clique único.<br>- Inclusão de gráficos de parâmetros.<br>- Tabelas formatadas e indicadores destacados.<br>- Disponível para exportação.                                                 | 
| Prioridade Usuário           | Alta                                                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                                                        |
| Rastreabilidade              | RF05-304                                                                                                                                                                                                        |

---

# [US06-304] - Exportar relatórios consolidados {#us06-304}

### Tabela 6: História de Usuário – Exportar relatórios consolidados

| Item                         | Descrição                                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-304                                                                                                                                                                              |
| Tema                         | Exportação de relatórios em PDF e Excel                                                                                                                                              |
| Descrição                    | Eu, como gestor de projetos, desejo exportar relatórios consolidados em formatos PDF e Excel com formatação adequada, para compartilhar com stakeholders externos e facilitar a tomada de decisão. |
| Critérios de Aceitação       | - Opção para PDF e Excel.<br>- Layout conforme padrão organizacional.<br>- Inclusão de sumário e legendas.<br>- Compatibilidade com softwares de escritório.                          |
| Prioridade Usuário           | Alta                                                                                                                                                                                  |
| Status                       | Validada                                                                                                                                                                              |
| Rastreabilidade              | RF06-304                                                                                                                                                                              |