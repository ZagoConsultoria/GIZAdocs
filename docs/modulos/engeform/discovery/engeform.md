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
