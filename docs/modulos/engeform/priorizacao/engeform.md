# Priorização de Requisitos - Módulo Engeform

## Introdução| **RF37-EG** | Exportação | **Prioridade** | **Funcionalidade Principal** | **Quantidade de Requisitos** | **% do Total** |

| -------------- | ----------------------------------------------- | ---------------------------- | -------------- |
| **Crítica** | Coleta de dados e funcionalidades essenciais | 18 | 36.0% |
| **Alta** | Sincronização, backup e distribuição básica | 11 | 22.0% |
| **Média** | Funcionalidades complementares e performance | 12 | 24.0% |
| **Baixa** | Dashboards e visualizações avançadas | 9 | 18.0% |
| **Total** | - | **50** | **100%** |s para Excel por meio ambiental | Funcional | Todos |
| **RF38-EG** | Sistema de busca avançada nos dados coletados | Funcional | Todos |
| **RF39-EG** | Sistema de favoritar fotos por registro e download em lote das favoritas | Funcional | Todos |
| **RF40-EG** | Exportação de coordenadas geográficas para planilha Excel | Funcional | Todos |Este documento apresenta a priorização dos requisitos funcionais e não funcionais do módulo **Engeform**, organizados por níveis de prioridade com base na criticidade para o funcionamento do sistema e valor de negócio. A priorização considera a coleta de dados como funcionalidade core mais crítica, seguida por armazenamento, distribuição básica e, por último, funcionalidades de visualização avançada.

## Objetivo

Definir a ordem de implementação dos requisitos do sistema Engeform, garantindo que as funcionalidades mais críticas sejam desenvolvidas primeiro, permitindo entregas incrementais de valor para os usuários.

---

## Priorização dos Requisitos

### Prioridade 1 - Crítica (MVP)

| **ID**       | **Descrição**                                                               | **Tipo**      | **Meio Ambiental** |
| ------------ | --------------------------------------------------------------------------- | ------------- | ------------------ |
| **RF01-EG**  | Interface de coleta via ZS para dados socioeconômicos                       | Funcional     | Socioeconômico     |
| **RF02-EG**  | Interface de coleta via ZS para cavidades (espeleologia)                    | Funcional     | Físico             |
| **RF03-EG**  | Interface de coleta via ZS para hidrologia (recursos hídricos superficiais) | Funcional     | Físico             |
| **RF05-EG**  | Interface de coleta via ZS para ruídos e efeitos estroboscópicos            | Funcional     | Físico             |
| **RF06-EG**  | Interface de coleta via ZS para solos (pedologia)                           | Funcional     | Físico             |
| **RF07-EG**  | Interface de coleta via ZS para solos (geomorfologia)                       | Funcional     | Físico             |
| **RF08-EG**  | Interface de coleta via ZS para fauna                                       | Funcional     | Biótico            |
| **RF09-EG**  | Interface de coleta via ZS para caracterização florística                   | Funcional     | Biótico            |
| **RF10-EG**  | Interface de coleta via ZS para inventário florestal                        | Funcional     | Biótico            |
| **RF11-EG**  | Sistema de funcionamento offline para todas as fichas de coleta             | Funcional     | Todos              |
| **RF12-EG**  | Captura automática de coordenadas GPS (UTM) em todos os formulários         | Funcional     | Todos              |
| **RF15-EG**  | Banco de dados parametrizado para múltiplos meios ambientais                | Funcional     | Todos              |
| **RF17-EG**  | Integração com ZS para recebimento automático dos dados                     | Funcional     | Todos              |
| **RF18-EG**  | Integração com GIZA para centralização dos dados                            | Funcional     | Todos              |
| **RF21-EG**  | Validação automática de dados obrigatórios nos formulários                  | Funcional     | Todos              |
| **RNF01-EG** | Sistema deve funcionar offline em dispositivos móveis sem conexão           | Não Funcional | -                  |
| **RNF03-EG** | Interface deve ser responsiva para tablets Android e iOS                    | Não Funcional | -                  |
| **RNF05-EG** | Dados devem ser criptografados durante armazenamento e transmissão          | Não Funcional | -                  |

### Prioridade 2 - Alta

| **ID**       | **Descrição**                                                                 | **Tipo**      | **Meio Ambiental** |
| ------------ | ----------------------------------------------------------------------------- | ------------- | ------------------ |
| **RF04-EG**  | Interface de coleta via ZS para coleta de água (padrão 304)                   | Funcional     | Físico             |
| **RF13-EG**  | Upload automático de fotos georreferenciadas com marca d'água da empresa      | Funcional     | Todos              |
| **RF14-EG**  | Sincronização automática dos dados quando conectado à internet                | Funcional     | Todos              |
| **RF16-EG**  | Sistema de versionamento para controle de alterações nos dados                | Funcional     | Todos              |
| **RF20-EG**  | Sistema de backup automático dos dados coletados                              | Funcional     | Todos              |
| **RF22-EG**  | Tabela filtrável e exportável para dados socioeconômicos                      | Funcional     | Socioeconômico     |
| **RF23-EG**  | Tabela filtrável e exportável para dados do meio físico                       | Funcional     | Físico             |
| **RF24-EG**  | Tabela filtrável e exportável para dados do meio biótico                      | Funcional     | Biótico            |
| **RF36-EG**  | Geração de relatórios automatizados por meio ambiental                        | Funcional     | Todos              |
| **RNF02-EG** | Sincronização de dados deve ocorrer em até 5 minutos após conectar à internet | Não Funcional | -                  |
| **RNF06-EG** | Sistema deve ter backup automático a cada 24 horas                            | Não Funcional | -                  |

### Prioridade 3 - Média

| **ID**       | **Descrição**                                                           | **Tipo**      | **Meio Ambiental** |
| ------------ | ----------------------------------------------------------------------- | ------------- | ------------------ |
| **RF19-EG**  | Integração com SharePoint para backup e compartilhamento                | Funcional     | Todos              |
| **RF33-EG**  | Sistema de visualização de fotos por registro                           | Funcional     | Todos              |
| **RF34-EG**  | Sistema de download de fotos por lote ou individual                     | Funcional     | Todos              |
| **RF37-EG**  | Exportação de dados para Excel por meio ambiental                       | Funcional     | Todos              |
| **RF38-EG**  | Sistema de busca avançada nos dados coletados                           | Funcional     | Todos              |
| **RNF04-EG** | Sistema deve suportar até 1000 registros simultâneos em campo           | Não Funcional | -                  |
| **RNF07-EG** | Interface deve seguir padrões de acessibilidade WCAG 2.1                | Não Funcional | -                  |
| **RNF08-EG** | Sistema deve funcionar com conectividade 3G ou superior                 | Não Funcional | -                  |
| **RNF09-EG** | Fotos devem ser comprimidas automaticamente para otimizar armazenamento | Não Funcional | -                  |
| **RNF10-EG** | Sistema deve ter tempo de resposta inferior a 3 segundos para consultas | Não Funcional | -                  |

### Prioridade 4 - Baixa (Dashboards e Visualizações Avançadas)

| **ID**      | **Descrição**                                                      | **Tipo**  | **Meio Ambiental** |
| ----------- | ------------------------------------------------------------------ | --------- | ------------------ |
| **RF25-EG** | Dashboard com gráficos de relevância e tipologia de cavidades      | Funcional | Físico             |
| **RF26-EG** | Dashboard com gráficos de vazão e níveis de poços (hidrogeologia)  | Funcional | Físico             |
| **RF27-EG** | Dashboard com gráficos de vazão específica (hidrologia)            | Funcional | Físico             |
| **RF28-EG** | Dashboard com gráficos de níveis de ruído (diurno e noturno)       | Funcional | Físico             |
| **RF29-EG** | Dashboard com gráficos de distribuição granulométrica dos solos    | Funcional | Físico             |
| **RF30-EG** | Dashboard com gráficos demográficos e socioeconômicos              | Funcional | Socioeconômico     |
| **RF31-EG** | Dashboard com gráficos de riqueza e abundância de espécies (fauna) | Funcional | Biótico            |
| **RF32-EG** | Dashboard com gráficos de fitofisionomias e conservação (flora)    | Funcional | Biótico            |
| **RF35-EG** | Sistema de edição controlada de registros via GIZA                 | Funcional | Todos              |

---

## Resumo por Prioridade

| **Prioridade** | **Funcionalidade Principal**                 | **Quantidade de Requisitos** | **% do Total** |
| -------------- | -------------------------------------------- | ---------------------------- | -------------- |
| **Crítica**    | Coleta de dados e funcionalidades essenciais | 18                           | 37.5%          |
| **Alta**       | Sincronização, backup e distribuição básica  | 11                           | 22.9%          |
| **Média**      | Funcionalidades complementares e performance | 10                           | 20.8%          |
| **Baixa**      | Dashboards e visualizações avançadas         | 9                            | 18.8%          |
| **Total**      | -                                            | **48**                       | **100%**       |

## Justificativa da Priorização

### Prioridade Crítica (MVP)

- **Coleta de dados**: Funcionalidade core do sistema, sem ela não há valor
- **Funcionamento offline**: Essencial para trabalho em campo
- **Armazenamento básico**: Necessário para persistir os dados coletados
- **Validação**: Garante qualidade dos dados desde o início

### Prioridade Alta

- **Sincronização e backup**: Garante segurança e integridade dos dados
- **Distribuição básica**: Permite acesso aos dados coletados
- **Relatórios**: Entrega valor imediato aos stakeholders

### Prioridade Média

- **Funcionalidades complementares**: Melhoram a experiência do usuário
- **Performance**: Otimiza o uso do sistema

### Prioridade Baixa

- **Dashboards e gráficos**: Agregam valor, mas não são essenciais para o funcionamento básico
- **Edição avançada**: Funcionalidade nice-to-have para ajustes pontuais
