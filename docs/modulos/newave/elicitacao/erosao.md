# Elicitação de Requisitos - Programa Erosão

## Introdução

Este documento apresenta a elicitação de requisitos para o programa de **Monitoramento de Erosão** do módulo Newave. O monitoramento de erosão é fundamental para avaliar os impactos ambientais relacionados à perda de solo, degradação de taludes e alterações na topografia das áreas de influência do projeto.

## Contexto

O programa de erosão visa:

- **Monitorar processos erosivos** em tempo real
- **Identificar áreas críticas** com risco de erosão
- **Avaliar eficácia de medidas mitigadoras** implementadas
- **Gerar relatórios técnicos** para órgãos ambientais
- **Integrar com outros programas ambientais** do projeto

## Metodologia de Elicitação

- **Entrevistas** com especialistas em geologia e meio ambiente
- **Análise de documentos** técnicos e regulamentações ambientais
- **Workshops** com equipe de campo e analistas
- **Benchmarking** com outros projetos similares

---

## Requisitos Funcionais

| **ID**  | **Descrição**                                                                 |
| ------- | ----------------------------------------------------------------------------- |
| RF25-NW | Permitir a coleta de dados de erosão via ZS com formulário parametrizado      |
| RF26-NW | Registrar medições de perda de solo por ponto com coordenadas GPS automáticas |
| RF27-NW | Anexar automaticamente evidências fotográficas e topográficas ao GIZA         |
| RF28-NW | Permitir funcionamento offline durante coletas em campo                       |
| RF29-NW | Armazenar dados em banco com versionamento para análise temporal              |
| RF30-NW | Integrar com ZS, GIZA e sistemas de monitoramento topográfico                 |
| RF31-NW | Exibir mapa de calor no GIZA com níveis de erosão por área                    |
| RF32-NW | Permitir download de dados e imagens por lote ou registro individual          |
| RF33-NW | Exibir dados em formato de tabela filtrável e exportável                      |
| RF34-NW | Gerar relatórios automatizados conforme padrões ambientais                    |
| RF35-NW | Permitir análise de tendência temporal da erosão por área                     |
| RF36-NW | Registrar eficácia de medidas mitigadoras implementadas                       |

---

## Requisitos Não Funcionais

| **ID**   | **Descrição**                                                                   |
| -------- | ------------------------------------------------------------------------------- |
| RNF12-NW | Interface intuitiva para usuários com nível 5/10 de conhecimento em informática |
| RNF13-NW | Evitar perda de dados durante coletas longas em campo                           |
| RNF14-NW | Garantir desempenho estável inclusive em áreas remotas offline                  |
| RNF15-NW | Instalação possível em tablets ruggerizados e acesso via navegador              |
| RNF16-NW | Garantir segurança e sigilo dos dados geotécnicos                               |
| RNF17-NW | Suportar armazenamento de imagens em alta resolução para análise técnica        |

---

## Rastreabilidade

| **Origem**           | **Stakeholder**            | **Justificativa**                            |
| -------------------- | -------------------------- | -------------------------------------------- |
| Regulamentação IBAMA | Equipe Ambiental           | Conformidade com licenciamento ambiental     |
| Análise de Campo     | Geólogos e Engenheiros     | Necessidades práticas de monitoramento       |
| Integração Sistêmica | Equipe de TI               | Compatibilidade com infraestrutura existente |
| Relatórios Técnicos  | Consultores Especializados | Qualidade e padronização dos deliverables    |

---

## Dependências Técnicas

- **ZS (Zago Survey)**: Plataforma de coleta de dados em campo
- **GIZA**: Sistema de visualização e análise de dados
- **TimeStamp**: Sistema de controle temporal e auditoria
- **GPS de Precisão**: Para georeferenciamento preciso dos pontos

---

## Considerações de Implementação

### Priorizações Sugeridas

1. **Alta Prioridade**: RF25-NW, RF26-NW, RF28-NW, RF29-NW (funcionalidades básicas de coleta)
2. **Média Prioridade**: RF27-NW, RF30-NW, RF31-NW, RF33-NW (visualização e integração)
3. **Baixa Prioridade**: RF35-NW, RF36-NW (análises avançadas)

### Riscos Identificados

- **Conectividade em campo**: Áreas remotas podem ter limitações de rede
- **Precisão GPS**: Necessário GPS de alta precisão para medições confiáveis
- **Volume de dados**: Imagens em alta resolução podem impactar performance

---

## Próximos Passos

1. **Validação** dos requisitos com stakeholders
2. **Priorização** detalhada dos requisitos
3. **Modelagem** das histórias de usuário
4. **Definição de critérios** de aceitação
