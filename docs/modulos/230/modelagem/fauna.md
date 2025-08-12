# Histórias de Usuário - Módulo Fauna

## Introdução

Com base no discovery realizado para o módulo **Fauna**, estas histórias de usuário descrevem, do ponto de vista dos técnicos de campo e coordenadores, as funcionalidades desejadas para coleta, armazenamento, integração e geração de relatórios de dados de fauna.

## Objetivo

Apresentar as histórias de usuário que guiarão o desenvolvimento incremental do módulo Fauna, assegurando a entrega de valor desde as necessidades mais críticas.

---

## Histórias de Usuário

---

# [US01-230] - Coletar dados de fauna atropelada via ZS {#us01-230}

### Tabela 1: História de Usuário – Coletar dados de fauna atropelada via ZS

| Item                         | Descrição                                                                                                                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-230                                                                                                                                                                   |
| Tema                         | Coletar dados de fauna atropelada via ZS com GPS e fotos                                                                                                                   |
| Descrição                    | Eu, como técnico de campo, desejo registrar dados de fauna atropelada diretamente no ZS, com captura automática de coordenadas e fotos, para substituir processos manuais. |
| Critérios de Aceitação       | - Formulário digital para registro de atropelamentos.<br>- Captura automática de data, hora e GPS.<br>- Upload automático de fotos.<br>- Funcionamento offline.            |
| Prioridade Usuário           | Alta                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                   |
| Rastreabilidade              | RF01-230                                                                                                                                                                   |

---

# [US02-230] - Integrar upload automático de fotos georreferenciadas {#us02-230}

### Tabela 2: História de Usuário – Integrar upload automático de fotos georreferenciadas

| Item                         | Descrição                                                                                                                                                               |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-230                                                                                                                                                                |
| Tema                         | Integrar upload automático de fotos georreferenciadas ao GIZA e SharePoint                                                                                              |
| Descrição                    | Eu, como técnico de campo, desejo que as fotos capturadas sejam enviadas automaticamente ao GIZA e SharePoint, sem necessidade de upload manual, para otimizar o fluxo. |
| Critérios de Aceitação       | - Fotos enviadas automaticamente após captura.<br>- Georreferenciamento mantido.<br>- Feedback de upload concluído.<br>- Transparência ao usuário.                      |
| Prioridade Usuário           | Alta                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                |
| Rastreabilidade              | RF02-230                                                                                                                                                                |

---

# [US03-230] - Armazenar automaticamente dados de fauna {#us03-230}

### Tabela 3: História de Usuário – Armazenar automaticamente dados de fauna

| Item                         | Descrição                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-230                                                                                                                                                          |
| Tema                         | Armazenar automaticamente dados de fauna em banco de dados parametrizado                                                                                          |
| Descrição                    | Eu, como analista de dados, desejo que todos os registros de fauna sejam salvos automaticamente em um banco de dados parametrizado, eliminando planilhas manuais. |
| Critérios de Aceitação       | - Dados persistidos em banco parametrizado.<br>- Estrutura suportando tipos de evento.<br>- Consistência e integridade dos registros.                             |
| Prioridade Usuário           | Alta                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                          |
| Rastreabilidade              | RF03-230                                                                                                                                                          |

---

# [US04-230] - Funcionar offline com sincronização automática {#us04-230}

### Tabela 4: História de Usuário – Funcionar offline com sincronização automática

| Item                         | Descrição                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US04-230                                                                                                                                                     |
| Tema                         | Operar offline com sincronização automática                                                                                                                  |
| Descrição                    | Eu, como técnico de campo, desejo que o sistema registre dados mesmo sem conexão e sincronize automaticamente ao reconectar, garantindo continuidade de uso. |
| Critérios de Aceitação       | - Gravação de dados offline sem falhas.<br>- Indicador de status offline/online.<br>- Sincronização automática ao restaurar conexão.                         |
| Prioridade Usuário           | Alta                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                     |
| Rastreabilidade              | RF04-230                                                                                                                                                     |

---

# [US05-230] - Registrar e categorizar espécimes por evento {#us05-230}

### Tabela 5: História de Usuário – Registrar e categorizar espécimes por evento

| Item                         | Descrição                                                                                                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-230                                                                                                                                                                               |
| Tema                         | Registrar e categorizar espécimes por tipo de evento com observações                                                                                                                   |
| Descrição                    | Eu, como técnico de campo, desejo registrar e categorizar cada espécime por evento (atropelamento, resgate, afugentamento), incluindo campos de observação, para análises posteriores. |
| Critérios de Aceitação       | - Seleção de tipo de evento obrigatória.<br>- Campo de observações livre.<br>- Validação de campos obrigatórios.                                                                       |
| Prioridade Usuário           | Alta                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                               |
| Rastreabilidade              | RF05-230                                                                                                                                                                               |

---

# [US06-230] - Gerar relatórios automáticos de fauna {#us06-230}

### Tabela 6: História de Usuário – Gerar relatórios automáticos de fauna

| Item                         | Descrição                                                                                                                                                                                |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-230                                                                                                                                                                                 |
| Tema                         | Gerar relatórios automáticos de fauna com fotos, tabelas e gráficos                                                                                                                      |
| Descrição                    | Eu, como coordenador técnico, desejo gerar relatórios consolidados de fauna com fotos favoritas, tabelas e gráficos comparativos, para facilitar a análise e comunicação dos resultados. |
| Critérios de Aceitação       | - Relatórios gerados em formato PDF e/ou Excel.<br>- Inclusão de fotos favoritas.<br>- Gráficos comparativos com períodos anteriores.<br>- Template padrão definido pela equipe.         |
| Prioridade Usuário           | Alta                                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                                 |
| Rastreabilidade              | RF06-230                                                                                                                                                                                 |
