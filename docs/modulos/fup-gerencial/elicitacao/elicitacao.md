# Elicitação de Requisitos - FUP Gerencial

## Introdução

Este documento apresenta a elicitação de requisitos para o **FUP Gerencial** (Follow-up), sistema destinado ao acompanhamento e avaliação da qualidade de projetos. O objetivo é criar uma ferramenta padronizada que guie usuários através de um fluxo de preenchimento assistido, gerando relatórios detalhados e dashboards gerenciais com indicadores visuais.

## Contexto

O FUP Gerencial visa:

- **Padronizar avaliações** de projetos em diferentes dimensões
- **Centralizar informações** de acompanhamento em sistema único
- **Melhorar visibilidade** através de dashboards com farol de cores
- **Gerar insights** por meio de relatórios detalhados
- **Facilitar tomada de decisão** com dados consolidados e filtráveis

## Metodologia de Elicitação

- **Análise do discovery** existente
- **Identificação de personas** e jornadas de usuário
- **Mapeamento de funcionalidades** principais
- **Definição de fluxos** de trabalho críticos

---

## Requisitos Funcionais

| **ID**   | **Descrição**                                                              |
| -------- | -------------------------------------------------------------------------- |
| RF01-FUP | Permitir criação de novo preenchimento FUP associado a projeto, PO e data  |
| RF02-FUP | Guiar usuário através de fluxo assistido com blocos temáticos              |
| RF03-FUP | Implementar bloco financeiro para custos, orçamento e viabilidade          |
| RF04-FUP | Implementar bloco de gestão de entregas para cronograma e desvios          |
| RF05-FUP | Implementar bloco de gestão da qualidade para processos e conformidade     |
| RF06-FUP | Implementar bloco de nível de qualidade para aferição das entregas         |
| RF07-FUP | Implementar bloco de nível tecnológico para arquitetura e débitos técnicos |
| RF08-FUP | Realizar salvamento automático do progresso durante preenchimento          |
| RF09-FUP | Aplicar lógica condicional baseada em respostas anteriores                 |
| RF10-FUP | Gerar relatório automático em PDF com todas as respostas do fluxo          |
| RF11-FUP | Organizar relatório por blocos temáticos com layout claro                  |
| RF12-FUP | Manter histórico de relatórios gerados por projeto                         |
| RF13-FUP | Exibir dashboard com indicadores de farol (verde, amarelo, vermelho)       |
| RF14-FUP | Calcular cor do farol automaticamente baseado nas respostas                |
| RF15-FUP | Filtrar dashboard por PO (todos os projetos de uma pessoa)                 |
| RF16-FUP | Filtrar dashboard por projeto específico                                   |
| RF17-FUP | Filtrar dashboard por período/data de avaliação                            |
| RF18-FUP | Permitir drill-down em faróis para ver detalhes da avaliação               |
| RF19-FUP | Associar cada preenchimento a projeto, PO e data específicos               |
| RF20-FUP | Permitir visualização da evolução de projetos ao longo do tempo            |

---

## Requisitos Não Funcionais

| **ID**    | **Descrição**                                                        |
| --------- | -------------------------------------------------------------------- |
| RNF01-FUP | Interface intuitiva para reduzir resistência à adoção pelos usuários |
| RNF02-FUP | Tempo de preenchimento do fluxo completo inferior a 15 minutos       |
| RNF03-FUP | Dashboard deve carregar em menos de 3 segundos                       |
| RNF04-FUP | Relatórios PDF devem ser gerados em menos de 10 segundos             |
| RNF05-FUP | Sistema deve suportar 100+ usuários simultâneos                      |
| RNF06-FUP | Disponibilidade de 99% durante horário comercial                     |
| RNF07-FUP | Backup automático diário dos dados de preenchimento                  |
| RNF08-FUP | Flexibilidade para modificação do fluxo sem desenvolvimento complexo |
| RNF09-FUP | Auditoria de todas as alterações nos preenchimentos                  |
| RNF10-FUP | Acesso baseado em perfil de usuário (PO, Gerente, Liderança)         |

---

## Rastreabilidade

| **Origem**                   | **Stakeholder**         | **Justificativa**                            |
| ---------------------------- | ----------------------- | -------------------------------------------- |
| Falta de padronização        | Gerente de Portfólio    | Necessidade de critérios uniformes           |
| Informações descentralizadas | Product Owners          | Centralização para eficiência                |
| Tomada de decisão lenta      | Liderança/Stakeholders  | Visibilidade rápida através de dashboards    |
| Análise manual demorada      | Gerentes de Projeto     | Automação de relatórios e indicadores        |
| Falta de histórico           | Coordenador de Projetos | Acompanhamento da evolução ao longo do tempo |

---

## Dependências Técnicas

- **Sistema de autenticação** para controle de acesso por perfil
- **Gerador de PDF** para criação automática de relatórios
- **Framework de dashboard** para visualizações interativas
- **Banco de dados** para armazenamento de respostas e histórico
- **Sistema de backup** para garantia de integridade dos dados

---

## Considerações de Implementação

### Priorizações Sugeridas

1. **Alta Prioridade**: RF01-FUP, RF02-FUP, RF03-FUP, RF04-FUP, RF05-FUP, RF13-FUP, RF14-FUP (fluxo básico e dashboard)
2. **Média Prioridade**: RF06-FUP, RF07-FUP, RF10-FUP, RF15-FUP, RF16-FUP, RF17-FUP (funcionalidades complementares)
3. **Baixa Prioridade**: RF09-FUP, RF18-FUP, RF20-FUP (funcionalidades avançadas)

### Riscos Identificados

- **Subjetividade nas respostas**: Necessário definir critérios claros para classificação dos faróis
- **Resistência dos usuários**: Interface deve ser simples e valor gerado deve ser evidente
- **Evolução do fluxo**: Sistema deve ser flexível para mudanças futuras
- **Consistência entre avaliadores**: Treinamento necessário para padronização

---

## Próximos Passos

1. **Validação** dos requisitos com stakeholders
2. **Priorização** detalhada dos requisitos
3. **Modelagem** das histórias de usuário
4. **Definição de critérios** de aceitação
