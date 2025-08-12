# Priorização de Requisitos - Módulo Fauna

## Introdução

Este documento apresenta a priorização dos requisitos funcionais e não funcionais do módulo **Fauna**, organizados por níveis de prioridade com base na criticidade para o funcionamento do sistema e valor de negócio. A priorização considera a coleta de dados em campo como funcionalidade core mais crítica, seguida por integração, armazenamento, relatórios e requisitos de qualidade.

## Objetivo

Definir a ordem de implementação dos requisitos do sistema Fauna, garantindo entregas incrementais de valor e substituindo processos manuais atuais.

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
| **RF06-230**  | Gerar relatórios automáticos de fauna com fotos, tabelas e gráficos        | Funcional     | Relatórios      |
| **RNF01-230** | Sistema deve suportar operação offline por até 7 dias consecutivos         | Não Funcional | Confiabilidade  |
| **RNF02-230** | Sincronização automática dos dados deve ocorrer em até 10 minutos          | Não Funcional | Performance     |
| **RNF03-230** | Interface deve ser otimizada para uso em aparelhos Android                 | Não Funcional | Usabilidade     |
| **RNF04-230** | Comunicação com APIs e backend deve usar HTTPS e criptografia              | Não Funcional | Segurança       |
| **RNF05-230** | Tempo de resposta para consultas e geração de relatórios deve ser < 3s     | Não Funcional | Performance     |

### Prioridade 2 - Alta

| **ID**        | **Descrição**                                                                  | **Tipo**      | **Categoria** |
| ------------- | ------------------------------------------------------------------------------ | ------------- | ------------- |
| **RNF06-230** | Aplicação deve ser intuitiva, sem necessidade de treinamento adicional         | Não Funcional | Usabilidade   |
| **RNF07-230** | Sistema deve suportar até 500 fotos por registro sem degradação de performance | Não Funcional | Performance   |
