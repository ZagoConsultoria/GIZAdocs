# Priorização de Requisitos - Módulo 230

## Introdução

Este documento apresenta a priorização dos requisitos funcionais e não funcionais do módulo **230**, organizados por níveis de prioridade com base na criticidade para o funcionamento do sistema e valor de negócio. A priorização considera a coleta de dados em campo como funcionalidade core mais crítica, seguida por integração, armazenamento, relatórios e requisitos de qualidade.

## Objetivo

Definir a ordem de implementação dos requisitos do sistema 230, garantindo entregas incrementais de valor e substituindo processos manuais atuais.

---

## Priorização dos Requisitos {#tabela-priorizacao}

### Prioridade 1 - Crítica (MVP)

| **ID**        | **Descrição**                                                              | **Tipo**      | **Categoria**   |
| ------------- | -------------------------------------------------------------------------- | ------------- | --------------- |
| **RF01-230**  | Permitir coleta de dados de fauna atropelada via ZS com GPS e fotos        | Funcional     | Coleta de Dados |
| **RF02-230**  | Integrar upload automático de fotos georreferenciadas ao GIZA e SharePoint | Funcional     | Integração      |
| **RF03-230**  | Armazenar automaticamente dados de fauna em banco de dados parametrizado   | Funcional     | Armazenamento   |
| **RF04-230**  | Permitir funcionamento offline com sincronização automática                | Funcional     | Infraestrutura  |
| **RF05-230**  | Registrar e categorizar espécimes por tipo de evento com observações       | Funcional     | Coleta de Dados |
| **RNF01-230** | Sistema deve suportar operação offline por até 7 dias consecutivos         | Não Funcional | Confiabilidade  |
| **RNF02-230** | Sincronização automática dos dados deve ocorrer em até 10 minutos          | Não Funcional | Performance     |
| **RNF03-230** | Interface deve ser otimizada para uso em aparelhos Android                 | Não Funcional | Usabilidade     |
| **RNF04-230** | Comunicação com APIs e backend deve usar HTTPS e criptografia              | Não Funcional | Segurança       |
| **RNF05-230** | Tempo de resposta para consultas e geração de relatórios deve ser < 3s     | Não Funcional | Performance     |

### Prioridade 2 - Alta

| **ID**        | **Descrição**                                                                  | **Tipo**      | **Categoria**   |
| ------------- | ------------------------------------------------------------------------------ | ------------- | --------------- |
| **RF06-230**  | Separar nome científico e nome popular em campos distintos                     | Funcional     | Estrutura Dados |
| **RF07-230**  | Padronizar coordenadas automaticamente no formato UTM                          | Funcional     | Georreferência  |
| **RF08-230**  | Implementar filtros funcionais por supervisor, data e segmento                 | Funcional     | Consulta        |
| **RF09-230**  | Permitir edição posterior dos registros para correção de espécies              | Funcional     | Edição          |
| **RF11-230**  | Exportar dados estruturados (Excel/CSV) com colunas pré-formatadas             | Funcional     | Exportação      |
| **RNF06-230** | Aplicação deve ser intuitiva, sem necessidade de treinamento adicional         | Não Funcional | Usabilidade     |
| **RNF07-230** | Sistema deve suportar até 500 fotos por registro sem degradação de performance | Não Funcional | Performance     |

### Prioridade 3 - Média

| **ID**       | **Descrição**                                                        | **Tipo**  | **Categoria** |
| ------------ | -------------------------------------------------------------------- | --------- | ------------- |
| **RF10-230** | Criar filtro "indeterminado" para facilitar revisão de registros     | Funcional | Consulta      |
| **RF12-230** | Gerar mapas interativos mostrando pontos de coleta georreferenciados | Funcional | Visualização  |
| **RF13-230** | Exportar mapas em formatos compatíveis (KML/KMZ, shapefile)          | Funcional | Exportação    |

### Prioridade 4 - Baixa (Futuro)

| **ID**       | **Descrição**                                                    | **Tipo**  | **Categoria** |
| ------------ | ---------------------------------------------------------------- | --------- | ------------- |
| **RF14-230** | Criar modelos de relatório automáticos a partir da base de dados | Funcional | Relatórios    |
