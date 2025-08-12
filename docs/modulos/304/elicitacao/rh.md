# Elicitação de Requisitos - Módulo Recursos Hídricos (304)

## Introdução

Este documento apresenta a elicitação de requisitos funcionais e não funcionais para o módulo **Recursos Hídricos (304)**, responsável pela automação da coleta de campo, armazenamento e geração de relatórios de parâmetros laboratoriais, a partir das dores e necessidades identificadas no discovery.

## Objetivo

Definir requisitos claros para desenvolver uma solução integrada que:

- Permita coleta digital de dados de campo no ZS, substituindo fichas manuais.
- Automatize a organização de fotos e importação de resultados de laboratório.
- Gere tabelas e relatórios automáticos comparativos com campanhas anteriores.

---

## Requisitos Funcionais {#requisitos-funcionais}

| **ID**   | **Descrição**                                                                                          | **Fonte** |
| -------- | ------------------------------------------------------------------------------------------------------ | --------- |
| RF01-304 | Permitir coleta de dados de campo via ZS, substituindo ficha manual em papel.                          | Discovery |
| RF02-304 | Organizar automaticamente fotos em pastas por ponto de coleta ao importar imagens do ZS.               | Discovery |
| RF03-304 | Importar resultados de laboratório (PDF) e extrair parâmetros automaticamente para tabelas no sistema. | Discovery |
| RF04-304 | Gerar tabelas comparativas de parâmetros por campanha e com a campanha de background.                  | Discovery |
| RF05-304 | Gerar relatórios automáticos no GISA com gráficos, tabelas e indicadores, prontos para exportação.     | Discovery |
| RF06-304 | Exportar relatórios consolidados em formatos PDF e Excel com formatação adequada.                      | Discovery |

---

## Requisitos Não Funcionais {#requisitos-nao-funcionais}

| **ID**    | **Descrição**                                                                                       | **Fonte** |
| --------- | --------------------------------------------------------------------------------------------------- | --------- |
| RNF01-304 | Sistema deve funcionar offline por até 7 dias, com sincronização automática ao reconectar.          | Discovery |
| RNF02-304 | Sincronização de dados deve ocorrer em até 10 minutos após reconexão.                               | Discovery |
| RNF03-304 | Tempo de resposta para consultas e geração de tabelas de parâmetros deve ser inferior a 3 segundos. | Discovery |
| RNF04-304 | Comunicação com APIs e backend deve usar HTTPS e criptografia para segurança dos dados.             | Discovery |
| RNF05-304 | Interface deve ser intuitiva, com usabilidade adequada a usuários de campo com conhecimento básico. | Discovery |

---

_Fonte: Entrevistas exploratórias, observação de campo e mapeamento de dores realizado no discovery._
