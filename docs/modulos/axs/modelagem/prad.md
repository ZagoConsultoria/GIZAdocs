# Modelagem de Requisitos — Módulo AXS (PRAD)

## Introdução

Durante o processo de elicitação de requisitos para o módulo AXS (Programa de Recuperação de Áreas Degradadas), foram identificadas diversas necessidades relacionadas à coleta, organização e apresentação de dados de campo, especialmente no contexto do monitoramento de áreas degradadas e ações de recuperação ambiental. Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de campo e escritório.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos técnicos ambientais e analistas de campo, as funcionalidades desejadas no sistema para o módulo PRAD. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

# [US01-AXS] - Coletar dados offline no ZS {#us01-axs}

### Tabela 1: História de Usuário – Coletar dados offline no ZS

| Item                         | Descrição                                                                                                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-AXS                                                                                                                                                                                                          |
| Tema                         | Coletar dados offline no ZS                                                                                                                                                                                       |
| Descrição                    | Eu, como técnico ambiental, desejo realizar a coleta de dados de áreas degradadas diretamente no ZS de forma offline com possibilidade de edição, para garantir continuidade do trabalho mesmo sem conectividade. |
| Critérios de Aceitação       | - A ficha de coleta deve estar disponível no ZS offline.<br>- Deve ser possível editar os dados coletados.<br>- Os dados devem ser armazenados localmente até a sincronização.                                    |
| Prioridade Usuário           | Alta                                                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                                                          |
| Rastreabilidade              | RF01-AXS                                                                                                                                                                                                          |

# [US02-AXS] - Transferir dados automaticamente {#us02-axs}

### Tabela 2: História de Usuário – Transferir dados automaticamente

| Item                         | Descrição                                                                                                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-AXS                                                                                                                                                                                      |
| Tema                         | Transferir dados automaticamente                                                                                                                                                              |
| Descrição                    | Eu, como técnico ambiental, desejo que os dados coletados no ZS sejam transferidos automaticamente para o GIZA após exportação, para otimizar o fluxo de trabalho e reduzir erros manuais.    |
| Critérios de Aceitação       | - A transferência deve ocorrer automaticamente após exportação do ZS.<br>- Os dados devem aparecer no GIZA sem intervenção manual.<br>- Deve haver confirmação de transferência bem-sucedida. |
| Prioridade Usuário           | Alta                                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                                      |
| Rastreabilidade              | RF02-AXS                                                                                                                                                                                      |

# [US03-AXS] - Visualizar fotos por registro {#us03-axs}

### Tabela 3: História de Usuário – Visualizar fotos por registro

| Item                         | Descrição                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-AXS                                                                                                                                                              |
| Tema                         | Visualizar fotos por registro                                                                                                                                         |
| Descrição                    | Eu, como analista ambiental, desejo visualizar as fotos associadas a cada registro no GIZA com opções de seleção e download, para facilitar a análise e documentação. |
| Critérios de Aceitação       | - As fotos devem ser exibidas organizadas por registro.<br>- Deve ser possível selecionar fotos específicas.<br>- Deve haver opção de download individual.            |
| Prioridade Usuário           | Alta                                                                                                                                                                  |
| Status                       | Validada                                                                                                                                                              |
| Rastreabilidade              | RF03-AXS                                                                                                                                                              |

# [US04-AXS] - Baixar fotos em lote {#us04-axs}

### Tabela 4: História de Usuário – Baixar fotos em lote

| Item                         | Descrição                                                                                                                                                              |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-AXS                                                                                                                                                               |
| Tema                         | Baixar fotos em lote                                                                                                                                                   |
| Descrição                    | Eu, como analista ambiental, desejo poder baixar fotos por lote ou por registro individual no GIZA, para facilitar a organização de relatórios e documentação técnica. |
| Critérios de Aceitação       | - Deve haver opção de download por lote de múltiplas fotos.<br>- Deve ser possível download por registro específico.<br>- As fotos devem manter qualidade original.    |
| Prioridade Usuário           | Alta                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                               |
| Rastreabilidade              | RF04-AXS                                                                                                                                                               |

# [US05-AXS] - Editar dados no GIZA {#us05-axs}

### Tabela 5: História de Usuário – Editar dados no GIZA

| Item                         | Descrição                                                                                                                                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-AXS                                                                                                                                                   |
| Tema                         | Editar dados no GIZA                                                                                                                                       |
| Descrição                    | Eu, como técnico ambiental, desejo poder editar dados por registro diretamente no GIZA, para corrigir informações e manter a base de dados atualizada.     |
| Critérios de Aceitação       | - Deve ser possível editar dados diretamente na interface do GIZA.<br>- As alterações devem ser salvas automaticamente.<br>- Deve haver log de alterações. |
| Prioridade Usuário           | Média                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                   |
| Rastreabilidade              | RF05-AXS                                                                                                                                                   |

# [US06-AXS] - Visualizar dashboard com filtros {#us06-axs}

### Tabela 6: História de Usuário – Visualizar dashboard com filtros

| Item                         | Descrição                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US06-AXS                                                                                                                                                     |
| Tema                         | Visualizar dashboard com filtros                                                                                                                             |
| Descrição                    | Eu, como gestor ambiental, desejo visualizar um dashboard com tabela filtrável dos dados coletados, para ter uma visão consolidada das informações de campo. |
| Critérios de Aceitação       | - O dashboard deve exibir dados em formato de tabela.<br>- Deve ser possível aplicar filtros por diferentes parâmetros.<br>- A interface deve ser intuitiva. |
| Prioridade Usuário           | Média                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                     |
| Rastreabilidade              | RF06-AXS                                                                                                                                                     |

# [US07-AXS] - Visualizar informações de análise {#us07-axs}

### Tabela 7: História de Usuário – Visualizar informações de análise

| Item                         | Descrição                                                                                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US07-AXS                                                                                                                                                                       |
| Tema                         | Visualizar informações de análise                                                                                                                                              |
| Descrição                    | Eu, como analista ambiental, desejo visualizar informações visuais de análise como estado da planta, pragas e adubação, para facilitar a interpretação dos dados coletados.    |
| Critérios de Aceitação       | - As informações devem ser apresentadas de forma visual.<br>- Deve incluir indicadores de estado da planta, pragas e adubação.<br>- A visualização deve ser clara e intuitiva. |
| Prioridade Usuário           | Baixa                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                       |
| Rastreabilidade              | RF07-AXS                                                                                                                                                                       |

# [US08-AXS] - Gerar relatórios editáveis {#us08-axs}

### Tabela 8: História de Usuário – Gerar relatórios editáveis

| Item                         | Descrição                                                                                                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US08-AXS                                                                                                                                                                              |
| Tema                         | Gerar relatórios editáveis                                                                                                                                                            |
| Descrição                    | Eu, como analista ambiental, desejo ter a opção de emitir relatórios editáveis com os dados dos registros, para personalizar documentos conforme necessidades específicas do projeto. |
| Critérios de Aceitação       | - O sistema deve gerar relatórios em formato editável.<br>- Os relatórios devem incluir dados dos registros.<br>- Deve ser possível personalizar o formato e conteúdo.                |
| Prioridade Usuário           | Baixa                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                              |
| Rastreabilidade              | RF08-AXS                                                                                                                                                                              |

## Resumo das Histórias de Usuário

### Por Prioridade

**Alta Prioridade:**

- US01-AXS: Coleta offline no ZS (RF01-AXS)
- US02-AXS: Transferência automática (RF02-AXS)
- US03-AXS: Visualização de fotos (RF03-AXS)
- US04-AXS: Download de fotos em lote (RF04-AXS)

**Média Prioridade:**

- US05-AXS: Edição no GIZA (RF05-AXS)
- US06-AXS: Dashboard com filtros (RF06-AXS)

**Baixa Prioridade:**

- US07-AXS: Informações visuais de análise (RF07-AXS)
- US08-AXS: Relatórios editáveis (RF08-AXS)

### Observações

- Todas as histórias foram validadas e estão prontas para implementação
- A priorização reflete as necessidades operacionais identificadas durante a elicitação
- As histórias de alta prioridade são fundamentais para o funcionamento básico do sistema
- As histórias de média e baixa prioridade agregam valor mas podem ser implementadas em fases posteriores
