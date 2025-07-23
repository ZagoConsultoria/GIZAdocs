# Especificação de Requisitos — Funcionalidade de Coleta e Gestão de Dados de Campo

## Introdução

Este documento tem como objetivo consolidar os requisitos identificados durante a entrevista com o usuário Willy, visando o desenvolvimento de uma funcionalidade para coleta, visualização, edição e geração de relatórios de dados de campo, com integração entre as plataformas ZS e GIZA.

## Objetivo

Desenvolver uma solução que permita:

- Coletar dados offline com posterior sincronização;

- Gerenciar evidências (fotos) de forma eficiente;

- Visualizar e editar registros diretamente no sistema GIZA;

- Automatizar processos que hoje são manuais, como a exportação de dados e geração de relatórios;

- Garantir facilidade de uso para usuários com conhecimento técnico limitado.

---

## Requisitos Funcionais {#requisitos-funcionais}

| Código | Descrição                                                                                |
| ------ | ---------------------------------------------------------------------------------------- |
| RF01-AXS   | Permitir coleta de dados no ZS de forma offline com possibilidade de edição.             |
| RF02-AXS   | Transferir automaticamente os dados do ZS para o GIZA após exportação.                   |
| RF03-AXS   | Exibir visualização das fotos por registro no GIZA para seleção e download.              |
| RF04-AXS   | Permitir download de fotos por lote e por registro no GIZA.                              |
| RF05-AXS   | Permitir edição de dados por registro diretamente no GIZA.                               |
| RF06-AXS   | Exibir em dashboard uma tabela filtrável com os dados coletados.                         |
| RF07-AXS   | Apresentar informações visuais de análise como: estado da planta, pragas, adubação, etc. |
| RF08-AXS   | Opção de emitir relatórios editáveis com os dados dos registros |

---

## Requisitos Não Funcionais {#requisitos-nao-funcionais}

| Código | Descrição                                                                                      |
| ------ | ---------------------------------------------------------------------------------------------- |
| RNF01-AXS  | Não exigir treinamento adicional para os usuários finais.                                      |
| RNF02-AXS  | A aplicação deve funcionar com nível básico de conhecimento em informática.                    |
| RNF03-AXS  | A solução deve integrar-se com o TimeStamp, se necessário.                                     |
| RNF04-AXS  | A aplicação deve ter boa performance durante uso em campo e nas visualizações do GIZA.         |
| RNF05-AXS  | A aplicação deve operar com alta confiabilidade em ambientes offline e sincronizar sem falhas. |
