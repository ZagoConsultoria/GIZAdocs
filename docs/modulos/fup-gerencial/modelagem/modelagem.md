# Histórias de Usuário - Módulo FUP Gerencial

## Introdução

Durante o processo de elicitação de requisitos para o módulo **FUP Gerencial**, foram identificadas diversas necessidades relacionadas ao preenchimento estruturado de formulários de acompanhamento de projetos, visualização de indicadores em dashboard e geração automatizada de relatórios. Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de gestão de projetos.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos Product Owners, gestores de programa e líderes técnicos, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

---

## Histórias de Usuário

---

# [US01-FUP] - Criar novo preenchimento FUP {#us01-fup}

### Tabela 1: História de Usuário – Criar novo preenchimento FUP

| Item                         | Descrição                                                                                                                                                                                                       |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-FUP                                                                                                                                                                                                        |
| Tema                         | Criar novo preenchimento FUP                                                                                                                                                                                    |
| Descrição                    | Eu, como PO, desejo criar um novo preenchimento FUP para meu projeto para documentar o status atual do projeto de forma estruturada e padronizada.                                                              |
| Critérios de Aceitação       | - Deve haver formulário de criação acessível.<br>- Sistema deve solicitar informações básicas do projeto.<br>- Associação automática com minha identificação como PO.<br>- Confirmação de criação com ID único. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                                                        |
| Rastreabilidade              | RF01-FUP, RF19-FUP                                                                                                                                                                                              |

---

# [US02-FUP] - Navegar por fluxo assistido com blocos {#us02-fup}

### Tabela 2: História de Usuário – Navegar por fluxo assistido com blocos

| Item                         | Descrição                                                                                                                                                                                 |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-FUP                                                                                                                                                                                  |
| Tema                         | Navegar por fluxo assistido com blocos                                                                                                                                                    |
| Descrição                    | Eu, como PO, desejo ser guiado através de blocos temáticos organizados para ter clareza sobre o que preencher e não perder nenhuma informação importante.                                 |
| Critérios de Aceitação       | - Interface deve apresentar blocos em sequência lógica.<br>- Navegação clara entre blocos (próximo/anterior).<br>- Indicador de progresso visual.<br>- Validação básica antes de avançar. |
| Prioridade Usuário           | Alta                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                  |
| Rastreabilidade              | RF02-FUP                                                                                                                                                                                  |

---

# [US03-FUP] - Preencher bloco financeiro {#us03-fup}

### Tabela 3: História de Usuário – Preencher bloco financeiro

| Item                         | Descrição                                                                                                                                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US03-FUP                                                                                                                                                                             |
| Tema                         | Preencher bloco financeiro                                                                                                                                                           |
| Descrição                    | Eu, como PO, desejo preencher informações financeiras do projeto para que os gestores tenham visibilidade sobre o aspecto orçamentário e possam tomar decisões informadas.           |
| Critérios de Aceitação       | - Campos para orçamento previsto vs. realizado.<br>- Indicadores de desvio percentual automáticos.<br>- Campos para justificativas de desvios.<br>- Validação de formatos numéricos. |
| Prioridade Usuário           | Alta                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                             |
| Rastreabilidade              | RF03-FUP                                                                                                                                                                             |

---

# [US04-FUP] - Preencher bloco de gestão de entregas {#us04-fup}

### Tabela 4: História de Usuário – Preencher bloco de gestão de entregas

| Item                         | Descrição                                                                                                                                                                       |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-FUP                                                                                                                                                                        |
| Tema                         | Preencher bloco de gestão de entregas                                                                                                                                           |
| Descrição                    | Eu, como PO, desejo registrar o status das entregas do projeto para que haja transparência sobre o cumprimento de prazos e identificação de bloqueadores.                       |
| Critérios de Aceitação       | - Lista de entregas com status atualizável.<br>- Campos para datas previstas vs. realizadas.<br>- Indicador visual de atraso/adiantamento.<br>- Comentários sobre bloqueadores. |
| Prioridade Usuário           | Alta                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                        |
| Rastreabilidade              | RF04-FUP                                                                                                                                                                        |

---

# [US05-FUP] - Preencher bloco de gestão da qualidade {#us05-fup}

### Tabela 5: História de Usuário – Preencher bloco de gestão da qualidade

| Item                         | Descrição                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US05-FUP                                                                                                                                                     |
| Tema                         | Preencher bloco de gestão da qualidade                                                                                                                       |
| Descrição                    | Eu, como PO, desejo registrar indicadores de qualidade do projeto para que aspectos qualitativos sejam considerados na avaliação geral e tomada de decisões. |
| Critérios de Aceitação       | - Métricas de qualidade predefinidas.<br>- Campos para evidências e comentários.<br>- Escala de avaliação padronizada.<br>- Anexo de documentos de suporte.  |
| Prioridade Usuário           | Média                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                     |
| Rastreabilidade              | RF05-FUP                                                                                                                                                     |

---

# [US06-FUP] - Preencher bloco de nível de qualidade técnica {#us06-fup}

### Tabela 6: História de Usuário – Preencher bloco de nível de qualidade técnica

| Item                         | Descrição                                                                                                                                                                 |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-FUP                                                                                                                                                                  |
| Tema                         | Preencher bloco de nível de qualidade técnica                                                                                                                             |
| Descrição                    | Eu, como PO, desejo avaliar o nível de qualidade técnica para que aspectos técnicos sejam incluídos na avaliação geral do projeto e identificação de melhorias.           |
| Critérios de Aceitação       | - Métricas técnicas específicas disponíveis.<br>- Integração com ferramentas de qualidade de código.<br>- Benchmarks de referência.<br>- Trending de melhoria/degradação. |
| Prioridade Usuário           | Média                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                  |
| Rastreabilidade              | RF06-FUP                                                                                                                                                                  |

---

# [US07-FUP] - Preencher bloco de nível tecnológico {#us07-fup}

### Tabela 7: História de Usuário – Preencher bloco de nível tecnológico

| Item                         | Descrição                                                                                                                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-FUP                                                                                                                                                                   |
| Tema                         | Preencher bloco de nível tecnológico                                                                                                                                       |
| Descrição                    | Eu, como PO, desejo avaliar o nível tecnológico do projeto para que a maturidade técnica seja considerada e estratégias de evolução sejam planejadas.                      |
| Critérios de Aceitação       | - Avaliação de stack tecnológico.<br>- Indicadores de modernidade das tecnologias.<br>- Comparação com padrões da organização.<br>- Recomendações automáticas de evolução. |
| Prioridade Usuário           | Baixa                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                   |
| Rastreabilidade              | RF07-FUP                                                                                                                                                                   |

---

# [US08-FUP] - Usar salvamento automático {#us08-fup}

### Tabela 8: História de Usuário – Usar salvamento automático

| Item                         | Descrição                                                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US08-FUP                                                                                                                                                                                   |
| Tema                         | Usar salvamento automático                                                                                                                                                                 |
| Descrição                    | Eu, como PO, desejo que minhas informações sejam salvas automaticamente para que eu não perca dados em caso de problemas técnicos ou fechamento acidental da página.                       |
| Critérios de Aceitação       | - Salvamento automático a cada 30 segundos.<br>- Indicador visual de status de salvamento.<br>- Recuperação automática em caso de reconexão.<br>- Mensagem de confirmação de dados salvos. |
| Prioridade Usuário           | Alta                                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                                   |
| Rastreabilidade              | RF08-FUP                                                                                                                                                                                   |

---

# [US09-FUP] - Usar lógica condicional no formulário {#us09-fup}

### Tabela 9: História de Usuário – Usar lógica condicional no formulário

| Item                         | Descrição                                                                                                                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US09-FUP                                                                                                                                                                                             |
| Tema                         | Usar lógica condicional no formulário                                                                                                                                                                |
| Descrição                    | Eu, como PO, desejo que o formulário se adapte às minhas respostas anteriores para ter uma experiência mais personalizada e eficiente durante o preenchimento.                                       |
| Critérios de Aceitação       | - Campos condicionais devem aparecer/desaparecer conforme contexto.<br>- Validações específicas por contexto.<br>- Fluxo otimizado baseado no tipo de projeto.<br>- Configuração flexível de regras. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                                             |
| Rastreabilidade              | RF09-FUP                                                                                                                                                                                             |

---

# [US10-FUP] - Gerar relatório em PDF {#us10-fup}

### Tabela 10: História de Usuário – Gerar relatório em PDF

| Item                         | Descrição                                                                                                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-FUP                                                                                                                                                                                |
| Tema                         | Gerar relatório em PDF                                                                                                                                                                  |
| Descrição                    | Eu, como líder técnico, desejo gerar um relatório em PDF do FUP para compartilhar ou arquivar as informações de forma profissional e padronizada.                                       |
| Critérios de Aceitação       | - Relatório deve ser formatado profissionalmente.<br>- Deve incluir todas as seções preenchidas.<br>- Geração em menos de 10 segundos.<br>- Download automático ou visualização online. |
| Prioridade Usuário           | Alta                                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                                |
| Rastreabilidade              | RF10-FUP                                                                                                                                                                                |

---

# [US11-FUP] - Visualizar relatório organizado por blocos {#us11-fup}

### Tabela 11: História de Usuário – Visualizar relatório organizado por blocos

| Item                         | Descrição                                                                                                                                                               |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-FUP                                                                                                                                                                |
| Tema                         | Visualizar relatório organizado por blocos                                                                                                                              |
| Descrição                    | Eu, como líder técnico, desejo que o relatório PDF seja organizado por blocos temáticos para que a leitura seja estruturada e fácil de navegar.                         |
| Critérios de Aceitação       | - Seções devem ser claramente divididas por bloco.<br>- Índice navegável disponível.<br>- Gráficos e tabelas bem formatados.<br>- Cabeçalho com informações do projeto. |
| Prioridade Usuário           | Média                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                |
| Rastreabilidade              | RF11-FUP                                                                                                                                                                |

---

# [US12-FUP] - Acessar histórico de relatórios {#us12-fup}

### Tabela 12: História de Usuário – Acessar histórico de relatórios

| Item                         | Descrição                                                                                                                                                                     |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-FUP                                                                                                                                                                      |
| Tema                         | Acessar histórico de relatórios                                                                                                                                               |
| Descrição                    | Eu, como líder técnico, desejo acessar o histórico de relatórios de um projeto para acompanhar a evolução ao longo do tempo e fazer análises comparativas.                    |
| Critérios de Aceitação       | - Lista cronológica de relatórios disponível.<br>- Visualização de versões anteriores.<br>- Funcionalidade de comparação entre períodos.<br>- Download de versões históricas. |
| Prioridade Usuário           | Média                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                      |
| Rastreabilidade              | RF12-FUP                                                                                                                                                                      |

---

# [US13-FUP] - Visualizar dashboard com faróis {#us13-fup}

### Tabela 13: História de Usuário – Visualizar dashboard com faróis

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US13-FUP                                                                                                                                                                                     |
| Tema                         | Visualizar dashboard com faróis                                                                                                                                                              |
| Descrição                    | Eu, como gestor de programa, desejo visualizar um dashboard com indicadores em formato de farol para ter uma visão rápida do status geral dos projetos sob minha gestão.                     |
| Critérios de Aceitação       | - Cards de projeto com cores de farol (verde/amarelo/vermelho).<br>- Layout responsivo e claro.<br>- Atualização em tempo real.<br>- Informações básicas visíveis sem necessidade de clique. |
| Prioridade Usuário           | Alta                                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF13-FUP                                                                                                                                                                                     |

---

# [US14-FUP] - Usar cálculo automático de farol {#us14-fup}

### Tabela 14: História de Usuário – Usar cálculo automático de farol

| Item                         | Descrição                                                                                                                                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US14-FUP                                                                                                                                                                             |
| Tema                         | Usar cálculo automático de farol                                                                                                                                                     |
| Descrição                    | Eu, como sistema, preciso calcular automaticamente a cor do farol para que os gestores tenham indicadores consistentes e objetivos baseados em critérios padronizados.               |
| Critérios de Aceitação       | - Algoritmo baseado nos blocos preenchidos.<br>- Regras claras para verde/amarelo/vermelho.<br>- Recálculo automático a cada atualização.<br>- Log de mudanças de status disponível. |
| Prioridade Usuário           | Alta                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                             |
| Rastreabilidade              | RF14-FUP                                                                                                                                                                             |

---

# [US15-FUP] - Filtrar dashboard por PO {#us15-fup}

### Tabela 15: História de Usuário – Filtrar dashboard por PO

| Item                         | Descrição                                                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-FUP                                                                                                                                                                    |
| Tema                         | Filtrar dashboard por PO                                                                                                                                                    |
| Descrição                    | Eu, como gestor de programa, desejo filtrar o dashboard por Product Owner para focar nos projetos de POs específicos e facilitar o acompanhamento personalizado.            |
| Critérios de Aceitação       | - Dropdown com lista completa de POs.<br>- Filtro aplicado instantaneamente.<br>- Opção "Todos" para remover filtro.<br>- Contadores de projetos atualizados dinamicamente. |
| Prioridade Usuário           | Alta                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                    |
| Rastreabilidade              | RF15-FUP                                                                                                                                                                    |

---

# [US16-FUP] - Filtrar dashboard por projeto {#us16-fup}

### Tabela 16: História de Usuário – Filtrar dashboard por projeto

| Item                         | Descrição                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-FUP                                                                                                                                                                          |
| Tema                         | Filtrar dashboard por projeto                                                                                                                                                     |
| Descrição                    | Eu, como gestor de programa, desejo filtrar o dashboard por projeto específico para acompanhar projetos de interesse particular e fazer análises focadas.                         |
| Critérios de Aceitação       | - Campo de busca por nome do projeto.<br>- Funcionalidade de autocomplete com sugestões.<br>- Busca parcial funcionando adequadamente.<br>- Resultados atualizados dinamicamente. |
| Prioridade Usuário           | Alta                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                          |
| Rastreabilidade              | RF16-FUP                                                                                                                                                                          |

---

# [US17-FUP] - Filtrar dashboard por período {#us17-fup}

### Tabela 17: História de Usuário – Filtrar dashboard por período

| Item                         | Descrição                                                                                                                                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US17-FUP                                                                                                                                                                                    |
| Tema                         | Filtrar dashboard por período                                                                                                                                                               |
| Descrição                    | Eu, como gestor de programa, desejo filtrar o dashboard por período específico para analisar tendências temporais e fazer comparações históricas.                                           |
| Critérios de Aceitação       | - Seletor de data inicial e final disponível.<br>- Presets comuns (último mês, trimestre, etc.).<br>- Visualização clara do período selecionado.<br>- Métricas recalculadas para o período. |
| Prioridade Usuário           | Média                                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                                    |
| Rastreabilidade              | RF17-FUP                                                                                                                                                                                    |

---

# [US18-FUP] - Usar drill-down em faróis {#us18-fup}

### Tabela 18: História de Usuário – Usar drill-down em faróis

| Item                         | Descrição                                                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US18-FUP                                                                                                                                                                                   |
| Tema                         | Usar drill-down em faróis                                                                                                                                                                  |
| Descrição                    | Eu, como gestor de programa, desejo clicar em um farol para ver detalhes específicos para entender os motivos por trás do status e tomar ações corretivas.                                 |
| Critérios de Aceitação       | - Modal ou página de detalhes acessível por clique.<br>- Breakdown dos fatores que influenciam o farol.<br>- Ações recomendadas apresentadas.<br>- Links diretos para áreas problemáticas. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                   |
| Rastreabilidade              | RF18-FUP                                                                                                                                                                                   |

---

# [US19-FUP] - Associar metadados do projeto {#us19-fup}

### Tabela 19: História de Usuário – Associar metadados do projeto

| Item                         | Descrição                                                                                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US19-FUP                                                                                                                                                                       |
| Tema                         | Associar metadados do projeto                                                                                                                                                  |
| Descrição                    | Eu, como PO, desejo que o sistema associe automaticamente metadados do projeto (PO, data, identificação) para garantir rastreabilidade e organização adequada das informações. |
| Critérios de Aceitação       | - Associação automática de projeto/PO/data.<br>- Metadados visíveis em relatórios.<br>- Identificação única por preenchimento.<br>- Histórico de modificações rastreável.      |
| Prioridade Usuário           | Alta                                                                                                                                                                           |
| Status                       | Validada                                                                                                                                                                       |
| Rastreabilidade              | RF19-FUP                                                                                                                                                                       |

---

# [US20-FUP] - Visualizar evolução de projetos {#us20-fup}

### Tabela 20: História de Usuário – Visualizar evolução de projetos

| Item                         | Descrição                                                                                                                                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US20-FUP                                                                                                                                                                                    |
| Tema                         | Visualizar evolução de projetos                                                                                                                                                             |
| Descrição                    | Eu, como gestor de programa, desejo visualizar a evolução dos projetos ao longo do tempo para identificar tendências, padrões e oportunidades de melhoria.                                  |
| Critérios de Aceitação       | - Gráficos de linha temporal disponíveis.<br>- Indicadores visuais de melhoria/piora.<br>- Alertas automáticos para mudanças significativas.<br>- Funcionalidade de drill-down por projeto. |
| Prioridade Usuário           | Média                                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                                    |
| Rastreabilidade              | RF20-FUP                                                                                                                                                                                    |
