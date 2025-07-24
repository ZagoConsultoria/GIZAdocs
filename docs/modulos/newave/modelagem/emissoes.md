## Introdução

Durante o processo de elicitação de requisitos com a analista ambiental Bruna Ferrari, foram identificadas diversas necessidades relacionadas à coleta, organização e apresentação de dados ambientais, especialmente no contexto do monitoramento de fumaça preta e gases. Com base nas funcionalidades levantadas, priorizadas com a técnica dos 100 dólares, elaboramos histórias de usuário que representam, de forma clara e objetiva, o que o sistema deve permitir que o usuário realize.

Essas histórias servirão como base para o desenvolvimento incremental da solução, permitindo que os entregáveis sejam organizados de acordo com o valor percebido pelo usuário final, reduzindo retrabalho e aumentando a aderência do sistema às operações reais de campo e escritório.

## Objetivo

O objetivo deste documento é apresentar as histórias de usuário que descrevem, do ponto de vista da analista ambiental, as funcionalidades desejadas no sistema. Cada história está associada a um requisito funcional previamente elicitado e tem por finalidade guiar o time de desenvolvimento quanto às expectativas de uso, critérios de aceitação e priorização, facilitando a organização do backlog e a comunicação entre equipe técnica e usuários.

# [US01-NW] - Coletar dados via ZS {#us01-nw}

### Tabela 1: História de Usuário – Coletar dados via ZS

| Item                         | Descrição                                                                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01-NW                                                                                                                                                                                            |
| Tema                         | Coletar dados via ZS                                                                                                                                                                               |
| Descrição                    | Eu, como analista ambiental, desejo realizar a coleta de dados de fumaça preta e gases diretamente no ZS para substituir o uso do celular e garantir padronização e rastreabilidade dos registros. |
| Critérios de Aceitação       | - A ficha de coleta deve estar disponível no ZS.<br>- Deve ser possível preencher os dados por tipo de gás.<br>- Os dados devem ser salvos no banco.                                               |
| Prioridade Usuário           | Alta                                                                                                                                                                                               |
| Status                       | Validada                                                                                                                                                                                           |
| Rastreabilidade              | RF01-NW                                                                                                                                                                                            |

# [US02-NW] - Utilizar sistema offline {#us02-nw}

### Tabela 2: História de Usuário – Funcionamento offline

| Item                         | Descrição                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02-NW                                                                                                                                        |
| Tema                         | Utilizar sistema offline                                                                                                                       |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema funcione offline durante as coletas para que eu possa registrar os dados mesmo sem internet. |
| Critérios de Aceitação       | - O sistema deve abrir e registrar dados sem conexão.<br>- Os dados devem ser sincronizados assim que houver conexão disponível.               |
| Prioridade Usuário           | Alta                                                                                                                                           |
| Status                       | Validada                                                                                                                                       |
| Rastreabilidade              | RF04-NW                                                                                                                                        |

# [US03-NW] - Organizar dados por gás {#us03-nw}

### Tabela 3: História de Usuário – Organizar dados por gás

| Item                         | Descrição                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US03-NW                                                                                                                                                      |
| Tema                         | Organizar dados por gás                                                                                                                                      |
| Descrição                    | Eu, como analista ambiental, desejo preencher uma ficha com os parâmetros CO₂, CO e SO₂ organizados por ponto de coleta, para facilitar a análise posterior. |
| Critérios de Aceitação       | - Cada ponto deve conter os três gases.<br>- Os campos devem estar organizados de forma clara.<br>- Os dados devem ser salvos corretamente.                  |
| Prioridade Usuário           | Alta                                                                                                                                                         |
| Status                       | Validada                                                                                                                                                     |
| Rastreabilidade              | RF02-NW                                                                                                                                                      |

# [US04-NW] - Enviar fotos automaticamente {#us04-nw}

### Tabela 4: História de Usuário – Enviar fotos automaticamente

| Item                         | Descrição                                                                                                                                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04-NW                                                                                                                                                    |
| Tema                         | Enviar fotos automaticamente                                                                                                                               |
| Descrição                    | Eu, como analista ambiental, desejo que as fotos da coleta sejam salvas automaticamente no GIZA e no SharePoint para não precisar fazer uploads manuais.   |
| Critérios de Aceitação       | - As fotos devem ser anexadas ao registro.<br>- As evidências devem ser salvas no GIZA.<br>- As mesmas fotos devem aparecer na pasta padrão do SharePoint. |
| Prioridade Usuário           | Alta                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                   |
| Rastreabilidade              | RF03-NW                                                                                                                                                    |

# [US05-NW] - Armazenar dados com segurança {#us05-nw}

### Tabela 5: História de Usuário – Armazenar dados

| Item                         | Descrição                                                                                                                       |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05-NW                                                                                                                         |
| Tema                         | Armazenar dados com segurança                                                                                                   |
| Descrição                    | Eu, como analista ambiental, desejo que os dados coletados fiquem armazenados de forma segura para evitar perda de informações. |
| Critérios de Aceitação       | - Os dados devem ser salvos em banco com backup automático.<br>- A confidencialidade deve ser garantida.                        |
| Prioridade Usuário           | Alta                                                                                                                            |
| Status                       | Validada                                                                                                                        |
| Rastreabilidade              | RF05-NW                                                                                                                         |

# [US06-NW] - Notificar sobre problemas na análise {#us06-nw}

### Tabela 6: História de Usuário – Notificar problemas

| Item                         | Descrição                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06-NW                                                                                                                                            |
| Tema                         | Baixar fotos por lote ou registro                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo poder baixar todas as fotos da coleta em lote ou individualmente, para facilitar a organização dos relatórios. |
| Critérios de Aceitação       | - Deve haver botão de download por coleta e por foto.<br>- As imagens devem manter qualidade original.                                             |
| Prioridade Usuário           | Alta                                                                                                                                               |
| Status                       | Validada                                                                                                                                           |
| Rastreabilidade              | RF08-NW                                                                                                                                            |

# [US07-NW] - Comparar diferentes cenários {#us07-nw}

### Tabela 7: História de Usuário – Comparar cenários

| Item                         | Descrição                                                                                                                       |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US07-NW                                                                                                                         |
| Tema                         | Tabela com filtros e exportação                                                                                                 |
| Descrição                    | Eu, como analista ambiental, desejo visualizar os dados coletados em uma tabela filtrável e exportável para facilitar análises. |
| Critérios de Aceitação       | - A tabela deve permitir aplicar filtros por parâmetro.<br>- Deve ser possível exportar para Excel ou CSV.                      |
| Prioridade Usuário           | Alta                                                                                                                            |
| Status                       | Validada                                                                                                                        |
| Rastreabilidade              | RF09-NW                                                                                                                         |

# [US08-NW] - Configurar sistema para cenários específicos {#us08-nw}

### Tabela 8: História de Usuário – Configurar sistema

| Item                         | Descrição                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US08-NW                                                                                                                                                                           |
| Tema                         | Integrações com ZS, GIZA e TimeStamp                                                                                                                                              |
| Descrição                    | Eu, como analista ambiental, desejo que o sistema seja integrado ao ZS, GIZA e TimeStamp para garantir o fluxo contínuo de dados entre as plataformas.                            |
| Critérios de Aceitação       | - O sistema deve importar/exportar dados com o ZS.<br>- As fotos e dados devem aparecer automaticamente no GIZA.<br>- Os registros devem ser associados a data/hora do TimeStamp. |
| Prioridade Usuário           | Média                                                                                                                                                                             |
| Status                       | Validada                                                                                                                                                                          |
| Rastreabilidade              | RF06-NW                                                                                                                                                                           |

# [US09-NW] - Monitorar desempenho em tempo real {#us09-nw}

### Tabela 9: História de Usuário – Monitorar desempenho

| Item                         | Descrição                                                                                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US09-NW                                                                                                                                                                        |
| Tema                         | Visualização com farol de cor                                                                                                                                                  |
| Descrição                    | Eu, como analista ambiental, desejo visualizar uma tabela com alertas em cores (farol) para identificar rapidamente parâmetros fora do padrão, como fumaça preta acima de 40%. |
| Critérios de Aceitação       | - A tabela deve aplicar cores conforme os valores dos parâmetros.<br>- Parâmetros fora do limite devem ser destacados em vermelho.                                             |
| Prioridade Usuário           | Média                                                                                                                                                                          |
| Status                       | Validada                                                                                                                                                                       |
| Rastreabilidade              | RF07-NW                                                                                                                                                                        |

# [US10-NW] - Exportar dados para Excel {#us10-nw}

### Tabela 10: História de Usuário – Exportação para Excel

| Item                         | Descrição                                                                                                                                                       |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US10-NW                                                                                                                                                         |
| Tema                         | Exportação de dados para planilha Excel                                                                                                                         |
| Descrição                    | Eu, como analista ambiental, desejo exportar os dados coletados para uma planilha Excel com formatação adequada, para facilitar análises e relatórios externos. |
| Critérios de Aceitação       | - O arquivo Excel deve conter todos os dados da coleta.<br>- A formatação deve ser adequada para análise.<br>- Deve incluir filtros automáticos nas colunas.    |
| Prioridade Usuário           | Média                                                                                                                                                           |
| Status                       | Validada                                                                                                                                                        |
| Rastreabilidade              | RF10-NW                                                                                                                                                         |

# [US11-NW] - Inserir dados complementares no relatório {#us11-nw}

### Tabela 11: História de Usuário – Inserção de dados manuais

| Item                         | Descrição                                                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US11-NW                                                                                                                                                                     |
| Tema                         | Inserção de dados manuais no relatório                                                                                                                                      |
| Descrição                    | Eu, como analista ambiental, desejo incluir manualmente dados complementares como particulados, gráficos e fotos no relatório, para garantir a entrega completa ao cliente. |
| Critérios de Aceitação       | - O Word gerado deve permitir edição livre.<br>- Deve ser possível adicionar gráficos e imagens facilmente.<br>- As tabelas devem ser compatíveis com formatação manual.    |
| Prioridade Usuário           | Baixa                                                                                                                                                                       |
| Status                       | Validada                                                                                                                                                                    |
| Rastreabilidade              | RF12-NW                                                                                                                                                                     |

# [US12-NW] - Gerar relatório conforme padrão regulatório {#us12-nw}

### Tabela 12: História de Usuário – Conformidade regulatória do relatório

| Item                         | Descrição                                                                                                                                                              |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US12-NW                                                                                                                                                                |
| Tema                         | Geração de relatório conforme padrão regulatório                                                                                                                       |
| Descrição                    | Eu, como analista ambiental, desejo que o relatório seja gerado conforme os padrões exigidos pelos órgãos ambientais, para garantir sua aceitação sem retrabalho.      |
| Critérios de Aceitação       | - O relatório deve seguir o modelo exigido.<br>- Deve conter campos obrigatórios definidos pela regulação.<br>- Deve ser compatível com as normas ambientais vigentes. |
| Prioridade Usuário           | Baixa                                                                                                                                                                  |
| Status                       | Validada                                                                                                                                                               |
| Rastreabilidade              | RF11-NW                                                                                                                                                                |
