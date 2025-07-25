# Discovery - Programa Plantio AXS

## Informações da Sessão

**Data:** 16/06/2025  
**Módulo:** AXS  
**Programa:** Plantio  
**Participantes:** Equipe AXS, Usuários de Campo, Analistas  
**Duração:** 2h30min

## Contexto e Objetivos

O programa de Plantio da AXS visa automatizar e otimizar o processo de coleta, armazenamento e análise de dados de caracterização de plantio. Atualmente, o processo é realizado de forma manual, gerando dores relacionadas à padronização, organização e análise dos dados coletados em campo.

## Processo Atual Identificado

### Etapas do Processo

| **Etapa**         | **Atividade Atual**                              | **Dores Identificadas**                                      | **Ferramentas Utilizadas**                 |
| ----------------- | ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ |
| **Coleta**        | Preenchimento manual de fichas de caracterização | Falta de padrão definido, dados inconsistentes               | Planilhas Excel, Formulários em papel      |
| **Armazenamento** | Organização manual no SharePoint                 | Dificuldade em localizar documentos, risco de perda de dados | SharePoint, pastas locais                  |
| **Tratamento**    | Revisão manual de erros ortográficos             | Tempo excessivo em atividades operacionais                   | Excel, Word, verificação manual            |
| **Distribuição**  | Criação manual de relatórios                     | Processo demorado, seleção manual de evidências              | Excel, PowerPoint, seleção manual de fotos |

## Dores e Necessidades Identificadas

### Principais Problemas

1. **Padronização**: Ausência de formulário padrão para coleta de dados de plantio
2. **Organização**: Dificuldade em encontrar e organizar documentos no SharePoint
3. **Eficiência**: Muito tempo gasto em atividades manuais e operacionais
4. **Qualidade**: Erros ortográficos e inconsistências nos dados
5. **Segurança**: Risco de perda de dados e evidências fotográficas

### Expectativas dos Usuários

- **Formulário padronizado** para coleta consistente de dados
- **Armazenamento centralizado** e seguro dos dados
- **Correção automática** de textos e dados
- **Geração automática** de relatórios conforme padrão AXS
- **Interface intuitiva** que não exija treinamento adicional

## Soluções Propostas

### Visão Geral da Solução

| **Componente**    | **Solução Proposta**                     | **Benefícios Esperados**                 | **Riscos Identificados**                              |
| ----------------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------------------- |
| **Coleta**        | Formulário no ZS com campos padronizados | Coleta consistente em poucos cliques     | Necessidade de conectividade, formulário não editável |
| **Armazenamento** | Banco de dados parametrizado integrado   | Dados seguros e facilmente consultáveis  | Usuários não poderão editar dados diretamente         |
| **Tratamento**    | IA para correção automática de textos    | Redução significativa do trabalho manual | Custo adicional, possíveis erros da IA                |
| **Distribuição**  | Relatórios automáticos no GIZA           | Relatórios em um clique                  | Limitações de edição simultânea                       |

## Recursos e Funcionalidades Definidas

### Funcionalidades Principais

1. **Formulário de Coleta no ZS**

   - Campos padronizados para caracterização de plantio
   - Captura automática de coordenadas GPS
   - Anexo automático de evidências fotográficas

2. **Banco de Dados Parametrizado**

   - Armazenamento seguro e versionado
   - Estrutura otimizada para consultas
   - Integração com sistemas existentes (ZS, GIZA, SharePoint)

3. **Correção Automática por IA**

   - Processamento de textos coletados
   - Correção ortográfica e padronização
   - Manutenção de log de alterações

4. **Geração Automática de Relatórios**
   - Templates conforme padrão AXS
   - Seleção automática de evidências relevantes
   - Exportação em múltiplos formatos

## Tecnologias e Integrações

### Stack Tecnológico

- **ZS**: Aplicativo de coleta em campo
- **GIZA**: Plataforma de visualização e relatórios
- **SharePoint**: Armazenamento de documentos e evidências
- **API ChatGPT**: Correção automática de textos
- **Banco de Dados**: PostgreSQL com versionamento

### Integrações Necessárias

- ZS ↔ Banco de Dados (sincronização de dados)
- GIZA ↔ Banco de Dados (visualização e relatórios)
- SharePoint ↔ Sistema (armazenamento de evidências)
- API IA ↔ Sistema (correção de textos)

## Próximos Passos

1. **Elicitação Detalhada**: Definir requisitos funcionais e não funcionais específicos
2. **Priorização**: Estabelecer ordem de implementação baseada em valor e complexidade
3. **Modelagem**: Criar histórias de usuário detalhadas
4. **Prototipação**: Desenvolver mockups das interfaces principais
5. **Planejamento Técnico**: Definir arquitetura e estratégia de implementação

## Links e Recursos

- [Documentação SharePoint do Discovery](https://grupozago.sharepoint.com/:fl:/g/contentstorage/CSP_62f7c2dd-684e-451b-a8b5-f5313509eb7a/ERsyqwtIZpJLnvbpNUcAiTEBmuj5CZD7A7Hd0XUam41FSg?e=kJy6m4&nav=cz0lMkZjb250ZW50c3RvcmFnZSUyRkNTUF82MmY3YzJkZC02ODRlLTQ1MWItYThiNS1mNTMxMzUwOWViN2EmZD1iITNjTDNZazVvRzBXb3RmVXhOUW5yZXBTX2xFT0FIaEJGaFFicWFvTGtFR2cyczJDaGF2NXNRNmVwNXlpMkxKdFomZj0wMUtIUldDTVkzR0tWUVdTREdTSkZaNTVYSkdWRFFCQ0pSJmM9JTJGJmZsdWlkPTEmYT1Mb29wQXBwJnA9JTQwZmx1aWR4JTJGbG9vcC1wYWdlLWNvbnRhaW5lciZ4PSU3QiUyMnclMjIlM0ElMjJUMFJUVUh4bmNuVndiM3BoWjI4dWMyaGhjbVZ3YjJsdWRDNWpiMjE4WWlFelkwd3pXV3MxYjBjd1YyOTBabFY0VGxGdWNtVndVMTlzUlU5QlNHaENSbWhSWW5GaGIweHJSVWRuTW5NeVEyaGhkalZ6VVRabGNEVjVhVEpNU25SYWZEQXhTMGhTVjBOTk4wVk9WRkpMVkZKT1dWcEtSa28xUlRaYVFrWkJUbGhKVVVnJTNEJTIyJTJDJTIyaSUyMiUzQSUyMmY3ZTEyZGUyLTU0MzEtNGUwMy1iNWVmLTQyY2ZjNTZiMTI2NCUyMiU3RA%3D%3D)

## Observações

- Priorizar desenvolvimento de funcionalidades que reduzam trabalho manual
- Garantir compatibilidade com dispositivos móveis para uso em campo
- Considerar funcionalidade offline para áreas com conectividade limitada
- Manter padrões visuais e de usabilidade consistentes com sistemas AXS existentes
