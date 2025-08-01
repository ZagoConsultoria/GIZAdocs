# Histórias de Usuário - Módulo Engeform

## Introdução

Durante o processo de elicitação de requisitos para o módulo **Engeform**, foram identificadas diversas necessidades relacionadas à coleta, armazenamento, tratamento e distribuição de dados para estudos de impacto ambiental (EIA). Com base nas funcionalidades levantadas e priorizadas, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de campo e escritório.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista dos analistas ambientais, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

---

## Histórias de Usuário

---

# [US01-EG] - Coletar dados socioeconômicos via ZS {#us01-eg}

### Tabela 1: História de Usuário – Coletar dados socioeconômicos via ZS

| Item                         | Descrição                                                                                                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-EG                                                                                                                                                                               |
| Tema                         | Coletar dados socioeconômicos via ZS                                                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo realizar a coleta de dados socioeconômicos diretamente no ZS para substituir formulários em papel e garantir padronização dos registros de campo. |
| Critérios de Aceitação       | - A ficha de coleta deve estar disponível no ZS.<br>- Deve ser possível preencher dados demográficos e socioeconômicos.<br>- Os dados devem ser salvos automaticamente no banco.      |
| Prioridade Usuário           | Alta                                                                                                                                                                                  |
| Status                       | Validada                                                                                                                                                                              |
| Rastreabilidade              | RF01-EG                                                                                                                                                                               |

---

# [US02-EG] - Coletar dados de cavidades via ZS {#us02-eg}

### Tabela 2: História de Usuário – Coletar dados de cavidades via ZS

| Item                         | Descrição                                                                                                                                                                    |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-EG                                                                                                                                                                      |
| Tema                         | Coletar dados de cavidades via ZS                                                                                                                                            |
| Descrição                    | Eu, como analista ambiental, desejo realizar a coleta de dados de espeleologia diretamente no ZS para registrar informações sobre cavidades naturais de forma padronizada.   |
| Critérios de Aceitação       | - A ficha de coleta deve estar disponível no ZS.<br>- Deve incluir campos específicos para dados espeleológicos.<br>- Os dados devem ser categorizados por tipo de cavidade. |
| Prioridade Usuário           | Alta                                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                                     |
| Rastreabilidade              | RF02-EG                                                                                                                                                                      |

---

# [US03-EG] - Coletar dados hidrológicos via ZS {#us03-eg}

### Tabela 3: História de Usuário – Coletar dados hidrológicos via ZS

| Item                         | Descrição                                                                                                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US03-EG                                                                                                                                                                                 |
| Tema                         | Coletar dados hidrológicos via ZS                                                                                                                                                       |
| Descrição                    | Eu, como analista ambiental, desejo realizar a coleta de dados de recursos hídricos superficiais diretamente no ZS para registrar informações sobre corpos d'água de forma padronizada. |
| Critérios de Aceitação       | - A ficha de coleta deve estar disponível no ZS.<br>- Deve incluir campos para características dos recursos hídricos.<br>- Os dados devem ser organizados por tipo de corpo d'água.     |
| Prioridade Usuário           | Alta                                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                                |
| Rastreabilidade              | RF03-EG                                                                                                                                                                                 |

---

# [US04-EG] - Utilizar sistema offline {#us04-eg}

### Tabela 4: História de Usuário – Utilizar sistema offline

| Item                         | Descrição                                                                                                                                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-EG                                                                                                                                                                                     |
| Tema                         | Utilizar sistema offline                                                                                                                                                                    |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema funcione offline durante as coletas de campo para que eu possa registrar os dados mesmo sem conexão com a internet.                       |
| Critérios de Aceitação       | - O sistema deve abrir e registrar dados sem conexão.<br>- Os dados devem ser sincronizados automaticamente quando houver conexão disponível.<br>- Todas as fichas devem funcionar offline. |
| Prioridade Usuário           | Alta                                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                                    |
| Rastreabilidade              | RF11-EG                                                                                                                                                                                     |

---

# [US05-EG] - Capturar GPS automaticamente {#us05-eg}

### Tabela 5: História de Usuário – Capturar GPS automaticamente

| Item                         | Descrição                                                                                                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-EG                                                                                                                                                                                       |
| Tema                         | Capturar GPS automaticamente                                                                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema capture automaticamente as coordenadas GPS em formato UTM para todos os formulários, facilitando o georreferenciamento dos dados coletados. |
| Critérios de Aceitação       | - As coordenadas devem ser capturadas automaticamente ao abrir qualquer formulário.<br>- O formato deve ser UTM.<br>- Deve funcionar mesmo offline.                                           |
| Prioridade Usuário           | Alta                                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                                      |
| Rastreabilidade              | RF12-EG                                                                                                                                                                                       |

---

# [US06-EG] - Enviar fotos georreferenciadas automaticamente {#us06-eg}

### Tabela 6: História de Usuário – Enviar fotos georreferenciadas automaticamente

| Item                         | Descrição                                                                                                                                                                                 |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-EG                                                                                                                                                                                   |
| Tema                         | Enviar fotos georreferenciadas automaticamente                                                                                                                                            |
| Descrição                    | Eu, como analista ambiental, desejo que as fotos da coleta sejam enviadas automaticamente com georreferenciamento e marca d'água da empresa para facilitar a documentação das evidências. |
| Critérios de Aceitação       | - As fotos devem ser georreferenciadas automaticamente.<br>- Deve incluir marca d'água da empresa.<br>- O upload deve ser automático quando conectado à internet.                         |
| Prioridade Usuário           | Alta                                                                                                                                                                                      |
| Status                       | Validada                                                                                                                                                                                  |
| Rastreabilidade              | RF13-EG                                                                                                                                                                                   |

---

# [US07-EG] - Integrar com GIZA automaticamente {#us07-eg}

### Tabela 7: História de Usuário – Integrar com GIZA automaticamente

| Item                         | Descrição                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-EG                                                                                                                                                                          |
| Tema                         | Integrar com GIZA automaticamente                                                                                                                                                |
| Descrição                    | Eu, como analista ambiental, desejo que os dados coletados no ZS apareçam automaticamente no GIZA para centralizar as informações e facilitar as análises.                       |
| Critérios de Aceitação       | - Os dados devem aparecer no GIZA automaticamente após sincronização.<br>- A integração deve ser transparente para o usuário.<br>- Deve manter a organização por meio ambiental. |
| Prioridade Usuário           | Alta                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                         |
| Rastreabilidade              | RF18-EG                                                                                                                                                                          |

---

# [US08-EG] - Validar dados obrigatórios automaticamente {#us08-eg}

### Tabela 8: História de Usuário – Validar dados obrigatórios automaticamente

| Item                         | Descrição                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US08-EG                                                                                                                                                                          |
| Tema                         | Validar dados obrigatórios automaticamente                                                                                                                                       |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema valide automaticamente os dados obrigatórios nos formulários para garantir a qualidade e completude das informações coletadas. |
| Critérios de Aceitação       | - O sistema deve identificar campos obrigatórios não preenchidos.<br>- Deve exibir alertas claros sobre dados faltantes.<br>- Não deve permitir salvar formulários incompletos.  |
| Prioridade Usuário           | Alta                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                         |
| Rastreabilidade              | RF21-EG                                                                                                                                                                          |

---

# [US09-EG] - Visualizar dados em tabela filtrável {#us09-eg}

### Tabela 9: História de Usuário – Visualizar dados em tabela filtrável

| Item                         | Descrição                                                                                                                                                                           |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US09-EG                                                                                                                                                                             |
| Tema                         | Visualizar dados em tabela filtrável                                                                                                                                                |
| Descrição                    | Eu, como analista ambiental, desejo visualizar os dados coletados em tabelas filtráveis por meio ambiental para facilitar a consulta e análise das informações de campo.            |
| Critérios de Aceitação       | - As tabelas devem permitir filtros por diferentes parâmetros.<br>- Deve haver separação por meio ambiental (físico, biótico, socioeconômico).<br>- A interface deve ser intuitiva. |
| Prioridade Usuário           | Alta                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                            |
| Rastreabilidade              | RF22-EG, RF23-EG, RF24-EG                                                                                                                                                           |

---

# [US10-EG] - Exportar dados para Excel {#us10-eg}

### Tabela 10: História de Usuário – Exportar dados para Excel

| Item                         | Descrição                                                                                                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-EG                                                                                                                                                                                 |
| Tema                         | Exportar dados para Excel                                                                                                                                                               |
| Descrição                    | Eu, como analista ambiental, desejo exportar os dados coletados para planilhas Excel organizadas por meio ambiental para facilitar análises externas e compartilhamento de informações. |
| Critérios de Aceitação       | - A exportação deve ser separada por meio ambiental.<br>- O arquivo Excel deve manter a formatação adequada.<br>- Deve incluir filtros automáticos nas colunas.                         |
| Prioridade Usuário           | Média                                                                                                                                                                                   |
| Status                       | Validada                                                                                                                                                                                |
| Rastreabilidade              | RF37-EG                                                                                                                                                                                 |

---

# [US11-EG] - Gerar relatórios automatizados {#us11-eg}

### Tabela 11: História de Usuário – Gerar relatórios automatizados

| Item                         | Descrição                                                                                                                                                                           |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-EG                                                                                                                                                                             |
| Tema                         | Gerar relatórios automatizados                                                                                                                                                      |
| Descrição                    | Eu, como analista ambiental, desejo gerar relatórios automatizados por meio ambiental para agilizar a produção de documentos técnicos e atender às demandas regulatórias.           |
| Critérios de Aceitação       | - Os relatórios devem ser gerados automaticamente.<br>- Deve haver separação por meio ambiental.<br>- O formato deve seguir padrões técnicos.<br>- Deve ser exportável em PDF/Word. |
| Prioridade Usuário           | Alta                                                                                                                                                                                |
| Status                       | Validada                                                                                                                                                                            |
| Rastreabilidade              | RF36-EG                                                                                                                                                                             |

---

# [US12-EG] - Visualizar fotos por registro {#us12-eg}

### Tabela 12: História de Usuário – Visualizar fotos por registro

| Item                         | Descrição                                                                                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-EG                                                                                                                                                                          |
| Tema                         | Visualizar fotos por registro                                                                                                                                                    |
| Descrição                    | Eu, como analista ambiental, desejo visualizar as fotos associadas a cada registro de coleta para facilitar a análise das evidências e a validação dos dados coletados em campo. |
| Critérios de Aceitação       | - As fotos devem ser organizadas por registro.<br>- Deve ser possível visualizar em tamanho adequado.<br>- Deve mostrar informações de georreferenciamento.                      |
| Prioridade Usuário           | Média                                                                                                                                                                            |
| Status                       | Validada                                                                                                                                                                         |
| Rastreabilidade              | RF33-EG                                                                                                                                                                          |

---

# [US13-EG] - Fazer download de fotos {#us13-eg}

### Tabela 13: História de Usuário – Fazer download de fotos

| Item                         | Descrição                                                                                                                                                   |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US13-EG                                                                                                                                                     |
| Tema                         | Fazer download de fotos                                                                                                                                     |
| Descrição                    | Eu, como analista ambiental, desejo fazer download das fotos individualmente ou em lote para utilizar as evidências em relatórios e documentações técnicas. |
| Critérios de Aceitação       | - Deve permitir download individual por foto.<br>- Deve permitir download em lote por registro ou coleta.<br>- As fotos devem manter qualidade original.    |
| Prioridade Usuário           | Média                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                    |
| Rastreabilidade              | RF34-EG                                                                                                                                                     |

---

# [US14-EG] - Realizar busca avançada {#us14-eg}

### Tabela 14: História de Usuário – Realizar busca avançada

| Item                         | Descrição                                                                                                                                                                                |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US14-EG                                                                                                                                                                                  |
| Tema                         | Realizar busca avançada                                                                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo realizar buscas avançadas nos dados coletados para localizar rapidamente informações específicas usando múltiplos critérios de pesquisa.             |
| Critérios de Aceitação       | - Deve permitir busca por múltiplos campos simultaneamente.<br>- Deve incluir filtros por data, localização e meio ambiental.<br>- Os resultados devem ser exibidos de forma organizada. |
| Prioridade Usuário           | Média                                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                                 |
| Rastreabilidade              | RF38-EG                                                                                                                                                                                  |

---

# [US15-EG] - Visualizar dashboards especializados {#us15-eg}

### Tabela 15: História de Usuário – Visualizar dashboards especializados

| Item                         | Descrição                                                                                                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-EG                                                                                                                                                                                                   |
| Tema                         | Visualizar dashboards especializados                                                                                                                                                                      |
| Descrição                    | Eu, como gestor ambiental, desejo visualizar dashboards com gráficos especializados por meio ambiental para ter uma visão analítica consolidada dos dados coletados em campo.                             |
| Critérios de Aceitação       | - Deve incluir gráficos específicos por meio ambiental.<br>- Os dashboards devem ser interativos.<br>- Deve permitir filtros por período e localização.<br>- Dados devem ser atualizados automaticamente. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                                                  |
| Rastreabilidade              | RF25-EG, RF26-EG, RF27-EG, RF28-EG, RF29-EG, RF30-EG, RF31-EG, RF32-EG                                                                                                                                    |

---

# [US16-EG] - Editar dados controladamente {#us16-eg}

### Tabela 16: História de Usuário – Editar dados controladamente

| Item                         | Descrição                                                                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US16-EG                                                                                                                                                                                        |
| Tema                         | Editar dados controladamente                                                                                                                                                                   |
| Descrição                    | Eu, como supervisor ambiental, desejo editar dados coletados de forma controlada via GIZA para corrigir informações quando necessário, mantendo o histórico de alterações.                     |
| Critérios de Aceitação       | - Edições devem ser registradas com log de auditoria.<br>- Apenas usuários autorizados podem editar.<br>- Versões anteriores devem ser preservadas.<br>- Deve haver notificação de alterações. |
| Prioridade Usuário           | Baixa                                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                                       |
| Rastreabilidade              | RF35-EG                                                                                                                                                                                        |

---

# [US17-EG] - Favoritar e baixar fotos selecionadas {#us17-eg}

### Tabela 17: História de Usuário – Favoritar e baixar fotos selecionadas

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US17-EG                                                                                                                                                                                      |
| Tema                         | Favoritar e baixar fotos selecionadas                                                                                                                                                        |
| Descrição                    | Eu, como analista ambiental, desejo favoritar fotos específicas em cada registro e fazer download em lote apenas das fotos favoritas para otimizar a seleção de evidências mais relevantes.  |
| Critérios de Aceitação       | - Deve permitir marcar fotos como favoritas em cada registro.<br>- Deve haver ícone visual para identificar fotos favoritas.<br>- Deve permitir download em lote apenas das fotos favoritas. |
| Prioridade Usuário           | Média                                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF39-EG                                                                                                                                                                                      |

---

# [US18-EG] - Exportar coordenadas geográficas {#us18-eg}

### Tabela 18: História de Usuário – Exportar coordenadas geográficas

| Item                         | Descrição                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US18-EG                                                                                                                                                                                      |
| Tema                         | Exportar coordenadas geográficas                                                                                                                                                             |
| Descrição                    | Eu, como analista ambiental, desejo exportar apenas as coordenadas geográficas dos registros para planilha Excel para facilitar análises espaciais e mapeamento dos pontos de coleta.        |
| Critérios de Aceitação       | - Deve exportar apenas coordenadas (latitude, longitude, UTM).<br>- Deve incluir identificador do registro.<br>- Formato deve ser compatível com softwares de GIS.<br>- Exportação em Excel. |
| Prioridade Usuário           | Média                                                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                                                     |
| Rastreabilidade              | RF40-EG                                                                                                                                                                                      |

---

## Resumo das Histórias de Usuário

### Por Prioridade

**Alta Prioridade:**

- US01-EG: Coleta socioeconômica (RF01-EG)
- US02-EG: Coleta de cavidades (RF02-EG)
- US03-EG: Coleta hidrológica (RF03-EG)
- US04-EG: Sistema offline (RF11-EG)
- US05-EG: GPS automático (RF12-EG)
- US06-EG: Fotos georreferenciadas (RF13-EG)
- US07-EG: Integração GIZA (RF18-EG)
- US08-EG: Validação automática (RF21-EG)
- US09-EG: Tabelas filtráveis (RF22-EG, RF23-EG, RF24-EG)
- US11-EG: Relatórios automatizados (RF36-EG)

**Média Prioridade:**

- US10-EG: Exportação Excel (RF37-EG)
- US12-EG: Visualização de fotos (RF33-EG)
- US13-EG: Download de fotos (RF34-EG)
- US14-EG: Busca avançada (RF38-EG)
- US17-EG: Favoritar fotos selecionadas (RF39-EG)
- US18-EG: Exportar coordenadas (RF40-EG)

**Baixa Prioridade:**

- US15-EG: Dashboards especializados (RF25-EG a RF32-EG)
- US16-EG: Edição controlada (RF35-EG)

### Por Meio Ambiental

**Transversal (Todos):** 12 histórias
**Físico:** 3 histórias (coleta + dashboards)
**Biótico:** 1 história (dashboards)
**Socioeconômico:** 2 histórias (coleta + dashboards)

### Observações

- Todas as histórias foram validadas e estão prontas para implementação
- A priorização reflete as necessidades operacionais de coleta e análise ambiental
- As histórias de alta prioridade são fundamentais para o MVP do sistema
- As histórias de baixa prioridade agregam valor analítico mas podem ser implementadas em fases posteriores
- O foco principal está na coleta de dados e funcionalidades básicas de distribuição
