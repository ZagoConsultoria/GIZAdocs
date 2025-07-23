# Priorização dos Requisitos Funcionais — Módulo AXS (PRAD)

## Introdução

Este documento apresenta a priorização dos requisitos funcionais identificados durante o processo de elicitação para o módulo AXS (PRAD - Programa de Recuperação de Áreas Degradadas). A priorização foi realizada utilizando a técnica dos 100 pontos, considerando fatores como valor para o negócio, urgência de implementação, complexidade técnica e dependências entre funcionalidades.

O módulo AXS tem como foco principal o apoio às atividades de monitoramento e recuperação de áreas degradadas, permitindo coleta de dados em campo, gestão de evidências fotográficas e geração de relatórios técnicos especializados.

## Objetivo

Estabelecer uma ordem de prioridade clara para o desenvolvimento das funcionalidades do módulo AXS, baseada em:

- **Valor para o usuário final**: Funcionalidades que oferecem maior benefício prático
- **Dependências técnicas**: Requisitos que são pré-requisitos para outros
- **Complexidade de implementação**: Balanceamento entre esforço e retorno
- **Urgência do negócio**: Necessidades mais críticas para as operações de campo
- **Impacto no fluxo de trabalho**: Funcionalidades que otimizam processos existentes

## Tabela de Priorização {#tabela-priorizacao}

| Código   | Descrição                                                                                | Pontos  |
| -------- | ---------------------------------------------------------------------------------------- | ------- |
| RF01-AXS | Permitir coleta de dados no ZS de forma offline com possibilidade de edição.             | 25      |
| RF02-AXS | Transferir automaticamente os dados do ZS para o GIZA após exportação.                   | 20      |
| RF03-AXS | Exibir visualização das fotos por registro no GIZA para seleção e download.              | 20      |
| RF04-AXS | Permitir download de fotos por lote e por registro no GIZA.                              | 15      |
| RF05-AXS | Permitir edição de dados por registro diretamente no GIZA.                               | 10      |
| RF06-AXS | Exibir em dashboard uma tabela filtrável com os dados coletados.                         | 5       |
| RF07-AXS | Apresentar informações visuais de análise como: estado da planta, pragas, adubação, etc. | 5       |
| RF08-AXS | Opção de emitir relatórios editáveis com os dados dos registros                          | 5       |
|          | **Total**                                                                                | **100** |

## Análise da Priorização

### Requisitos de Alta Prioridade (20+ pontos)

- **RF01-AXS (25 pontos)**: A coleta offline é fundamental para operações de campo onde a conectividade pode ser limitada
- **RF02-AXS (20 pontos)**: A transferência automática otimiza o fluxo de trabalho e reduz erros manuais
- **RF03-AXS (20 pontos)**: Visualização de fotos é essencial para análise técnica e validação dos dados coletados

### Requisitos de Média Prioridade (10-19 pontos)

- **RF04-AXS (15 pontos)**: Download em lote facilita a organização de relatórios e documentação
- **RF05-AXS (10 pontos)**: Edição direta no GIZA oferece flexibilidade na correção de dados

### Requisitos de Baixa Prioridade (5-9 pontos)

- **RF06-AXS (5 pontos)**: Dashboard filtrável é uma funcionalidade de conveniência
- **RF07-AXS (5 pontos)**: Informações visuais agregam valor mas não são críticas
- **RF08-AXS (5 pontos)**: Relatórios editáveis são importantes mas podem ser implementados posteriormente

## Observações

- A priorização reflete as necessidades operacionais identificadas durante as sessões de elicitação
- Requisitos de alta prioridade são essenciais para o funcionamento básico do sistema
- A implementação deve seguir esta ordem para maximizar o valor entregue aos usuários
- Esta priorização poderá ser revista conforme feedback dos usuários e mudanças nos requisitos de negócio
