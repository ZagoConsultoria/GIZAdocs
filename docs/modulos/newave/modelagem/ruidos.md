# Modelagem de Requisitos - Monitoramento de Ruídos

## Introdução

Durante o processo de elicitação de requisitos com a analista ambiental Bruna Ferrari e tomadora de decisão Daniella, foram identificadas diversas necessidades relacionadas à coleta, organização e apresentação de dados de ruído para acompanhar o impacto da obra na fauna e na área urbana. Com base nas funcionalidades levantadas e priorizadas com a técnica dos 100 dólares, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de monitoramento ambiental.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista da analista ambiental, as funcionalidades desejadas no sistema para monitoramento de ruídos. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

# [US13-NW] - Coletar dados de ruído via ZS {#us13-nw}

### Tabela 13: História de Usuário – Coletar dados de ruído via ZS

| Item                         | Descrição                                                                                                                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US13-NW                                                                                                                                                                                              |
| Tema                         | Coletar dados de ruído via ZS                                                                                                                                                                        |
| Descrição                    | Eu, como analista ambiental, desejo realizar a coleta de dados de ruído diretamente no ZS com formulário automatizado para acompanhar o impacto da obra na fauna e área urbana de forma padronizada. |
| Critérios de Aceitação       | - O formulário de coleta deve estar disponível no ZS.<br>- Deve ser possível registrar níveis sonoros por ponto.<br>- Os dados devem ser salvos automaticamente.                                     |
| Prioridade Usuário           | Alta                                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                                             |
| Rastreabilidade              | RF13-NW                                                                                                                                                                                              |

# [US14-NW] - Registrar níveis sonoros com data/hora {#us14-nw}

### Tabela 14: História de Usuário – Registrar níveis sonoros

| Item                         | Descrição                                                                                                                                                       |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US14-NW                                                                                                                                                         |
| Tema                         | Registrar níveis sonoros com data/hora                                                                                                                          |
| Descrição                    | Eu, como analista ambiental, desejo registrar níveis sonoros por ponto de medição com data/hora automática para garantir rastreabilidade das medições.          |
| Critérios de Aceitação       | - Cada medição deve ter timestamp automático.<br>- Deve ser possível associar medições a pontos específicos.<br>- Os dados devem ser organizados temporalmente. |
| Prioridade Usuário           | Alta                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                        |
| Rastreabilidade              | RF14-NW                                                                                                                                                         |

# [US15-NW] - Anexar evidências sonoras automaticamente {#us15-nw}

### Tabela 15: História de Usuário – Anexar evidências sonoras

| Item                         | Descrição                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-NW                                                                                                                                                           |
| Tema                         | Anexar evidências sonoras automaticamente                                                                                                                         |
| Descrição                    | Eu, como analista ambiental, desejo que as evidências sonoras e fotográficas sejam anexadas automaticamente ao GIZA para não precisar fazer uploads manuais.      |
| Critérios de Aceitação       | - Os arquivos de áudio devem ser anexados ao registro.<br>- As fotos devem ser salvas no GIZA automaticamente.<br>- Deve manter qualidade dos arquivos originais. |
| Prioridade Usuário           | Alta                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                          |
| Rastreabilidade              | RF15-NW                                                                                                                                                           |

# [US16-NW] - Utilizar sistema offline para ruídos {#us16-nw}

### Tabela 16: História de Usuário – Funcionamento offline

| Item                         | Descrição                                                                                                                                                |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-NW                                                                                                                                                  |
| Tema                         | Utilizar sistema offline para coleta de ruídos                                                                                                           |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema funcione offline durante as medições de ruído para que eu possa registrar os dados mesmo sem internet. |
| Critérios de Aceitação       | - O sistema deve funcionar sem conexão durante a coleta.<br>- Os dados devem ser sincronizados quando houver conexão disponível.                         |
| Prioridade Usuário           | Alta                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                 |
| Rastreabilidade              | RF16-NW                                                                                                                                                  |

# [US17-NW] - Armazenar dados de ruído com segurança {#us17-nw}

### Tabela 17: História de Usuário – Armazenar dados

| Item                         | Descrição                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US17-NW                                                                                                                                        |
| Tema                         | Armazenar dados de ruído com segurança                                                                                                         |
| Descrição                    | Eu, como analista ambiental, desejo que os dados de ruído fiquem armazenados de forma parametrizada e segura para evitar perda de informações. |
| Critérios de Aceitação       | - Os dados devem ser salvos em banco parametrizado.<br>- Deve haver backup automático.<br>- A segurança dos dados deve ser garantida.          |
| Prioridade Usuário           | Alta                                                                                                                                           |
| Status                       | Validada                                                                                                                                       |
| Rastreabilidade              | RF17-NW                                                                                                                                        |

# [US18-NW] - Integrar sistemas para ruídos {#us18-nw}

### Tabela 18: História de Usuário – Integrar sistemas

| Item                         | Descrição                                                                                                                                                      |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US18-NW                                                                                                                                                        |
| Tema                         | Integrar sistemas ZS, GIZA e TimeStamp                                                                                                                         |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema de ruídos seja integrado ao ZS, GIZA e TimeStamp para garantir fluxo contínuo de dados entre as plataformas. |
| Critérios de Aceitação       | - O sistema deve importar/exportar dados com o ZS.<br>- Os dados devem aparecer automaticamente no GIZA.<br>- Os registros devem ser associados ao TimeStamp.  |
| Prioridade Usuário           | Média                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                       |
| Rastreabilidade              | RF18-NW                                                                                                                                                        |

# [US19-NW] - Visualizar dashboard de ruídos {#us19-nw}

### Tabela 19: História de Usuário – Dashboard de ruídos

| Item                         | Descrição                                                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US19-NW                                                                                                                                                   |
| Tema                         | Visualizar dashboard com níveis de ruído                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo visualizar um dashboard no GIZA com níveis de ruído por área/período para acompanhar o impacto da obra em tempo real. |
| Critérios de Aceitação       | - O dashboard deve exibir níveis por área geográfica.<br>- Deve permitir filtros por período temporal.<br>- Deve destacar níveis críticos visualmente.    |
| Prioridade Usuário           | Média                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                  |
| Rastreabilidade              | RF19-NW                                                                                                                                                   |

# [US20-NW] - Baixar arquivos de áudio e dados {#us20-nw}

### Tabela 20: História de Usuário – Download de arquivos

| Item                         | Descrição                                                                                                                                                   |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US20-NW                                                                                                                                                     |
| Tema                         | Baixar arquivos de áudio e dados                                                                                                                            |
| Descrição                    | Eu, como analista ambiental, desejo poder baixar dados e arquivos de áudio por lote ou registro individual para análise externa e elaboração de relatórios. |
| Critérios de Aceitação       | - Deve haver opção de download por lote e individual.<br>- Os arquivos devem manter qualidade original.<br>- Deve incluir metadados das medições.           |
| Prioridade Usuário           | Média                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                    |
| Rastreabilidade              | RF20-NW                                                                                                                                                     |

# [US21-NW] - Visualizar tabela filtrável de ruídos {#us21-nw}

### Tabela 21: História de Usuário – Tabela filtrável

| Item                         | Descrição                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US21-NW                                                                                                                                            |
| Tema                         | Visualizar tabela filtrável de dados de ruído                                                                                                      |
| Descrição                    | Eu, como analista ambiental, desejo visualizar os dados de ruído em uma tabela filtrável e exportável para facilitar análises e comparações.       |
| Critérios de Aceitação       | - A tabela deve permitir filtros por parâmetro, data e local.<br>- Deve ser possível exportar para Excel ou CSV.<br>- Deve ter ordenação flexível. |
| Prioridade Usuário           | Média                                                                                                                                              |
| Status                       | Validada                                                                                                                                           |
| Rastreabilidade              | RF21-NW                                                                                                                                            |

# [US22-NW] - Gerar relatórios automáticos de ruídos {#us22-nw}

### Tabela 22: História de Usuário – Relatórios automáticos

| Item                         | Descrição                                                                                                                                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US22-NW                                                                                                                                           |
| Tema                         | Gerar relatórios automáticos no GIZA                                                                                                              |
| Descrição                    | Eu, como analista ambiental, desejo gerar relatórios automáticos no GIZA a um clique para agilizar a entrega de documentos aos órgãos ambientais. |
| Critérios de Aceitação       | - O relatório deve ser gerado automaticamente.<br>- Deve incluir gráficos e análises.<br>- Deve seguir padrões regulatórios ambientais.           |
| Prioridade Usuário           | Média                                                                                                                                             |
| Status                       | Validada                                                                                                                                          |
| Rastreabilidade              | RF22-NW                                                                                                                                           |

# [US23-NW] - Analisar impacto na fauna {#us23-nw}

### Tabela 23: História de Usuário – Análise de impacto na fauna

| Item                         | Descrição                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US23-NW                                                                                                                                                          |
| Tema                         | Analisar impacto na fauna                                                                                                                                        |
| Descrição                    | Eu, como analista ambiental, desejo analisar o impacto na fauna com base nos níveis de ruído registrados para avaliar os efeitos da obra na vida selvagem local. |
| Critérios de Aceitação       | - Deve correlacionar níveis de ruído com impacto na fauna.<br>- Deve permitir análise por período e espécie.<br>- Deve gerar alertas para níveis críticos.       |
| Prioridade Usuário           | Baixa                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                         |
| Rastreabilidade              | RF23-NW                                                                                                                                                          |

# [US24-NW] - Registrar impacto em área urbana {#us24-nw}

### Tabela 24: História de Usuário – Impacto em área urbana

| Item                         | Descrição                                                                                                                                                           |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US24-NW                                                                                                                                                             |
| Tema                         | Registrar observações sobre impacto em área urbana                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo registrar observações sobre impacto em área urbana por ponto de coleta para documentar os efeitos da obra na população local.   |
| Critérios de Aceitação       | - Deve permitir registro de observações por ponto.<br>- Deve incluir campos para descrição de impactos.<br>- Deve associar observações aos níveis de ruído medidos. |
| Prioridade Usuário           | Baixa                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                            |
| Rastreabilidade              | RF24-NW                                                                                                                                                             |

## Resumo das Histórias de Usuário

### Por Prioridade

**Alta Prioridade:**

- US13-NW: Coleta de dados via ZS (RF13-NW)
- US14-NW: Registro de níveis sonoros (RF14-NW)
- US15-NW: Anexar evidências automaticamente (RF15-NW)
- US16-NW: Funcionamento offline (RF16-NW)
- US17-NW: Armazenamento seguro (RF17-NW)

**Média Prioridade:**

- US18-NW: Integração de sistemas (RF18-NW)
- US19-NW: Dashboard de ruídos (RF19-NW)
- US20-NW: Download de arquivos (RF20-NW)
- US21-NW: Tabela filtrável (RF21-NW)
- US22-NW: Relatórios automáticos (RF22-NW)

**Baixa Prioridade:**

- US23-NW: Análise de impacto na fauna (RF23-NW)
- US24-NW: Impacto em área urbana (RF24-NW)

### Observações

- Todas as histórias foram validadas e estão prontas para implementação
- A priorização reflete as necessidades operacionais de monitoramento ambiental
- As histórias de alta prioridade são fundamentais para o MVP
- As histórias de média e baixa prioridade agregam valor especializado
