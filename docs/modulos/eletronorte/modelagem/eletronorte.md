# Histórias de Usuário - Módulo Eletronorte

## Introdução

Durante o processo de elicitação de requisitos para o módulo **Eletronorte**, foram identificadas diversas necessidades relacionadas à digitalização dos processos de acompanhamento de atividades no viveiro e monitoramento ambiental na Estação Ecológica (ESEC). Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, substituindo efetivamente o processo manual atual que utiliza múltiplos dispositivos e sistemas desconectados.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos técnicos de campo e coordenadores, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

---

## Histórias de Usuário

---

# [US01-EL] - Registrar acompanhamento diário do viveiro via ZS {#us01-el}

### Tabela 1: História de Usuário – Registrar acompanhamento diário do viveiro via ZS

| Item                         | Descrição                                                                                                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-EL                                                                                                                                                                                 |
| Tema                         | Registrar acompanhamento diário do viveiro via ZS                                                                                                                                       |
| Descrição                    | Eu, como técnico de campo, desejo registrar as atividades diárias do viveiro diretamente no ZS para substituir os registros manuais e ter dados organizados automaticamente.            |
| Critérios de Aceitação       | - Formulário com 52 campos estruturados conforme ficha atual.<br>- Campos condicionais baseados nas respostas.<br>- Captura automática de data, hora e GPS.<br>- Funcionamento offline. |
| Prioridade Usuário           | Alta                                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                                |
| Rastreabilidade              | RF01-EL, RF02-EL                                                                                                                                                                        |

---

# [US02-EL] - Registrar atividades de irrigação {#us02-el}

### Tabela 2: História de Usuário – Registrar atividades de irrigação

| Item                         | Descrição                                                                                                                                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-EL                                                                                                                                                                                     |
| Tema                         | Registrar atividades de irrigação                                                                                                                                                           |
| Descrição                    | Eu, como técnico de campo, desejo registrar detalhes das atividades de irrigação para controlar a frequência e eficiência do sistema de irrigação do viveiro.                               |
| Critérios de Aceitação       | - Campo para indicar se houve irrigação no dia.<br>- Campos condicionais para frequência e tempo por turno.<br>- Seleção de setores irrigados.<br>- Campo para observações sobre problemas. |
| Prioridade Usuário           | Alta                                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                                    |
| Rastreabilidade              | RF03-EL                                                                                                                                                                                     |

---

# [US03-EL] - Registrar atividades de adubação {#us03-el}

### Tabela 3: História de Usuário – Registrar atividades de adubação

| Item                         | Descrição                                                                                                                                                                                 |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-EL                                                                                                                                                                                   |
| Tema                         | Registrar atividades de adubação                                                                                                                                                          |
| Descrição                    | Eu, como técnico de campo, desejo registrar as atividades de adubação realizadas para acompanhar o cronograma e tipos de adubos utilizados nas mudas.                                     |
| Critérios de Aceitação       | - Campo para indicar se houve adubação.<br>- Seleção do tipo de adubo (mineral, foliar, outro).<br>- Lista das espécies que receberam adubação.<br>- Verificação de cronograma planejado. |
| Prioridade Usuário           | Alta                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                  |
| Rastreabilidade              | RF04-EL                                                                                                                                                                                   |

---

# [US04-EL] - Registrar pragas e doenças {#us04-el}

### Tabela 4: História de Usuário – Registrar pragas e doenças

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-EL                                                                                                                                                                                      |
| Tema                         | Registrar pragas e doenças                                                                                                                                                                   |
| Descrição                    | Eu, como técnico de campo, desejo registrar a presença de pragas e doenças nas mudas para monitorar a saúde do viveiro e tomar medidas preventivas.                                          |
| Critérios de Aceitação       | - Identificação de sinais de pragas.<br>- Registro de sintomas de doenças (manchas, murcha, apodrecimento).<br>- Lista das espécies afetadas.<br>- Campo para medidas de controle aplicadas. |
| Prioridade Usuário           | Alta                                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF05-EL                                                                                                                                                                                      |

---

# [US05-EL] - Registrar atividades de manutenção {#us05-el}

### Tabela 5: História de Usuário – Registrar atividades de manutenção

| Item                         | Descrição                                                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US05-EL                                                                                                                                                                                    |
| Tema                         | Registrar atividades de manutenção                                                                                                                                                         |
| Descrição                    | Eu, como técnico de campo, desejo registrar atividades de manutenção do viveiro para manter histórico das ações realizadas e equipamentos utilizados.                                      |
| Critérios de Aceitação       | - Registro de capina e limpeza de bancadas.<br>- Controle de mudas descartadas e substituídas.<br>- Registro de replantio e transferências.<br>- Manutenção de equipamentos e ferramentas. |
| Prioridade Usuário           | Alta                                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                                   |
| Rastreabilidade              | RF06-EL                                                                                                                                                                                    |

---

# [US06-EL] - Anexar fotos georreferenciadas automaticamente {#us06-el}

### Tabela 6: História de Usuário – Anexar fotos georreferenciadas automaticamente

| Item                         | Descrição                                                                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-EL                                                                                                                                                                                        |
| Tema                         | Anexar fotos georreferenciadas automaticamente                                                                                                                                                 |
| Descrição                    | Eu, como técnico de campo, desejo anexar fotos aos registros com localização automática para documentar visualmente as atividades e problemas identificados no viveiro.                        |
| Critérios de Aceitação       | - Upload múltiplo de até 10 fotos por registro.<br>- Georreferenciamento automático das fotos.<br>- Compressão automática para economizar espaço.<br>- Sistema de favoritar fotos importantes. |
| Prioridade Usuário           | Alta                                                                                                                                                                                           |
| Status                       | Validada                                                                                                                                                                                       |
| Rastreabilidade              | RF07-EL, RF08-EL                                                                                                                                                                               |

---

# [US07-EL] - Registrar contagem e medição de mudas {#us07-el}

### Tabela 7: História de Usuário – Registrar contagem e medição de mudas

| Item                         | Descrição                                                                                                                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US07-EL                                                                                                                                                                                          |
| Tema                         | Registrar contagem e medição de mudas                                                                                                                                                            |
| Descrição                    | Eu, como técnico de campo, desejo registrar contagem e medições das mudas por espécie para substituir o processo manual do Mata Nativa e ter controle automatizado.                              |
| Critérios de Aceitação       | - Lista de 17 espécies nativas pré-cadastradas.<br>- Opção "Outro" para espécies não listadas.<br>- Seleção de setor (casa de sombra/pleno sol).<br>- Campos para altura, diâmetro e quantidade. |
| Prioridade Usuário           | Alta                                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                                         |
| Rastreabilidade              | RF09-EL, RF10-EL                                                                                                                                                                                 |

---

# [US08-EL] - Utilizar sistema offline {#us08-el}

### Tabela 8: História de Usuário – Utilizar sistema offline

| Item                         | Descrição                                                                                                                                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US08-EL                                                                                                                                                                              |
| Tema                         | Utilizar sistema offline                                                                                                                                                             |
| Descrição                    | Eu, como técnico de campo, desejo que o sistema funcione offline durante as coletas no viveiro para que eu possa registrar os dados mesmo sem conexão com a internet.                |
| Critérios de Aceitação       | - O sistema deve abrir e registrar dados sem conexão.<br>- Os dados devem ser sincronizados automaticamente quando houver conexão.<br>- Indicador visual do status de sincronização. |
| Prioridade Usuário           | Alta                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                             |
| Rastreabilidade              | RF13-EL                                                                                                                                                                              |

---

# [US09-EL] - Capturar GPS automaticamente {#us09-el}

### Tabela 9: História de Usuário – Capturar GPS automaticamente

| Item                         | Descrição                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US09-EL                                                                                                                                                                          |
| Tema                         | Capturar GPS automaticamente                                                                                                                                                     |
| Descrição                    | Eu, como técnico de campo, desejo que o sistema capture automaticamente as coordenadas GPS para todos os registros, facilitando o georreferenciamento das atividades do viveiro. |
| Critérios de Aceitação       | - As coordenadas devem ser capturadas automaticamente ao abrir qualquer formulário.<br>- Deve funcionar mesmo offline.<br>- Formato de coordenadas adequado para análise.        |
| Prioridade Usuário           | Alta                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                         |
| Rastreabilidade              | RF14-EL                                                                                                                                                                          |

---

# [US10-EL] - Integrar com GIZA automaticamente {#us10-el}

### Tabela 10: História de Usuário – Integrar com GIZA automaticamente

| Item                         | Descrição                                                                                                                                                                           |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-EL                                                                                                                                                                             |
| Tema                         | Integrar com GIZA automaticamente                                                                                                                                                   |
| Descrição                    | Eu, como técnico de campo, desejo que os dados coletados no ZS apareçam automaticamente no GIZA para centralizar as informações e facilitar as análises do coordenador.             |
| Critérios de Aceitação       | - Os dados devem aparecer no GIZA automaticamente após sincronização.<br>- A integração deve ser transparente para o usuário.<br>- Deve manter a organização por tipo de atividade. |
| Prioridade Usuário           | Alta                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                            |
| Rastreabilidade              | RF18-EL                                                                                                                                                                             |

---

# [US11-EL] - Calcular médias de mudas automaticamente {#us11-el}

### Tabela 11: História de Usuário – Calcular médias de mudas automaticamente

| Item                         | Descrição                                                                                                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-EL                                                                                                                                                                                       |
| Tema                         | Calcular médias de mudas automaticamente                                                                                                                                                      |
| Descrição                    | Eu, como coordenador técnico, desejo ter cálculos automáticos de médias por espécie para não precisar fazer cálculos manuais no Excel como é feito atualmente.                                |
| Critérios de Aceitação       | - Cálculo automático de médias de altura e diâmetro.<br>- Totalizadores por espécie e setor.<br>- Histórico de medições com comparação temporal.<br>- Exportação direta para Excel formatado. |
| Prioridade Usuário           | Alta                                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                                      |
| Rastreabilidade              | RF11-EL, RF12-EL                                                                                                                                                                              |

---

# [US12-EL] - Visualizar dados em tabela filtrável {#us12-el}

### Tabela 12: História de Usuário – Visualizar dados em tabela filtrável

| Item                         | Descrição                                                                                                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-EL                                                                                                                                                                                |
| Tema                         | Visualizar dados em tabela filtrável                                                                                                                                                   |
| Descrição                    | Eu, como coordenador técnico, desejo visualizar os dados coletados em tabelas filtráveis para facilitar a consulta e validação das informações registradas no viveiro.                 |
| Critérios de Aceitação       | - Tabela filtrável com todos os dados do viveiro.<br>- Filtros por data, atividade, responsável e espécie.<br>- Busca textual em observações.<br>- Exportação de resultados filtrados. |
| Prioridade Usuário           | Alta                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                               |
| Rastreabilidade              | RF21-EL, RF22-EL, RF23-EL                                                                                                                                                              |

---

# [US13-EL] - Gerenciar fotos dos registros {#us13-el}

### Tabela 13: História de Usuário – Gerenciar fotos dos registros

| Item                         | Descrição                                                                                                                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US13-EL                                                                                                                                                                                          |
| Tema                         | Gerenciar fotos dos registros                                                                                                                                                                    |
| Descrição                    | Eu, como coordenador técnico, desejo visualizar e gerenciar as fotos dos registros para selecionar as melhores imagens para relatórios e organizar automaticamente no Google Drive.              |
| Critérios de Aceitação       | - Visualização de fotos por registro.<br>- Download individual e em lote.<br>- Filtro de fotos favoritas.<br>- Organização automática por data e atividade.<br>- Sincronização com Google Drive. |
| Prioridade Usuário           | Alta                                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                                         |
| Rastreabilidade              | RF24-EL, RF25-EL, RF19-EL                                                                                                                                                                        |

---

# [US14-EL] - Gerar relatórios mensais automaticamente {#us14-el}

### Tabela 14: História de Usuário – Gerar relatórios mensais automaticamente

| Item                         | Descrição                                                                                                                                                                           |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US14-EL                                                                                                                                                                             |
| Tema                         | Gerar relatórios mensais automaticamente                                                                                                                                            |
| Descrição                    | Eu, como coordenador técnico, desejo gerar relatórios mensais automaticamente para não precisar montar relatórios manualmente para o cliente como é feito atualmente.               |
| Critérios de Aceitação       | - Template baseado no modelo atual da Eletronorte.<br>- Inserção automática de fotos favoritadas.<br>- Compilação automática de dados do período.<br>- Geração em formato Word/PDF. |
| Prioridade Usuário           | Alta                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                            |
| Rastreabilidade              | RF31-EL, RF32-EL, RF33-EL, RF34-EL                                                                                                                                                  |

---

# [US15-EL] - Visualizar dashboards de acompanhamento {#us15-el}

### Tabela 15: História de Usuário – Visualizar dashboards de acompanhamento

| Item                         | Descrição                                                                                                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-EL                                                                                                                                                                                       |
| Tema                         | Visualizar dashboards de acompanhamento                                                                                                                                                       |
| Descrição                    | Eu, como gestor de projeto, desejo visualizar indicadores do viveiro em dashboards para acompanhar o desempenho e tomar decisões estratégicas baseadas em dados consolidados.                 |
| Critérios de Aceitação       | - Gráficos de crescimento de mudas por espécie.<br>- Indicadores de taxa de mortalidade.<br>- Métricas de irrigação e adubação.<br>- Alertas de pragas e doenças.<br>- Comparações temporais. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                                      |
| Rastreabilidade              | RF27-EL, RF28-EL, RF29-EL, RF30-EL                                                                                                                                                            |

---

# [US16-EL] - Editar registros de forma controlada {#us16-el}

### Tabela 16: História de Usuário – Editar registros de forma controlada

| Item                         | Descrição                                                                                                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-EL                                                                                                                                                                               |
| Tema                         | Editar registros de forma controlada                                                                                                                                                  |
| Descrição                    | Eu, como coordenador técnico, desejo editar registros quando necessário para corrigir erros sem perder a rastreabilidade das alterações realizadas.                                   |
| Critérios de Aceitação       | - Permissão de edição apenas para coordenadores.<br>- Histórico de alterações (auditoria).<br>- Justificativa obrigatória para edições.<br>- Notificação de alterações para a equipe. |
| Prioridade Usuário           | Média                                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                                              |
| Rastreabilidade              | RF37-EL                                                                                                                                                                               |

---

## Resumo das Histórias de Usuário

### Distribuição por Prioridade

| **Prioridade** | **Quantidade** | **Histórias**       |
| -------------- | -------------- | ------------------- |
| **Alta**       | 14             | US01-EL até US14-EL |
| **Média**      | 1              | US16-EL             |
| **Baixa**      | 1              | US15-EL             |
| **Total**      | **16**         | -                   |

