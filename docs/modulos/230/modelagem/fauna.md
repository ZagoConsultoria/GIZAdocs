# Histórias de Usuário - Módulo 230

## Introdução

Com base no discovery realizado para o módulo **230**, estas histórias de usuário descrevem, do ponto de vista dos técnicos de campo e coordenadores, as funcionalidades desejadas para coleta, armazenamento, integração e geração de relatórios de dados de fauna.

## Objetivo

Apresentar as histórias de usuário que guiarão o desenvolvimento incremental do módulo 230, assegurando a entrega de valor desde as necessidades mais críticas.

---

## Histórias de Usuário

---

# [US01-230] - Coletar dados de fauna via ZS {#us01-230}

### Tabela 1: História de Usuário – Coletar dados de fauna via ZS

| Item                         | Descrição                                                                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-230                                                                                                                                                                                           |
| Tema                         | Coletar dados de fauna afungentada, atropelada e passagem via ZS com GPS e fotos                                                                                                                   |
| Descrição                    | Eu, como técnico de campo, desejo registrar dados de fauna afungentada, atropelada e passagem diretamente no ZS, com captura automática de coordenadas e fotos, para substituir processos manuais. |
| Critérios de Aceitação       | - Formulário digital para registro de atropelamentos.<br>- Captura automática de data, hora e GPS.<br>- Upload automático de fotos.<br>- Funcionamento offline.                                    |
| Prioridade Usuário           | Alta                                                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                                                           |
| Rastreabilidade              | RF01-230                                                                                                                                                                                           |

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

# [US06-230] - Separar nomenclatura científica e popular {#us06-230}

### Tabela 6: História de Usuário – Separar nomenclatura científica e popular

| Item                         | Descrição                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-230                                                                                                                                                         |
| Tema                         | Separar nome científico e nome popular em campos distintos                                                                                                       |
| Descrição                    | Eu, como analista de dados, desejo que o nome científico e nome popular sejam campos separados, para facilitar análises taxonômicas e relatórios especializados. |
| Critérios de Aceitação       | - Campo específico para nome científico.<br>- Campo específico para nome popular.<br>- Validação de preenchimento adequado.<br>- Busca independente por tipo.    |
| Prioridade Usuário           | Alta                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                         |
| Rastreabilidade              | RF06-230                                                                                                                                                         |

---

# [US07-230] - Padronizar coordenadas em formato UTM {#us07-230}

### Tabela 7: História de Usuário – Padronizar coordenadas em formato UTM

| Item                         | Descrição                                                                                                                                                   |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-230                                                                                                                                                    |
| Tema                         | Padronizar coordenadas automaticamente no formato UTM                                                                                                       |
| Descrição                    | Eu, como técnico de campo, desejo que as coordenadas sejam automaticamente convertidas para o formato UTM, para manter consistência nos dados geoespaciais. |
| Critérios de Aceitação       | - Conversão automática para UTM.<br>- Preservação da precisão.<br>- Indicação do fuso UTM utilizado.<br>- Compatibilidade com análises SIG.                 |
| Prioridade Usuário           | Alta                                                                                                                                                        |
| Status                       | Validada                                                                                                                                                    |
| Rastreabilidade              | RF07-230                                                                                                                                                    |

---

# [US08-230] - Implementar filtros funcionais de consulta {#us08-230}

### Tabela 8: História de Usuário – Implementar filtros funcionais de consulta

| Item                         | Descrição                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US08-230                                                                                                                                                         |
| Tema                         | Implementar filtros funcionais por supervisor, data e segmento                                                                                                   |
| Descrição                    | Eu, como coordenador, desejo filtrar registros por supervisor, data e segmento, para acompanhar o trabalho de equipe e analisar dados por período e localização. |
| Critérios de Aceitação       | - Filtro por supervisor operacional.<br>- Filtro por período/data funcional.<br>- Filtro por segmento ativo.<br>- Combinação de filtros possível.                |
| Prioridade Usuário           | Alta                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                         |
| Rastreabilidade              | RF08-230                                                                                                                                                         |

---

# [US09-230] - Editar registros após análise {#us09-230}

### Tabela 9: História de Usuário – Editar registros após análise

| Item                         | Descrição                                                                                                                                                                |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US09-230                                                                                                                                                                 |
| Tema                         | Permitir edição posterior dos registros para correção de espécies                                                                                                        |
| Descrição                    | Eu, como analista especializado, desejo editar registros existentes para corrigir identificação de espécies após análise laboratorial, mantendo histórico de alterações. |
| Critérios de Aceitação       | - Edição de campos de identificação.<br>- Histórico de alterações mantido.<br>- Controle de permissões de edição.<br>- Log de quem fez alterações.                       |
| Prioridade Usuário           | Alta                                                                                                                                                                     |
| Status                       | Validada                                                                                                                                                                 |
| Rastreabilidade              | RF09-230                                                                                                                                                                 |

---

# [US10-230] - Criar filtro para registros indeterminados {#us10-230}

### Tabela 10: História de Usuário – Criar filtro para registros indeterminados

| Item                         | Descrição                                                                                                                                                           |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-230                                                                                                                                                            |
| Tema                         | Criar filtro "indeterminado" para facilitar revisão de registros                                                                                                    |
| Descrição                    | Eu, como analista de dados, desejo filtrar registros marcados como "indeterminados", para priorizar a revisão de espécimes com identificação ainda incompleta.      |
| Critérios de Aceitação       | - Filtro específico para status "indeterminado".<br>- Marcação de registros como indeterminados.<br>- Contagem de registros pendentes.<br>- Priorização de revisão. |
| Prioridade Usuário           | Média                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                            |
| Rastreabilidade              | RF10-230                                                                                                                                                            |

---

# [US11-230] - Exportar dados estruturados {#us11-230}

### Tabela 11: História de Usuário – Exportar dados estruturados

| Item                         | Descrição                                                                                                                                                               |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-230                                                                                                                                                                |
| Tema                         | Exportar dados estruturados (Excel/CSV) com colunas pré-formatadas                                                                                                      |
| Descrição                    | Eu, como analista de dados, desejo exportar dados em Excel/CSV com colunas já separadas e formatadas, para eliminar retrabalho manual e acelerar análises estatísticas. |
| Critérios de Aceitação       | - Exportação em Excel e CSV.<br>- Colunas pré-formatadas e separadas.<br>- Dados prontos para análise.<br>- Eliminação de processamento manual pós-exportação.          |
| Prioridade Usuário           | Alta                                                                                                                                                                    |
| Status                       | Validada                                                                                                                                                                |
| Rastreabilidade              | RF11-230                                                                                                                                                                |

---

# [US12-230] - Gerar mapas interativos {#us12-230}

### Tabela 12: História de Usuário – Gerar mapas interativos

| Item                         | Descrição                                                                                                                                                           |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-230                                                                                                                                                            |
| Tema                         | Gerar mapas interativos mostrando pontos de coleta georreferenciados                                                                                                |
| Descrição                    | Eu, como coordenador, desejo visualizar mapas interativos com pontos de coleta de fauna, para análise espacial e planejamento de ações de conservação por programa. |
| Critérios de Aceitação       | - Mapas interativos dentro de cada programa.<br>- Pontos georreferenciados visíveis.<br>- Navegação e zoom funcionais.<br>- Filtragem por tipo de evento nos mapas. |
| Prioridade Usuário           | Média                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                            |
| Rastreabilidade              | RF12-230                                                                                                                                                            |

---

# [US13-230] - Exportar mapas em formatos compatíveis {#us13-230}

### Tabela 13: História de Usuário – Exportar mapas em formatos compatíveis

| Item                         | Descrição                                                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US13-230                                                                                                                                                                    |
| Tema                         | Exportar mapas em formatos compatíveis (KML/KMZ, shapefile)                                                                                                                 |
| Descrição                    | Eu, como analista GIS, desejo exportar mapas em formatos KML/KMZ e shapefile, para integração com QGIS e Google Earth em análises espaciais mais avançadas.                 |
| Critérios de Aceitação       | - Exportação em formato KML/KMZ.<br>- Exportação em formato shapefile.<br>- Compatibilidade com QGIS.<br>- Compatibilidade com Google Earth.<br>- Preservação de atributos. |
| Prioridade Usuário           | Média                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                    |
| Rastreabilidade              | RF13-230                                                                                                                                                                    |

---

# [US14-230] - Criar relatórios automáticos {#us14-230}

### Tabela 14: História de Usuário – Criar relatórios automáticos

| Item                         | Descrição                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US14-230                                                                                                                                                              |
| Tema                         | Criar modelos de relatório automáticos a partir da base de dados                                                                                                      |
| Descrição                    | Eu, como coordenador, desejo gerar relatórios automáticos padronizados a partir da base de dados, para agilizar a produção de documentos de acompanhamento e análise. |
| Critérios de Aceitação       | - Modelos de relatório pré-definidos.<br>- Geração automática a partir dos dados.<br>- Formatação profissional.<br>- Configuração de períodos para relatórios.        |
| Prioridade Usuário           | Baixa                                                                                                                                                                 |
| Status                       | Validada                                                                                                                                                              |
| Rastreabilidade              | RF14-230                                                                                                                                                              |

---

# [US15-230] - Capturar timestamp no momento do registro {#us15-230}

### Tabela 15: História de Usuário – Capturar timestamp no momento do registro

| Item                         | Descrição                                                                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US15-230                                                                                                                                                                                                                          |
| Tema                         | Capturar data e hora no momento exato do registro                                                                                                                                                                                 |
| Descrição                    | Eu, como técnico de campo, desejo que a data e hora sejam capturadas no momento exato da coleta de dados, independentemente de quando ocorre a sincronização, para garantir precisão temporal dos registros.                      |
| Critérios de Aceitação       | - Data e hora capturadas no momento do registro, não na sincronização.<br>- Timestamp local preservado durante operação offline.<br>- Sincronização mantém horário original de coleta.<br>- Fuso horário registrado corretamente. |
| Prioridade Usuário           | Alta                                                                                                                                                                                                                              |
| Status                       | Validada                                                                                                                                                                                                                          |
| Rastreabilidade              | RF15-230                                                                                                                                                                                                                          |
