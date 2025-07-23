# Monitoramento de Emissões Atmosféricas

## Introdução

Esta documentação tem como objetivo registrar e organizar os requisitos levantados durante as reuniões de elicitação para o módulo de **Monitoramento de Emissões Atmosféricas** do aplicativo em desenvolvimento. A funcionalidade será utilizada para registrar medições de fumaça preta, gases atmosféricos e particulados em campo, com integração posterior à plataforma GIZA.

## Objetivo

Construir um sistema capaz de:

- Coletar dados de campo relacionados a emissões atmosféricas (fumaça preta, gases e particulados);
- Visualizar as medições de maneira clara e filtrável;
- Permitir exportações (dados e fotos) para elaboração de relatórios;
- Operar offline e em dispositivos móveis.

## Metodologia

A elicitação de requisitos foi realizada com base em:

- Reuniões com stakeholders do projeto;
- Análise dos fluxos de trabalho atuais;
- Observação de processos similares (como o monitoramento de processos erosivos);
- Identificação de lacunas no processo atual de coleta e organização de dados ambientais.

### Requisitos Funcionais

| **ID**  | **Requisito Funcional**                                                                |
| ------- | -------------------------------------------------------------------------------------- |
| RF01-NW | Permitir a coleta de dados de fumaça preta via ZS.                                     |
| RF02-NW | Ficha de coleta deve incluir CO₂, CO e SO₂, com dados organizados por ponto de coleta. |
| RF03-NW | Anexar automaticamente as evidências fotográficas ao GIZA e SharePoint.                |
| RF04-NW | Permitir funcionamento offline durante a coleta.                                       |
| RF05-NW | Armazenar os dados em banco de dados seguro.                                           |
| RF06-NW | Integrar com ZS, GIZA e TimeStamp.                                                     |
| RF07-NW | Exibir tabela no GIZA com filtro e farol de cor (ex: fumaça preta > 40% em vermelho).  |
| RF08-NW | Permitir download de fotos por lote ou por registro individual.                        |
| RF09-NW | Exibir dados em formato de tabela filtrável e exportável.                              |
| RF10-NW | Gerar esqueleto de relatório Word com tabelas prontas para completar com dados extras. |
| RF11-NW | Gerar relatórios conforme padrão regulatório ambiental.                                |
| RF12-NW | Permitir inserção manual de dados complementares (particulados, gráficos, fotos).      |

### Requisitos Não Funcionais

| **ID**   | **Requisito Não Funcional**                                                                |
| -------- | ------------------------------------------------------------------------------------------ |
| RNF01-NW | Interface intuitiva e adequada para usuário com nível 5/10 de conhecimento em informática. |
| RNF02-NW | Evitar perda de dados e falhas de funcionamento.                                           |
| RNF03-NW | Garantir desempenho estável, inclusive no modo offline.                                    |
| RNF04-NW | Instalação possível no celular e acesso também via navegador.                              |
| RNF05-NW | Garantir segurança e sigilo dos dados.                                                     |

## Observações

- A visualização da fumaça preta pode seguir o modelo dos processos erosivos (Newave), com destaque para valores críticos.
- Link para documento de referência:  
  [Documento de requisitos](https://grupozago.sharepoint.com/:w:/s/PROJ_NEWAVE_2025/EQBooffqVDJDpczRdoUe6dQB7f_Q4qaj4M19OEpvKvnBeg?e=RyYb59)

## Próximos Passos

1. **Criação de protótipos das telas** com base nos formulários e visualizações descritas;
2. **Validação dos requisitos** com usuários finais;
3. **Definição da arquitetura de dados** e fluxos offline;
4. **Implementação do módulo de coleta em campo**;
5. **Testes de exportação e integração com GIZA**;
6. **Planejamento do fluxo de download de fotos em lote com filtros aplicáveis**.
