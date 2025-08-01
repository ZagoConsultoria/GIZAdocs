# Ficha de Coleta - Engeform

## Introdução

Este documento consolida todas as fichas de coleta de dados do módulo Engeform, organizadas por meio ambiental. O sistema abrange a coleta estruturada de dados para estudos de impacto ambiental (EIA), contemplando aspectos socioeconômicos, físicos e bióticos.

### Resumo por Meio Ambiental

#### Meio Socioeconômico

- **Fichas**: 1
  - Ficha de Coleta Socio (35 campos estruturados)
- **Status**: ✅ Completo

#### Meio Físico

- **Fichas**: 6
  - Cavidades - Espeleologia
  - Hidrologia - Recursos Hídricos Superficiais
  - Solos - Pedologia
  - Solos - Geomorfologia
  - Ruídos e Efeito Estroboscópico
  - Sismicidade
- **Pendências**: 2
  - Hidrogeologia (não existe)
  - Coleta de Água da 304 (pendente)
- **Status**: 🟡 Parcialmente completo

#### Meio Biótico

- **Fichas**: 3
  - Fauna
  - Flora - Caracterização Florística
  - Flora - Inventário Florestal
- **Status**: ✅ Completo

### Totais

- **Fichas de coleta**: 10
- **Fichas pendentes**: 2
- **Survey123**: 2 formulários
- **Fichas estruturadas**: 8

---

## Meio Socio

| **Campo**                                        | **Tipo de Resposta** | **Opções/Formato**                                                                      |
| ------------------------------------------------ | -------------------- | --------------------------------------------------------------------------------------- |
| Data da Entrevista                               | Data                 | Data (dd/mm/aaaa)                                                                       |
| Nome da Comunidade/Localidade                    | Texto                | Campo de texto livre                                                                    |
| Entrevistado(a) – Nome Completo                  | Texto                | Campo de texto livre                                                                    |
| Sexo                                             | Seleção única        | Masculino; Feminino; Outro                                                              |
| Idade                                            | Numérico             | Valor numérico                                                                          |
| Telefone de Contato                              | Numérico             | Número com DDD                                                                          |
| Coordenadas geográficas                          | Geolocalização       | Latitude / Longitude                                                                    |
| Tempo de residência no local                     | Seleção única        | Menos de 1 ano; 1 a 5 anos; 6 a 10 anos; Mais de 10 anos                                |
| Naturalidade                                     | Texto                | Município/Estado                                                                        |
| Número de pessoas na residência                  | Numérico             | Valor numérico                                                                          |
| Faixa etária dos moradores                       | Seleção múltipla     | Crianças (0–12); Adolescentes (13–17); Adultos (18–59); Idosos (60+)                    |
| Grau de escolaridade do entrevistado             | Seleção única        | Analfabeto; Ensino Fundamental Incompleto/Completo; Médio Incompleto/Completo; Superior |
| Fonte de renda principal da família              | Seleção única        | Agricultura; Comércio; Serviço público; Trabalho informal; Bolsa Família; Outros        |
| Valor médio da renda mensal familiar (R$)        | Numérico             | Valor em reais                                                                          |
| Recebe algum benefício social?                   | Seleção única        | Sim; Não                                                                                |
| Se sim, qual(is)?                                | Seleção múltipla     | Bolsa Família; BPC; Aposentadoria; Auxílio Brasil; Outros                               |
| Possui documento de posse ou escritura?          | Seleção única        | Sim; Não                                                                                |
| Tipo de moradia                                  | Seleção única        | Alvenaria; Madeira; Taipa; Mista; Palafita                                              |
| Condição da moradia                              | Seleção única        | Boa; Regular; Precária                                                                  |
| Acesso à energia elétrica?                       | Seleção única        | Sim; Não                                                                                |
| Acesso à água potável?                           | Seleção única        | Sim; Não                                                                                |
| Fonte de abastecimento de água                   | Seleção única        | Poço; Cisterna; Carro-pipa; Rede pública; Outro                                         |
| Acesso à coleta de lixo?                         | Seleção única        | Sim; Não                                                                                |
| Sistema de esgotamento sanitário                 | Seleção única        | Rede pública; Fossa; Céu aberto; Não possui                                             |
| Distância até escola mais próxima (km)           | Numérico             | Valor em quilômetros                                                                    |
| Distância até unidade de saúde mais próxima (km) | Numérico             | Valor em quilômetros                                                                    |
| Frequenta alguma associação ou coletivo?         | Seleção única        | Sim; Não                                                                                |
| Qual(is)?                                        | Seleção múltipla     | Associação de moradores; Igreja; Sindicato; Cooperativa; Outro                          |
| Usa o território para subsistência?              | Seleção única        | Sim; Não                                                                                |
| Se sim, como?                                    | Seleção múltipla     | Agricultura; Extrativismo; Criação de animais; Pesca; Outros                            |
| Conhece o projeto em análise?                    | Seleção única        | Sim; Não                                                                                |
| O que espera do projeto?                         | Texto livre          | Campo de resposta aberta                                                                |
| Tem alguma preocupação com o projeto?            | Texto livre          | Campo de resposta aberta                                                                |
| Sugestão de contrapartida da empresa             | Texto livre          | Campo de resposta aberta                                                                |
| Registro Fotográfico                             | Arquivo/Link         | Número ou link das fotos associadas                                                     |
| Outras observações relevantes                    | Texto livre          | Campo de resposta aberta                                                                |

## Meio Físico

### Cavidades - Ficha de Campo Espeleologia

#### Campos Gerais

| **Campo**          | **Tipo de Resposta**       | **Opções/Formato**                                                  |
| ------------------ | -------------------------- | ------------------------------------------------------------------- |
| ID                 | Numérico (Auto-incremento) | Campo de número inteiro (gerado automaticamente em ordem crescente) |
| Ponto Inspecionado | Geolocalização             | Localização georreferenciada automática                             |
| É uma caverna?     | Seleção única              | Sim; Não                                                            |

#### Se SIM (É uma caverna)

| **Campo**             | **Tipo de Resposta**                | **Opções/Formato**                                                                          |
| --------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------- |
| Foto                  | Arquivo/Múltiplo                    | 10 fotos obrigatórias                                                                       |
| Toponímia             | Texto livre                         | Nome da caverna (como a comunidade chama)                                                   |
| Uso                   | Seleção única + Texto condicional   | Vegetação; Área antropizada; Corpo d'água; Manancial; Outros (campo textual para descrição) |
| Aspecto Geológico     | Texto livre                         | Descrição das características geológicas                                                    |
| Forma                 | Texto livre                         | Descrição da forma da caverna                                                               |
| Orientação Geral      | Texto livre                         | Direcionamento/orientação da caverna                                                        |
| Dimensão das Galerias | Texto livre                         | Medidas e dimensões das galerias                                                            |
| Conteúdo Sedimentar   | Texto livre                         | Descrição dos sedimentos presentes                                                          |
| Conteúdo Hídrico      | Texto livre                         | Descrição da presença de água                                                               |
| Biota Cavernícola     | Seleção única + Arquivo condicional | Sim; Não (Se Sim: 10 fotos adicionais)                                                      |

#### Se NÃO (Não é uma caverna)

| **Campo**                   | **Tipo de Resposta**              | **Opções/Formato**                                                                          |
| --------------------------- | --------------------------------- | ------------------------------------------------------------------------------------------- |
| Foto                        | Arquivo/Múltiplo                  | 5 fotos obrigatórias                                                                        |
| Uso                         | Seleção única + Texto condicional | Vegetação; Área antropizada; Corpo d'água; Manancial; Outros (campo textual para descrição) |
| Litologia                   | Texto livre                       | Descrição das características das rochas                                                    |
| Fendas                      | Texto livre                       | Descrição de fendas e fraturas                                                              |
| Vegetação sobre Afloramento | Seleção única                     | Sim; Não                                                                                    |
| Outras Observações          | Texto livre                       | Observações gerais relevantes                                                               |

### Hidrogeologia

NÃO EXISTE

### Hidrologia - Ficha de Campo EIA - Recursos Hídricos Superficiais

| **Campo**                           | **Tipo de Resposta**                | **Opções/Formato**                                                   |
| ----------------------------------- | ----------------------------------- | -------------------------------------------------------------------- |
| ID                                  | Numérico (Auto-incremento)          | Campo de número inteiro (gerado automaticamente)                     |
| Localização                         | Geolocalização                      | Coordenadas geográficas automáticas                                  |
| Registro fotográfico                | Arquivo/Múltiplo                    | 5 fotos obrigatórias                                                 |
| Cobertura vegetal nas margens       | Seleção única                       | Preservada; Alterada; Erosão                                         |
| Presença de sedimentos em suspensão | Seleção única                       | Sim; Não                                                             |
| Espuma / óleo visível               | Seleção única                       | Sim; Não                                                             |
| Fontes de poluição                  | Seleção única + Texto condicional   | Pontual; Difusa (seguido de campo textual para descrição)            |
| Descrição da fonte de poluição      | Texto livre (condicional)           | Campo textual descritivo (aparece após seleção de pontual ou difusa) |
| Nível                               | Seleção única                       | Normal; Baixo; Alto                                                  |
| Condições climáticas                | Seleção única                       | Ensolarado; Parcialmente nublado; Nublado; Chuvoso; Chuva forte      |
| Tipo de corpo d'água                | Seleção única + Campos condicionais | Curso d'água; Massa d'água; Manancial                                |

### Coleta de Água da 304

**Pendente**: Adicionar ficha de coleta de água específica da norma 304

### Ruídos e Efeito Estroboscópico

Esta ficha de coleta utiliza formulário Survey123 já configurado:

**Link do formulário**: [Survey123 - Ruídos e Efeito Estroboscópico](https://survey123.arcgis.com/share/ad6624c98048441b9f5271677ead2503)

### Sismicidade

    Não tem

### Solos

#### Pedologia - Ficha de Campo EIA

| **Campo**                                 | **Tipo de Resposta**        | **Opções/Formato**                                                                             |
| ----------------------------------------- | --------------------------- | ---------------------------------------------------------------------------------------------- |
| ID                                        | Numérico (Auto-incremento)  | Campo de número inteiro (gerado automaticamente)                                               |
| Localização                               | Geolocalização              | Coordenadas geográficas automáticas                                                            |
| Pedregosidade                             | Seleção única + Condicional | Não; Sim (Se Sim: Baixa; Média; Alta)                                                          |
| Presença de raízes/fauna                  | Seleção múltipla            | Minhocas; Formigas; Raízes visíveis; Outro                                                     |
| Consistência do solo                      | Seleção única               | Seca; Úmida; Molhada                                                                           |
| Cor do solo (horizonte A)                 | Seleção única               | Preto; Marrom; Vermelho; Amarelo; Cinza                                                        |
| Textura aparente                          | Seleção única               | Arenoso; Argiloso; Humoso; Calcário                                                            |
| Profundidade do perfil                    | Seleção única               | Rasos (<50 cm); Pouco profundos (50-100 cm); Profundos (100-200 cm); Muito profundos (>200 cm) |
| Presença de lençol freático/encharcamento | Seleção única               | Não; Sim                                                                                       |
| Registro fotográfico                      | Arquivo/Múltiplo            | 5 fotos obrigatórias                                                                           |
| Outras observações                        | Texto livre                 | Campo de resposta aberta                                                                       |

#### Geomorfologia - Ficha de Campo EIA (Relevo e Paisagens)

| **Campo**                 | **Tipo de Resposta**                 | **Opções/Formato**                                                                       |
| ------------------------- | ------------------------------------ | ---------------------------------------------------------------------------------------- |
| ID                        | Numérico (Auto-incremento)           | Campo de número inteiro (gerado automaticamente)                                         |
| Localização               | Geolocalização                       | Coordenadas geográficas automáticas                                                      |
| Registro fotográfico      | Arquivo/Múltiplo                     | 5 fotos obrigatórias                                                                     |
| Forma de relevo dominante | Seleção única + Texto condicional    | Planície; Terraço; Colina; Morro; Planalto; Depressão; Escarpa; Outros (campo textual)   |
| Presença de corpo hídrico | Seleção única + Múltipla condicional | Não; Sim (Se Sim: Curso d'água; Massa d'água; Alagamento; Manancial)                     |
| Uso atual do solo         | Seleção múltipla                     | Agricultura; Pastagem; Vegetação densa; Vegetação esparsa; Área urbana; Mineração; Outro |
| Processos erosivos        | Seleção múltipla                     | Erosão hídrica; Movimentos de massa; Sedimentação; Ausência de processos visíveis        |
| Outras observações        | Texto livre                          | Campo de resposta aberta                                                                 |

## Meio Biótico - Fauna

**Link do formulário**: [Survey123 - Fauna](https://survey123.arcgis.com/share/ad6624c98048441b9f5271677ead2503)

## Meio Biótico - Flora

### Ficha de Caracterização Florística

#### Dados de Localização e Identificação

| **Campo**              | **Tipo de Resposta** | **Opções/Formato**                                 |
| ---------------------- | -------------------- | -------------------------------------------------- |
| Módulo/Conglomerado    | Texto/Código         | Identificação do módulo ou conglomerado            |
| Condição Climática     | Seleção única        | Ensolarado; Nublado; Chuvoso; Parcialmente nublado |
| Área de Influência     | Seleção única        | ADA; AE                                            |
| Subparcela             | Numérico             | Número da subparcela                               |
| Folha                  | Texto                | Número da folha / Total de folhas                  |
| Data                   | Data                 | Data da coleta (DD/MM/AAAA)                        |
| Horário                | Hora                 | Horário da coleta (HH:MM)                          |
| Estado                 | Texto                | Estado da federação                                |
| Município              | Texto                | Nome do município                                  |
| Coordenadas UTM - Fuso | Numérico             | Número do fuso UTM                                 |
| Coordenada E (Leste)   | Numérico             | Coordenada UTM Leste                               |
| Coordenada N (Norte)   | Numérico             | Coordenada UTM Norte                               |
| Altitude               | Numérico             | Altitude em metros                                 |

#### Características da Vegetação

| **Campo**                                     | **Tipo de Resposta** | **Opções/Formato**                                                 |
| --------------------------------------------- | -------------------- | ------------------------------------------------------------------ |
| Fitofisionomia predominante                   | Texto livre          | Descrição da fitofisionomia                                        |
| Estágio sucessional                           | Seleção única        | Pioneiro; Inicial; Médio; Avançado; Clímax                         |
| Estado de conservação predominante            | Seleção única        | Preservada; Alterada; Muito Alterada                               |
| Formas de vida presentes                      | Seleção múltipla     | Árvores; Arbustos; Subarbustos; Ervas; Epífitas; Lianas; Parasitas |
| Classificação do Sub-bosque                   | Seleção única        | Denso; Médio; Ralo                                                 |
| Serrapilheira                                 | Seleção única        | Ausente; Fina; Média; Espessa                                      |
| Cobertura de Dossel                           | Seleção única        | Aberto; Intermediário; Fechado                                     |
| Altura média da vegetação                     | Seleção única        | < 4 m; 4 a 10 m; > 10 m                                            |
| Cipós/Lianas/Epífitas/Palmeiras/Cactos/Bambus | Seleção única        | Presente; Ausente                                                  |

#### Características Ambientais e do Solo

| **Campo**                 | **Tipo de Resposta** | **Opções/Formato**                                                 |
| ------------------------- | -------------------- | ------------------------------------------------------------------ |
| Textura visual do solo    | Seleção múltipla     | Afl. Rochas; Pedregoso; Arenoso; Areno-argiloso; Argiloso; Siltoso |
| Topografia/Declividade    | Seleção única        | 0 a 5º; 6 a 15º; 16 a 30º; > 30º                                   |
| Acesso à Unidade Amostral | Seleção única        | Fácil; Com restrição; Difícil                                      |

#### Observações e Descrições

| **Campo**                                         | **Tipo de Resposta**  | **Opções/Formato**                                                   |
| ------------------------------------------------- | --------------------- | -------------------------------------------------------------------- |
| Características Ambientais do Fragmento Florestal | Texto livre           | Descrição da vegetação, estágio sucessional, perturbações antrópicas |
| Ocorrência notável não mapeada                    | Seleção única + Texto | Não; Sim (Se Sim: campo descritivo)                                  |
| Observações Gerais                                | Texto livre           | Aspectos gerais, dificuldades de acesso, riscos ocupacionais         |
| Levantamento Florístico                           | Texto livre           | Dados específicos do levantamento florístico                         |

**Link do formulário**: [Ficha de Caracterização Florística](https://grupozago.sharepoint.com/:w:/s/BR-304RN/Ea2hr-HqFZtPkz-qbMLpaFoBAVGKwRxZuFWf_nn2kobgxw?e=t7NUcV)

### Ficha de Campo - Inventário Florestal

#### Dados de Identificação da Parcela

| **Campo** | **Tipo de Resposta** | **Opções/Formato**                        |
| --------- | -------------------- | ----------------------------------------- |
| Local     | Texto livre          | Nome do local de coleta                   |
| Data      | Data                 | Data da coleta (DD/MM/AAAA)               |
| Parcela   | Texto/Numérico       | Identificação da parcela                  |
| APP       | Seleção única        | Sim; Não (Área de Preservação Permanente) |

#### Registro de Espécies Vegetais

| **Campo**   | **Tipo de Resposta** | **Opções/Formato**                               |
| ----------- | -------------------- | ------------------------------------------------ |
| Nº          | Numérico             | Número sequencial do indivíduo (auto-incremento) |
| Espécie     | Texto livre          | Nome científico da espécie                       |
| CAP         | Numérico (decimal)   | Circunferência à Altura do Peito em centímetros  |
| Altura      | Numérico (decimal)   | Altura estimada em metros                        |
| Observações | Texto livre          | Observações específicas sobre o indivíduo        |
