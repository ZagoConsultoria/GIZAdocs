# Elicitação de Requisitos - Módulo Engeform

## Introdução

Este documento apresenta a elicitação de requisitos funcionais para o módulo **Engeform**, dedicado à automatização da coleta e gestão de dados para estudos de impacto ambiental (EIA). Os requisitos foram identificados com base no discovery realizado junto aos stakeholders e na análise das necessidades dos diferentes meios ambientais: físico, socioeconômico e biótico.

## Objetivo

Definir os requisitos funcionais e não funcionais necessários para implementar um sistema integrado que permita:

- Coleta eficiente de dados primários em campo através de formulários digitais
- Armazenamento centralizado e seguro dos dados coletados
- Processamento e análise dos dados conforme necessidades específicas de cada meio
- Distribuição dos dados através de interfaces de visualização, relatórios e dashboards

---

## Requisitos Funcionais

| **ID**      | **Descrição**                                                               | **Meio Ambiental** |
| ----------- | --------------------------------------------------------------------------- | ------------------ |
| **RF01-EG** | Interface de coleta via ZS para dados socioeconômicos                       | Socioeconômico     |
| **RF02-EG** | Interface de coleta via ZS para cavidades (espeleologia)                    | Físico             |
| **RF03-EG** | Interface de coleta via ZS para hidrologia (recursos hídricos superficiais) | Físico             |
| **RF04-EG** | Interface de coleta via ZS para coleta de água (padrão 304)                 | Físico             |
| **RF05-EG** | Interface de coleta via ZS para ruídos e efeitos estroboscópicos            | Físico             |
| **RF06-EG** | Interface de coleta via ZS para solos (pedologia)                           | Físico             |
| **RF07-EG** | Interface de coleta via ZS para solos (geomorfologia)                       | Físico             |
| **RF08-EG** | Interface de coleta via ZS para fauna                                       | Biótico            |
| **RF09-EG** | Interface de coleta via ZS para caracterização florística                   | Biótico            |
| **RF10-EG** | Interface de coleta via ZS para inventário florestal                        | Biótico            |
| **RF11-EG** | Sistema de funcionamento offline para todas as fichas de coleta             | Todos              |
| **RF12-EG** | Captura automática de coordenadas GPS (UTM) em todos os formulários         | Todos              |
| **RF13-EG** | Upload automático de fotos georreferenciadas com marca d'água da empresa    | Todos              |
| **RF14-EG** | Sincronização automática dos dados quando conectado à internet              | Todos              |
| **RF15-EG** | Banco de dados parametrizado para múltiplos meios ambientais                | Todos              |
| **RF16-EG** | Sistema de versionamento para controle de alterações nos dados              | Todos              |
| **RF17-EG** | Integração com ZS para recebimento automático dos dados                     | Todos              |
| **RF18-EG** | Integração com GIZA para centralização dos dados                            | Todos              |
| **RF19-EG** | Integração com SharePoint para backup e compartilhamento                    | Todos              |
| **RF20-EG** | Sistema de backup automático dos dados coletados                            | Todos              |
| **RF21-EG** | Validação automática de dados obrigatórios nos formulários                  | Todos              |
| **RF22-EG** | Tabela filtrável e exportável para dados socioeconômicos                    | Socioeconômico     |
| **RF23-EG** | Tabela filtrável e exportável para dados do meio físico                     | Físico             |
| **RF24-EG** | Tabela filtrável e exportável para dados do meio biótico                    | Biótico            |
| **RF25-EG** | Dashboard com gráficos de relevância e tipologia de cavidades               | Físico             |
| **RF26-EG** | Dashboard com gráficos de vazão e níveis de poços (hidrogeologia)           | Físico             |
| **RF27-EG** | Dashboard com gráficos de vazão específica (hidrologia)                     | Físico             |
| **RF28-EG** | Dashboard com gráficos de níveis de ruído (diurno e noturno)                | Físico             |
| **RF29-EG** | Dashboard com gráficos de distribuição granulométrica dos solos             | Físico             |
| **RF30-EG** | Dashboard com gráficos demográficos e socioeconômicos                       | Socioeconômico     |
| **RF31-EG** | Dashboard com gráficos de riqueza e abundância de espécies (fauna)          | Biótico            |
| **RF32-EG** | Dashboard com gráficos de fitofisionomias e conservação (flora)             | Biótico            |
| **RF33-EG** | Sistema de visualização de fotos por registro                               | Todos              |
| **RF34-EG** | Sistema de download de fotos por lote ou individual                         | Todos              |
| **RF35-EG** | Sistema de edição controlada de registros via GIZA                          | Todos              |
| **RF36-EG** | Geração de relatórios automatizados por meio ambiental                      | Todos              |
| **RF37-EG** | Exportação de dados para Excel por meio ambiental                           | Todos              |
| **RF38-EG** | Sistema de busca avançada nos dados coletados                               | Todos              |
| **RF39-EG** | Sistema de favoritar fotos por registro e download em lote das favoritas    | Todos              |
| **RF40-EG** | Exportação de coordenadas geográficas para planilha Excel                   | Todos              |

## Requisitos Não Funcionais

| **ID**       | **Descrição**                                                                 | **Categoria**   |
| ------------ | ----------------------------------------------------------------------------- | --------------- |
| **RNF01-EG** | Sistema deve funcionar offline em dispositivos móveis sem conexão             | Disponibilidade |
| **RNF02-EG** | Sincronização de dados deve ocorrer em até 5 minutos após conectar à internet | Performance     |
| **RNF03-EG** | Interface deve ser responsiva para tablets Android e iOS                      | Usabilidade     |
| **RNF04-EG** | Sistema deve suportar até 1000 registros simultâneos em campo                 | Performance     |
| **RNF05-EG** | Dados devem ser criptografados durante armazenamento e transmissão            | Segurança       |
| **RNF06-EG** | Sistema deve ter backup automático a cada 24 horas                            | Confiabilidade  |
| **RNF07-EG** | Interface deve seguir padrões de acessibilidade WCAG 2.1                      | Usabilidade     |
| **RNF08-EG** | Sistema deve funcionar com conectividade 3G ou superior                       | Compatibilidade |
| **RNF09-EG** | Fotos devem ser comprimidas automaticamente para otimizar armazenamento       | Performance     |
| **RNF10-EG** | Sistema deve ter tempo de resposta inferior a 3 segundos para consultas       | Performance     |

---

## Resumo Quantitativo

| **Tipo de Requisito**     | **Quantidade** |
| ------------------------- | -------------- |
| Requisitos Funcionais     | 40             |
| Requisitos Não Funcionais | 10             |
| **Total**                 | **50**         |
