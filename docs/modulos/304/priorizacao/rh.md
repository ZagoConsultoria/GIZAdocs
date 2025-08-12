# Priorização de Requisitos - Módulo Recursos Hídricos (304)

## Introdução

Este documento apresenta a priorização dos requisitos funcionais e não funcionais do módulo **Recursos Hídricos (304)**, organizados por níveis de prioridade com base na criticidade e valor de negócio. A priorização considera a coleta digital e processamento automatizado como funcionalidades core.

## Objetivo

Definir a ordem de implementação dos requisitos do sistema, garantindo entregas incrementais de valor que substituam os processos manuais existentes.

---

## Priorização dos Requisitos {#tabela-priorizacao}

### Prioridade 1 - Crítica (MVP)

| **ID**        | **Descrição**                                                                                          | **Tipo**      | **Categoria**            |
| ------------- | ------------------------------------------------------------------------------------------------------ | ------------- | ------------------------ |
| **RF01-304**  | Permitir coleta de dados de campo via ZS, substituindo ficha manual em papel.                          | Funcional     | Coleta de Dados          |
| **RF02-304**  | Organizar automaticamente fotos em pastas por ponto de coleta ao importar imagens do ZS.               | Funcional     | Armazenamento de Imagens |
| **RF03-304**  | Importar resultados de laboratório (PDF) e extrair parâmetros automaticamente para tabelas no sistema. | Funcional     | Importação de Dados      |
| **RF04-304**  | Gerar tabelas comparativas de parâmetros por campanha e com a campanha de background.                  | Funcional     | Processamento de Dados   |
| **RNF01-304** | Sistema deve funcionar offline por até 7 dias, com sincronização automática ao reconectar.             | Não Funcional | Disponibilidade          |
| **RNF04-304** | Comunicação com APIs e backend deve usar HTTPS e criptografia para garantir segurança dos dados.       | Não Funcional | Segurança                |

### Prioridade 2 - Alta

| **ID**        | **Descrição**                                                                                       | **Tipo**      | **Categoria**       |
| ------------- | --------------------------------------------------------------------------------------------------- | ------------- | ------------------- |
| **RF05-304**  | Gerar relatórios automáticos no GISA com gráficos, tabelas e indicadores, prontos para exportação.  | Funcional     | Relatórios          |
| **RF06-304**  | Exportar relatórios consolidados em formatos PDF e Excel com formatação adequada.                   | Funcional     | Exportação de Dados |
| **RNF02-304** | Sincronização de dados deve ocorrer em até 10 minutos após reconexão.                               | Não Funcional | Performance         |
| **RNF03-304** | Tempo de resposta para consultas e geração de tabelas de parâmetros deve ser inferior a 3 segundos. | Não Funcional | Performance         |
| **RNF05-304** | Interface deve ser intuitiva, com usabilidade adequada a usuários de campo com conhecimento básico. | Não Funcional | Usabilidade         |

### Prioridade 3 - Média

| **ID** | **Descrição** | **Tipo** | **Categoria** |
| ------ | ------------- | -------- | ------------- |
| -      | -             | -        | -             |

**Fonte:** Entrevistas exploratórias, observação de campo e análise de processos identificados no discovery.
