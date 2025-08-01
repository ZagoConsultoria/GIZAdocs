# Discovery - Módulo Engeform

## Introdução

O módulo **Engeform** visa automatizar a coleta e gestão de dados para estudos de impacto ambiental (EIA), abrangendo tanto dados primários (coleta em campo) quanto dados secundários (consulta a bases governamentais). Este documento apresenta o mapeamento inicial dos meios ambientais e as soluções propostas para otimização dos processos.

## Objetivo

Desenvolver um sistema integrado que:

- **Automatize a coleta de dados primários** através de fichas digitais otimizadas
- **Agilize o levantamento de dados secundários** através de consultas automatizadas a APIs governamentais
- **Centralize o armazenamento e distribuição** dos dados coletados

---

## Mapeamento dos Meios Ambientais

### 🏔️ Meio Físico

#### Cavidades

- **Dados Secundários**: Consulta ao CANIE (Cadastro Nacional de Informações Espeleológicas)
- **Dados Primários**: Ficha de coleta para cavernas não cadastradas
- **Status**: ✅ Identificado

#### Hidrogeologia

- **Dados Secundários**: A definir
- **Dados Primários**: ⚠️ Ficha de coleta inexistente
- **Status**: 🔄 Pendente de esclarecimento

#### Hidrologia

- **Dados Secundários**: Não aplicável
- **Dados Primários**:
  - Ficha de recursos hídricos superficiais
  - Ficha de coleta de água (padrão 304)
- **Status**: ✅ Identificado

#### Ruídos e Efeitos Estroboscópicos

- **Dados Secundários**: Não aplicável
- **Dados Primários**: Ficha padrão de coleta de ruídos
- **Status**: ✅ Identificado (similar ao módulo Newave)

#### Sismicidade

- **Dados Secundários**: ⚠️ Fonte de dados a definir
- **Dados Primários**: Não aplicável
- **Status**: 🔄 Pendente de definição da fonte

#### Solos

- **Dados Secundários**: A definir necessidade
- **Dados Primários**:
  - Ficha de pedologia
  - Ficha de geomorfologia
- **Status**: ✅ Identificado

### 👥 Meio Socioeconômico

- **Dados Secundários**:
  - IBGE, INEP, DATASUS, SNIS, PNUD
  - SIGEF, FUNAI, INCRA, Fundação Palmares
- **Dados Primários**: Ficha de coleta socioeconômica
- **Status**: ✅ Identificado

### 🌿 Meio Biótico - Flora

- **Dados Secundários**:
  - Áreas protegidas
  - Uso do solo
  - Biomas e tipologias vegetais (⚠️ fonte a definir)
- **Dados Primários**: Duas fichas de coleta especializadas
- **Status**: 🔄 Fonte de dados secundários pendente

### 🦎 Meio Biótico - Fauna

- **Dados Secundários**:
  - Áreas alagadas sazonalmente
  - Metodologias para fauna rara, endêmica e ameaçada
- **Dados Primários**: Ficha de coleta faunística
- **Status**: ✅ Identificado

---

## Soluções Propostas

### 📱 Dados Primários (Coleta em Campo)

#### Coleta

- **Plataforma**: ZS com formulários otimizados
- **Características**:
  - Mínimo de campos textuais para reduzir erros humanos
  - Funcionamento offline
  - Fotos georreferenciadas (UTM) com marca d'água da empresa

#### Armazenamento

- **Sincronização**: Envio automático quando conectado à internet
- **Destinos**: GIZA e/ou SharePoint
- **Banco de dados**: Armazenamento estruturado

#### Distribuição

- **Interface**: Tabela filtrável no GIZA
- **Funcionalidades**:
  - Edição de registros
  - Visualização de evidências fotográficas
  - Filtragem e ordenação avançadas
  - Dashboards e gráficos (a definir necessidades específicas)

### 🤖 Dados Secundários (Consulta Automatizada)

#### Coleta

- **Solução**: Bot de raspagem de dados para cada fonte governamental
- **Objetivo**: Reduzir tempo de levantamento manual

#### Armazenamento

- **Estratégia**: A definir entre:
  - Cache local para otimização
  - Consulta em tempo real via APIs

#### Distribuição

- **Formato**: Planilhas estruturadas para análise
- **Integração**: Compatibilidade com ferramentas de análise existentes

---

## Questões para Validação

### ❓ Pontos que Precisam de Esclarecimento

1. **Hidrogeologia**: Confirmar se realmente é necessária ficha de coleta
2. **Sismicidade**: Definir fonte oficial de dados sísmicos
3. **Flora - Dados Secundários**: Identificar fonte para biomas e tipologias vegetais
4. **Armazenamento de Dados Secundários**: Cache local vs. consulta em tempo real
5. **Dashboards**: Definir métricas e visualizações necessárias

### ✅ Próximos Passos

1. Validação das suposições com stakeholders
2. Definição das fontes de dados pendentes
3. Priorização das funcionalidades por meio ambiental
4. Elaboração do cronograma de desenvolvimento

Gráficos que eles me passaram que já foram feitos em estudos anteriores, analisar quais são mais viáveis para por no dash e quais eles deveriam fazer manualmente: 

### Após a reunião de validação:

- Não vamos atuar nos dados secundários pois já foi feito pelo arlon
- Foi definido que será tabela filtravel
- ZS com as fichas para o Heitor

  Meio físico: 
    🕳️ Cavidades Naturais
Gráfico 5 – Relevância das Cavidades Naturais
Tipo: Gráfico de barras
Representa a classificação das cavidades quanto à relevância (alta, média, baixa etc.)
Gráfico 6 – Tipologia das Cavidades Naturais
Tipo: Gráfico de barras
Mostra os tipos de cavidades encontrados (por exemplo: cársticas, pseudocársticas etc.)
💧 Hidrogeologia
Gráfico 11 – Vazão Estática dos Poços
Tipo: Gráfico de barras
Indica a vazão estática de diferentes poços amostrados
Gráfico 12 – Nível Estático dos Poços
Tipo: Gráfico de barras
Representa os níveis estáticos medidos nos poços
🌊 Hidrologia
Gráfico 13 – Vazão Específica (L/s/km²)
Tipo: Gráfico de barras
Mostra a vazão específica para diferentes bacias hidrográficas
🔊 Ruído Ambiental
Gráfico 14 – Resultados da Campanha de Ruído (Diurno)
Tipo: Gráfico de barras
Apresenta os níveis de pressão sonora medidos durante o período diurno, por ponto
Gráfico 15 – Resultados da Campanha de Ruído (Noturno)
Tipo: Gráfico de barras
Mostra os níveis de ruído noturnos por ponto de medição
🌍 Sismicidade
Gráfico 16 – Eventos Sísmicos Registrados (Magnitude)
Tipo: Gráfico de barras
Mostra a quantidade de eventos por faixa de magnitude
Gráfico 17 – Eventos Sísmicos por Ano
Tipo: Gráfico de barras
Representa a frequência de eventos ao longo dos anos analisados
🧱 Solos
Gráfico 18 – Distribuição Granulométrica dos Solos
Tipo: Gráfico de colunas empilhadas
Apresenta a proporção de areia, silte e argila para diferentes amostras
 
 
  Meio sócio: 

    Com base no conteúdo do documento “TOMO V - Diagnóstico do Meio Socioeconômico 2022”, segue a listagem completa e precisa dos gráficos apresentados, organizada por subtemas e com informações sobre o tipo de gráfico e os dados que ele representa:
👥 1. População e Demografia
Gráfico 1 – População residente por município da AIDF
Tipo: Gráfico de colunas
Dados: População total residente nos municípios da Área de Influência Direta e Funcional (AIDF)
Gráfico 2 – População residente na zona rural e urbana da AIDF
Tipo: Gráfico de barras agrupadas
Dados: Comparação entre população urbana e rural por município
Gráfico 3 – Evolução da população (2000, 2010 e 2021)
Tipo: Gráfico de linhas
Dados: Crescimento populacional nos anos indicados
🏥 2. Saúde e Educação
Gráfico 4 – Indicadores de saúde nos municípios da AIDF
Tipo: Gráfico de colunas
Dados: Cobertura de atenção básica, taxa de mortalidade infantil e expectativa de vida
Gráfico 5 – Indicadores de educação nos municípios da AIDF
Tipo: Gráfico de colunas
Dados: Taxa de alfabetização, taxa de frequência escolar e média de anos de estudo
💰 3. Economia e Emprego
Gráfico 6 – PIB per capita dos municípios da AIDF
Tipo: Gráfico de colunas
Dados: Valor do Produto Interno Bruto per capita por município
Gráfico 7 – Distribuição setorial do PIB
Tipo: Gráfico de pizza
Dados: Proporção do PIB por setor (agropecuária, indústria, serviços e administração pública)
Gráfico 8 – Taxa de desocupação
Tipo: Gráfico de colunas
Dados: Porcentagem da população economicamente ativa sem ocupação
🏡 4. Uso e Ocupação do Solo
Gráfico 9 – Uso do solo na AIDF
Tipo: Gráfico de barras empilhadas
Dados: Percentual de áreas agrícolas, pastagens, vegetação natural e área urbana por município
🏙️ 5. Infraestrutura e Serviços Urbanos
Gráfico 10 – Acesso a serviços básicos (água, esgoto, coleta de lixo)
Tipo: Gráfico de barras agrupadas
Dados: Porcentagem de domicílios com acesso a cada serviço em cada município
Gráfico 11 – Tipologia dos domicílios
Tipo: Gráfico de pizza
Dados: Distribuição entre casas, apartamentos e outros tipos
🛤️ 6. Mobilidade e Transporte
Gráfico 12 – Tipos de vias de acesso aos municípios da AIDF
Tipo: Gráfico de colunas
Dados: Quantidade de vias pavimentadas, não pavimentadas, e ferrovias
🏛️ 7. Patrimônio Cultural e Comunidades Tradicionais
Gráfico 13 – Bens culturais inventariados por município
Tipo: Gráfico de colunas
Dados: Número de bens patrimoniais mapeados (igrejas, casas históricas, etc.)
Gráfico 14 – Comunidades tradicionais identificadas
Tipo: Gráfico de pizza
Dados: Proporção entre comunidades quilombolas, indígenas, extrativistas etc.
📜 8. Dinâmica Fundiária e Conflitos Sociais
Gráfico 15 – Conflitos fundiários registrados
Tipo: Gráfico de colunas
Dados: Número de ocorrências de conflitos por município
Gráfico 16 – Regularização fundiária por tipo
Tipo: Gráfico de barras agrupadas
Dados: Quantidade de títulos individuais, coletivos e de posse por município
Se desejar, posso montar uma planilha com os dados de cada gráfico ou sugerir visualizações complementares para relatórios e apresentações. Deseja avançar com isso?
 

  Meio Biótico: 


  Com base no documento “TOMO IV - Diagnóstico do Meio Biótico – Fauna 2022”, compilei abaixo todos os gráficos identificados nas seções de flora e fauna, com informações sobre tipo de gráfico e dados representados, conforme consta no próprio estudo.
🌿 FLORA
1. Fitofisionomias e Cobertura Vegetal
Gráfico 1 – Fitofisionomias encontradas na área de influência direta
Tipo: Pizza
Dados: Proporção de Cerrado Típico, Veredas, Mata Ciliar etc.
Gráfico 2 – Estado de conservação das fitofisionomias
Tipo: Barras agrupadas
Dados: Percentual de vegetação conservada, alterada, muito alterada por fitofisionomia.
2. Hábito Vegetativo
Gráfico 3 – Espécies por grupo de hábito
Tipo: Colunas
Dados: Quantidade de espécies herbáceas, arbóreas, arbustivas e lianas.
Gráfico 4 – Espécies por fitofisionomia
Tipo: Colunas empilhadas
Dados: Quantidade de espécies que ocorrem em mais de uma fitofisionomia.
3. Espécies Ameaçadas ou Endêmicas
Gráfico 5 – Espécies ameaçadas por categoria
Tipo: Pizza
Dados: Distribuição entre CR (Criticamente em Perigo), EN (Em Perigo), VU (Vulnerável).
4. Fitossociologia
Gráfico 6 – Índice de Valor de Importância (IVI)
Tipo: Colunas
Dados: IVI das principais espécies (frequência, densidade, dominância).
5. Fragmentação
Gráfico 7 – Tamanho dos fragmentos de vegetação
Tipo: Barras
Dados: Quantidade de fragmentos por classe de área (<10 ha, 10–50 ha etc.).
Gráfico 8 – Conectividade dos fragmentos
Tipo: Radar ou colunas
Dados: Grau de conexão ecológica entre áreas vegetadas.
🐾 FAUNA
1. Riqueza e Abundância de Espécies
Gráfico 9 – Riqueza de espécies por grupo faunístico
Tipo: Colunas
Dados: Número de espécies de mastofauna, avifauna, herpetofauna, entomofauna.
Gráfico 10 – Abundância relativa por grupo
Tipo: Colunas
Dados: Total de indivíduos registrados por grupo (em capturas ou observações).
2. Espécies Ameaçadas
Gráfico 11 – Espécies ameaçadas por grupo faunístico
Tipo: Colunas
Dados: Quantidade de espécies ameaçadas por categoria (VU, EN, CR) em cada grupo.
3. Mastofauna
Gráfico 12 – Mastofauna por método de registro
Tipo: Colunas
Dados: Nº de espécies registradas por armadilhamento fotográfico, visual e vestígios.
4. Avifauna
Gráfico 13 – Frequência relativa das aves
Tipo: Colunas
Dados: Frequência de ocorrência das principais espécies (comuns, incomuns, raras).
5. Herpetofauna
Gráfico 14 – Espécies de répteis e anfíbios por ambiente
Tipo: Colunas empilhadas
Dados: Quantidade de espécies por tipo de ambiente (cerrado, vereda, mata ciliar).
6. Entomofauna
Gráfico 15 – Riqueza de espécies de borboletas
Tipo: Pizza ou colunas
Dados: Distribuição de espécies registradas por família (Nymphalidae, Pieridae etc.)
Se desejar, posso organizar esses gráficos em uma planilha com base nos dados do relatório, gerar templates prontos em Excel ou adaptá-los para apresentações técnicas. Deseja seguir com isso?
 