## Priorização dos Requisitos Funcionais – Técnica dos 100 Dólares

### Objetivo
Estabelecer a prioridade dos requisitos funcionais identificados na entrevista com a usuária Bruna Ferrari, com base na percepção de valor e urgência para o negócio e para o uso prático da aplicação.

### Introdução
Durante o processo de elicitação de requisitos, foram levantadas diversas funcionalidades desejadas pela usuária final para apoiar atividades relacionadas à coleta e tratamento de dados atmosféricos, geração de relatórios e integração com sistemas utilizados internamente. Para orientar o desenvolvimento incremental do sistema, realizou-se uma etapa de priorização com a participação direta da usuária.

### Metodologia
Foi utilizada a técnica dos **100 dólares**, na qual a usuária distribuiu uma quantia simbólica de $100 entre os requisitos funcionais, de acordo com a importância percebida. Quanto maior o valor atribuído a um requisito, maior a sua prioridade de implementação. Esse método facilita decisões quando há limitação de tempo, orçamento ou recursos de desenvolvimento.

### Tabela de Priorização

| **ID**  | **Requisito Funcional**                                                                 | **Valor ($)** |
|--------|-------------------------------------------------------------------------------------------|---------------|
| RF01   | Permitir a coleta de dados de fumaça preta e gases via ZS.                               | 15.00         |
| RF04   | Permitir funcionamento offline durante a coleta.                                         | 15.00         |
| RF02   | Ficha de coleta deve incluir CO₂, CO e SO₂, com dados organizados por ponto de coleta.   | 10.00         |
| RF03   | Anexar automaticamente as evidências fotográficas ao GIZA e SharePoint.                  | 10.00         |
| RF05   | Armazenar os dados em banco de dados seguro.                                             | 10.00         |
| RF08   | Permitir download de fotos por lote ou por registro individual.                          | 10.00         |
| RF09   | Exibir dados em formato de tabela filtrável e exportável.                                | 10.00         |
| RF06   | Integrar com ZS, GIZA e TimeStamp.                                                       | 05.00         |
| RF07   | Exibir tabela no GIZA com filtro e farol de cor (ex: fumaça preta > 40% em vermelho).    | 05.00         |
| RF10   | Gerar esqueleto de relatório Word com tabelas prontas para completar com dados extras.   | 05.00         |
| RF12   | Permitir inserção manual de dados complementares (particulados, gráficos, fotos).        | 04.00         |
| RF11   | Gerar relatórios conforme padrão regulatório ambiental.                                  | 02.00         |

### Observações
- A soma total é de $101 devido a arredondamentos, o que é aceitável nesta técnica.
- Os requisitos RF01 e RF04 foram os mais valorizados, indicando que a coleta estruturada e o funcionamento offline são aspectos críticos para o sucesso da solução.

