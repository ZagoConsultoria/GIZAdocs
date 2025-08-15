# Visão Analítica - Indicadores de Tecnologia

## Problema Atual

Os indicadores de todas as células estão espalhados por várias planilhas e não há confiabilidade desses dados. Além disso, quando esses dados são levados à visão analítica no Power BI, muitas limitações são encontradas da ferramenta.

## Solução Proposta

Trazer tudo para o sistema GIZA para trazer mais confiabilidade de dados e centralizar os BIs.

## Indicadores de Produto

Para implementar essa solução, começaremos com os indicadores de produto:

### 1. NPS GIZA + ZS

- **O que é**: Net Promoter Score integrado para ambas as plataformas
- **Base de dados**: Requer funcionalidade adicional no GIZA em todas as páginas e módulos - botão "Enviar Feedback"
- **Benefício**: Avaliações diretas dos usuários sem interferência externa

### 2. Usuários Ativos por Módulo

- **O que é**: Contagem de usuários únicos ativos em cada módulo
- **Base de dados**: Logs do GIZA
- **Métrica**: Distribuição de uso por funcionalidade

### 3. Taxa de Sucesso de Tarefas (Task Success Rate)

- **O que é**: Percentual de usuários que conseguem completar com sucesso um fluxo de trabalho crítico
- **Exemplo**: "Dos usuários que iniciaram o processo de 'Cadastro de Novo Cliente', quantos chegaram à tela de confirmação?"
- **Base de dados**: Logs de navegação e conclusão de tarefas

### 4. Tempo para Conclusão de Tarefa (Time to Completion)

- **O que é**: Tempo médio que um usuário leva para completar uma tarefa específica
- **Base de dados**: Deve vir do ZS, mapeando o tempo para realizar um formulário e enviar como metadado
- **Importância**: Reduções nesse tempo indicam melhorias na interface e ganhos de produtividade

### 5. Frequência de Uso (Stickiness) - Relação DAU/MAU

- **O que é**: Proporção de Usuários Ativos Diários (DAU) sobre os Usuários Ativos Mensais (MAU)
- **Métrica**: Porcentagem que indica a "aderência" do produto
- **Importância**: Mostra o quão integrado o GIZA está na rotina de trabalho dos usuários
- **Exemplo**: 50% significa que o usuário médio usa o sistema em 15 dos 30 dias do mês
- **Fonte de dados**: Logs do GIZA (requer contagem de usuários únicos por dia e por mês)

## Objetivo

Indicar se as soluções estão sendo efetivas e estão valendo o esforço investido.
