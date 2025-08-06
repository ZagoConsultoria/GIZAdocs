# Ficha de Coleta - Eletronorte

## Introdução

Este documento apresenta as fichas de coleta de dados para o módulo **Eletronorte**, focado no acompanhamento de atividades de viveiro e gestão de mudas para o projeto da Estação Ecológica (ESEC). O sistema visa automatizar a coleta de dados diários do viveiro, substituindo formulários manuais e integrando com sistemas de relatórios automatizados.

### Resumo das Fichas

#### Acompanhamento de Viveiro

- **Fichas**: 1
  - Ficha de Acompanhamento Diário de Atividades no Viveiro (52 campos estruturados)
- **Funcionalidades**:
  - Coleta offline no ZS
  - Sincronização automática com GIZA
  - Sistema de favoritar fotos
  - Geração automática de relatórios
- **Status**: ✅ Completo

### Categorias de Dados

| **Categoria**        | **Quantidade de Campos** | **Obrigatórios** | **Opcionais** |
| -------------------- | ------------------------ | ---------------- | ------------- |
| Dados Gerais         | 5                        | 4                | 1             |
| Irrigação            | 7                        | 4                | 3             |
| Adubação             | 8                        | 4                | 4             |
| Pragas e Doenças     | 10                       | 5                | 5             |
| Manutenção           | 7                        | 5                | 2             |
| Registro Fotográfico | 4                        | 3                | 1             |
| Contagem de Mudas    | 8                        | 8                | 0             |
| Observações Gerais   | 3                        | 0                | 3             |
| **TOTAL**            | **52**                   | **33**           | **19**        |

---

## Ficha de Acompanhamento Diário - Viveiro

### Seção 1: Dados Gerais

| **Campo**                              | **Tipo de Resposta** | **Opções/Formato**            | **Obrigatório** |
| -------------------------------------- | -------------------- | ----------------------------- | --------------- |
| Data                                   | Data                 | Data (dd/mm/aaaa)             | ✅              |
| Nome do responsável pelo preenchimento | Lista suspensa       | Lista de usuários cadastrados | ✅              |
| Horário da visita/atividade            | Hora                 | Formato HH:MM                 | ✅              |
| Clima predominante no dia              | Seleção única        | Sol / Nublado / Chuva / Outro | ✅              |
| Observações climáticas                 | Texto livre          | Campo aberto para detalhes    | ❌              |

### Seção 2: Irrigação

| **Campo**                                    | **Tipo de Resposta** | **Opções/Formato**                     | **Obrigatório**         |
| -------------------------------------------- | -------------------- | -------------------------------------- | ----------------------- |
| A irrigação foi realizada hoje?              | Sim/Não              | Sim / Não                              | ✅                      |
| Quantas vezes no dia foi realizada?          | Numérico             | Número inteiro                         | ✅ (se irrigação = Sim) |
| Tempo médio de irrigação por turno (minutos) | Numérico             | Número inteiro                         | ✅ (se irrigação = Sim) |
| Setores irrigados - Casa de sombra           | Checkbox             | Marcação múltipla                      | ✅ (se irrigação = Sim) |
| Setores irrigados - Pleno sol                | Checkbox             | Marcação múltipla                      | ✅ (se irrigação = Sim) |
| Observações sobre o funcionamento do sistema | Texto longo          | Falhas, ajustes, controle manual, etc. | ❌                      |

### Seção 3: Adubação

| **Campo**                                 | **Tipo de Resposta** | **Opções/Formato**         | **Obrigatório**          |
| ----------------------------------------- | -------------------- | -------------------------- | ------------------------ |
| Houve adubação hoje?                      | Sim/Não              | Sim / Não                  | ✅                       |
| Tipo de adubo utilizado - Mineral         | Radio button         | Seleção única              | ✅ (se adubação = Sim)   |
| Tipo de adubo utilizado - Foliar          | Radio button         | Seleção única              | ✅ (se adubação = Sim)   |
| Tipo de adubo utilizado - Outro           | Radio button + Texto | Especificar tipo           | ✅ (se adubação = Sim)   |
| Quais espécies/mudas foram adubadas?      | Texto longo          | Listagem das espécies      | ✅ (se adubação = Sim)   |
| Adubação está seguindo o cronograma?      | Sim/Não              | Sim / Não                  | ✅ (se adubação = Sim)   |
| Se não está seguindo cronograma, por quê? | Texto livre          | Justificativa do desvio    | ✅ (se cronograma = Não) |
| Observações sobre adubação                | Texto longo          | Informações complementares | ❌                       |

### Seção 4: Pragas e Doenças

| **Campo**                                 | **Tipo de Resposta** | **Opções/Formato**              | **Obrigatório**              |
| ----------------------------------------- | -------------------- | ------------------------------- | ---------------------------- |
| Há sinais de pragas nas mudas?            | Sim/Não              | Sim / Não                       | ✅                           |
| Se sim, quais pragas foram identificadas? | Texto livre          | Descrição das pragas observadas | ✅ (se pragas = Sim)         |
| Há sintomas de doenças nas mudas?         | Sim/Não              | Sim / Não                       | ✅                           |
| Sintomas observados - Manchas             | Checkbox             | Múltipla seleção                | ✅ (se doenças = Sim)        |
| Sintomas observados - Murcha              | Checkbox             | Múltipla seleção                | ✅ (se doenças = Sim)        |
| Sintomas observados - Apodrecimento       | Checkbox             | Múltipla seleção                | ✅ (se doenças = Sim)        |
| Outros sintomas observados                | Texto livre          | Descrição de outros sintomas    | ❌                           |
| Espécies afetadas (se identificadas)      | Texto livre          | Listagem das espécies afetadas  | ✅ (se pragas/doenças = Sim) |
| Alguma medida de controle foi aplicada?   | Texto longo          | Descrição das medidas aplicadas | ❌                           |

### Seção 5: Manutenção e Atividades Gerais

| **Campo**                                     | **Tipo de Resposta** | **Opções/Formato**                | **Obrigatório**          |
| --------------------------------------------- | -------------------- | --------------------------------- | ------------------------ |
| Foi realizada capina ou limpeza das bancadas? | Sim/Não              | Sim / Não                         | ✅                       |
| Alguma muda foi descartada ou substituída?    | Sim/Não              | Sim / Não                         | ✅                       |
| Quantas mudas foram descartadas?              | Numérico             | Número inteiro                    | ✅ (se descarte = Sim)   |
| Houve replantio ou transferência de mudas?    | Sim/Não              | Sim / Não                         | ✅                       |
| Houve manutenção de equipamentos?             | Sim/Não              | Bandejas, ferramentas, irrigação  | ✅                       |
| Se sim, qual tipo de manutenção?              | Texto livre          | Descrição da manutenção realizada | ✅ (se manutenção = Sim) |
| Observações sobre a manutenção geral          | Texto longo          | Informações complementares        | ❌                       |

### Seção 6: Registro Fotográfico

| **Campo**                                 | **Tipo de Resposta** | **Opções/Formato**                   | **Obrigatório**        |
| ----------------------------------------- | -------------------- | ------------------------------------ | ---------------------- |
| Foram feitos registros fotográficos hoje? | Sim/Não              | Sim / Não                            | ✅                     |
| Upload de fotos                           | Upload múltiplo      | Anexar múltiplas imagens             | ✅ (se registro = Sim) |
| Descreva brevemente o que foi registrado  | Texto longo          | Descrição dos registros fotográficos | ✅ (se registro = Sim) |
| Sistema de favoritos para fotos           | Favoritar            | ⭐ Marcar fotos importantes          | ❌                     |

### Seção 7: Contagem e Medição de Mudas

| **Campo**                                    | **Tipo de Resposta** | **Opções/Formato**               | **Obrigatório**         |
| -------------------------------------------- | -------------------- | -------------------------------- | ----------------------- |
| A contagem de mudas foi atualizada hoje?     | Sim/Não              | Sim / Não                        | ✅                      |
| Foi realizada medição de altura ou diâmetro? | Sim/Não              | Sim / Não                        | ✅                      |
| Se sim, quais espécies foram medidas?        | Texto livre          | Listagem das espécies medidas    | ✅ (se medição = Sim)   |
| Altura média das mudas (cm)                  | Numérico decimal     | Valor com até 2 casas decimais   | ✅ (se medição = Sim)   |
| Diâmetro médio das mudas (mm)                | Numérico decimal     | Valor com até 2 casas decimais   | ✅ (se medição = Sim)   |
| Quantidade total de mudas                    | Numérico             | Número inteiro                   | ✅                      |
| Houve alteração significativa no número?     | Sim/Não              | Sim / Não                        | ✅                      |
| Se sim, especifique a alteração              | Texto livre          | Descrição da alteração observada | ✅ (se alteração = Sim) |
| As informações foram registradas em sistema? | Sim/Não              | Sim / Não                        | ✅                      |
| Qual sistema/local foi utilizado?            | Texto livre          | Nome do sistema ou local         | ✅ (se registro = Sim)  |

### Seção 8: Observações Gerais

| **Campo**                         | **Tipo de Resposta** | **Opções/Formato**                   | **Obrigatório** |
| --------------------------------- | -------------------- | ------------------------------------ | --------------- |
| Ocorrências do dia                | Texto longo          | Espaço livre para anotar ocorrências | ❌              |
| Sugestões de melhoria             | Texto longo          | Espaço livre para sugestões          | ❌              |
| Destaques e observações especiais | Texto longo          | Espaço livre para destaques          | ❌              |

### Seção 9: Metadados Automáticos (Capturados pelo Sistema)

| **Campo**             | **Tipo de Captura** | **Formato**                  | **Observações**                     |
| --------------------- | ------------------- | ---------------------------- | ----------------------------------- |
| Coordenadas GPS       | Automática          | Latitude/Longitude (WGS84)   | Geolocalização do ponto de coleta   |
| Timestamp de criação  | Automática          | dd/mm/aaaa HH:MM:SS          | Momento da criação do registro      |
| Usuário responsável   | Automática          | ID do usuário logado         | Rastreabilidade do responsável      |
| Dispositivo utilizado | Automática          | Modelo e sistema operacional | Informações técnicas do dispositivo |
| Versão do formulário  | Automática          | Número da versão             | Controle de versionamento           |

---

## Resumo Técnico

### Validações e Regras de Negócio

1. **Campos Condicionais**: 19 campos aparecem apenas quando condições específicas são atendidas
2. **Validações Numéricas**: Campos de medição devem aceitar valores decimais positivos
3. **Listas Suspensas**: Responsáveis devem ser cadastrados previamente no sistema
4. **Upload de Fotos**: Máximo de 10 fotos por registro, com sistema de favoritos
5. **Geolocalização**: Captura automática de GPS para rastreabilidade
6. **Backup Automático**: Dados salvos localmente até sincronização

### Integrações Previstas

- **ZenSurvey (ZS)**: Coleta de dados offline
- **GIZA**: Visualização e análise de dados
- **Mata Nativa**: Migração de dados históricos (análise necessária)
- **Google Drive**: Sincronização de fotos e documentos
- **SharePoint**: Backup e compartilhamento de relatórios

### Relatórios Automatizados

1. **Relatório Mensal de Atividades**: Baseado em todos os registros do mês
2. **Dashboard de Mudas**: Gráficos de crescimento e quantidade
3. **Alertas de Pragas/Doenças**: Notificações automáticas
4. **Controle de Irrigação**: Histórico e padrões de irrigação
5. **Indicadores de Produtividade**: Métricas de performance do viveiro
