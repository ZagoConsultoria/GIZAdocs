# Ficha de Coleta - Eletronorte

## Introdução

Este documento apresenta as fichas de coleta de dados para o módulo **Eletronorte**, focado no acompanhamento de atividades de viveiro e gestão de mudas para o projeto da Estação Ecológica (ESEC). O sistema visa automatizar a coleta de dados diários do viveiro, substituindo formulários manuais e integrando com sistemas de relatórios automatizados.

## Ficha de Acompanhamento Diário - Viveiro

### Seção 1: Dados Gerais

| **Campo**                              | **Tipo de Resposta** | **Opções/Formato**            |
| -------------------------------------- | -------------------- | ----------------------------- |
| Data                                   | Data                 | Data (dd/mm/aaaa)             |
| Nome do responsável pelo preenchimento | Lista suspensa       | Lista de usuários cadastrados |
| Horário da visita/atividade            | Hora                 | Formato HH:MM                 |
| Clima predominante no dia              | Seleção única        | Sol / Nublado / Chuva / Outro |
| Observações climáticas                 | Texto livre          | Campo aberto para detalhes    |

### Seção 2: Irrigação

| **Campo**                                    | **Tipo de Resposta** | **Opções/Formato**                     |
| -------------------------------------------- | -------------------- | -------------------------------------- |
| A irrigação foi realizada hoje?              | Sim/Não              | Sim / Não                              |
| Quantas vezes no dia foi realizada?          | Numérico             | Número inteiro                         |
| Tempo médio de irrigação por turno (minutos) | Numérico             | Número inteiro                         |
| Setor irrigado                               | Seleção única        | Casa de sombra; Pleno sol              |
| Observações sobre o funcionamento do sistema | Texto longo          | Falhas, ajustes, controle manual, etc. |
| Fotos da irrigação                           | Upload múltiplo      | Anexar múltiplas imagens               |

### Seção 3: Adubação

| **Campo**                                 | **Tipo de Resposta** | **Opções/Formato**            |
| ----------------------------------------- | -------------------- | ----------------------------- |
| Houve adubação hoje?                      | Sim/Não              | Sim; Não                      |
| Tipo de adubo utilizado                   | Seleção múltipla     | Mineral; Foliar; Outro        |
| Especificar outro tipo de adubo           | Texto livre          | Campo aberto para especificar |
| Quais espécies/mudas foram adubadas?      | Texto longo          | Listagem das espécies         |
| Adubação está seguindo o cronograma?      | Sim/Não              | Sim; Não                      |
| Se não está seguindo cronograma, por quê? | Texto livre          | Justificativa do desvio       |
| Observações sobre adubação                | Texto longo          | Informações complementares    |
| Fotos da adubação                         | Upload múltiplo      | Anexar múltiplas imagens      |

### Seção 4: Pragas e Doenças

| **Campo**                                 | **Tipo de Resposta** | **Opções/Formato**              |
| ----------------------------------------- | -------------------- | ------------------------------- |
| Há sinais de pragas nas mudas?            | Sim/Não              | Sim; Não                        |
| Se sim, quais pragas foram identificadas? | Texto livre          | Descrição das pragas observadas |
| Há sintomas de doenças nas mudas?         | Sim/Não              | Sim; Não                        |
| Sintomas observados                       | Seleção múltipla     | Manchas; Murcha; Apodrecimento  |
| Outros sintomas observados                | Texto livre          | Descrição de outros sintomas    |
| Espécies afetadas (se identificadas)      | Texto livre          | Listagem das espécies afetadas  |
| Alguma medida de controle foi aplicada?   | Texto longo          | Descrição das medidas aplicadas |
| Fotos de pragas e doenças                 | Upload múltiplo      | Anexar múltiplas imagens        |

### Seção 5: Manutenção e Atividades Gerais

| **Campo**                                     | **Tipo de Resposta** | **Opções/Formato**                |
| --------------------------------------------- | -------------------- | --------------------------------- |
| Foi realizada capina ou limpeza das bancadas? | Sim/Não              | Sim; Não                          |
| Alguma muda foi descartada ou substituída?    | Sim/Não              | Sim; Não                          |
| Quantas mudas foram descartadas?              | Numérico             | Número inteiro                    |
| Houve replantio ou transferência de mudas?    | Sim/Não              | Sim; Não                          |
| Houve manutenção de equipamentos?             | Sim/Não              | Bandejas, ferramentas, irrigação  |
| Se sim, qual tipo de manutenção?              | Texto livre          | Descrição da manutenção realizada |
| Observações sobre a manutenção geral          | Texto longo          | Informações complementares        |
| Fotos das atividades de manutenção            | Upload múltiplo      | Anexar múltiplas imagens          |

### Seção 6: Plantio

| **Campo**                            | **Tipo de Resposta** | **Opções/Formato** |
| ------------------------------------ | -------------------- | ------------------ |
| Qual espécie foi plantada (semeada)? | Texto livre          | Nome da espécie    |
| Quantidade de sementes?              | Numérico             | Número inteiro     |
| Tipo de semeadura?                   | Seleção única        | Direta; Indireta   |
| Data de plantio                      | Data                 | dd/mm/aaaa         |

### Seção 7: Coleta de sementes

| **Campo**       | **Tipo de Resposta** | **Opções/Formato** |
| --------------- | -------------------- | ------------------ |
| Data de coleta? | Data                 | dd/mm/aaaa         |
| Local?          | Texto livre          | Nome do local      |

### Seção 8: Observações Gerais

| **Campo**                         | **Tipo de Resposta** | **Opções/Formato**                   |
| --------------------------------- | -------------------- | ------------------------------------ |
| Ocorrências do dia                | Texto longo          | Espaço livre para anotar ocorrências |
| Sugestões de melhoria             | Texto longo          | Espaço livre para sugestões          |
| Destaques e observações especiais | Texto longo          | Espaço livre para destaques          |

---

### Seção 9: Contagem de Mudas Detalhada

**Espécies Disponíveis:**

- Amburana — Amburana cearensis
- Angico vermelho — Anadenanthera macrocarpa
- Aroeira — Astronium urundeuva
- Cagaita — Eugenia dysenterica
- Candeia — Plathymenia foliolosa
- Chicha — Sterculia striata
- Copaíba — Copaifera langsdorffii
- Embaúba — Cecropia pachystachya
- Ipê-amarelo felpudo — Zeyheria tuberculosa
- Ipê-branco — Tabebuia roseo-alba
- Ipê-rosa — Handroanthus heptaphyllus
- Ipê-roxo — Handroanthus impetiginosus
- Jacarandá — Jacaranda micrantha
- Jurema-branca — Mimosa verrucosa
- Mutamba — Guazuma ulmifolia
- Pacari — Lafoensia pacari
- Parkia — Parkia platycephala

**Fluxo de uso:**

1. Selecionar a espécie.
2. Informar a altura individual de 20 mudas da espécie selecionada (cm).
3. Informar a quantidade total de mudas da espécie selecionada.
4. Informar a quantidade de mudas mortas da espécie selecionada.
5. Repetir para outras espécies ou salvar ao finalizar.

| Campo                      | Tipo de Resposta | Opções/Formato                |
| -------------------------- | ---------------- | ----------------------------- |
| Espécie                    | Seleção única    | Lista de espécies (ver acima) |
| Altura (cm)        | Numérico decimal | Valor em cm (ex.: 20,0)       |
| Quantidade total de mudas  | Numérico inteiro | Número inteiro                |
| Quantidade de mudas mortas | Numérico inteiro | Número inteiro                |

### Seção 10: Metadados Automáticos (Capturados pelo Sistema)

| **Campo**            | **Tipo de Captura** | **Formato**                |
| -------------------- | ------------------- | -------------------------- |
| Coordenadas GPS      | Automática          | Latitude/Longitude (WGS84) |
| Timestamp de criação | Automática          | dd/mm/aaaa HH:MM:SS        |
