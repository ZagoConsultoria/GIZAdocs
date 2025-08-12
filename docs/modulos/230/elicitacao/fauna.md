# Elicitação de Requisitos - Módulo Fauna

## Introdução

Este documento apresenta a elicitação de requisitos funcionais e não funcionais para o módulo **Fauna**, responsável pela coleta, armazenamento, tratamento e distribuição de dados de fauna (atropelamento, resgate, afugentamento) com base no discovery realizado com os stakeholders.

## Objetivo

Definir requisitos claros para o desenvolvimento de uma solução integrada que permita:

- Coleta de dados de fauna em campo com captura automática de GPS e fotos.
- Armazenamento automático em banco de dados parametrizado.
- Operação offline com sincronização automática dos registros.
- Geração de relatórios automáticos com imagens, tabelas e gráficos comparativos.

---

## Requisitos Funcionais {#requisitos-funcionais}

| **ID**   | **Descrição**                                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF01-230 | Permitir coleta de dados de fauna atropelada via ZS com formulário digital, incluindo captura automática de coordenadas GPS e fotos.                                  |
| RF02-230 | Integrar upload automático de fotos georreferenciadas ao GIZA e SharePoint, sem necessidade de upload manual.                                                         |
| RF03-230 | Armazenar automaticamente dados de fauna (atropelamento, resgate, afugentamento) em banco de dados parametrizado, eliminando uso de planilhas manuais.                |
| RF04-230 | Permitir funcionamento offline durante a coleta de dados, com sincronização automática dos registros ao reconectar.                                                   |
| RF05-230 | Registrar e categorizar espécimes de fauna por tipo de evento (resgate, afugentamento, atropelamento), incluindo campos para observações e características do animal. |
| RF06-230 | Gerar relatórios automáticos de fauna, incluindo fotos favoritas, tabelas e gráficos comparativos com períodos anteriores.                                            |

---

## Requisitos Não Funcionais {#requisitos-nao-funcionais}

| **ID**    | **Descrição**                                                                                    |
| --------- | ------------------------------------------------------------------------------------------------ |
| RNF01-230 | Sistema deve suportar operação offline por até 7 dias consecutivos sem conectividade.            |
| RNF02-230 | Sincronização automática dos dados deve ocorrer em até 10 minutos após reconexão.                |
| RNF03-230 | Interface deve ser otimizada para uso em aparelhos Android.                      |
| RNF04-230 | Comunicação com APIs e backend deve usar HTTPS e criptografia para garantir segurança dos dados. |
| RNF05-230 | Tempo de resposta para consultas e geração de relatórios deve ser inferior a 3 segundos.         |
| RNF06-230 | Aplicação deve ser intuitiva, sem necessidade de treinamento adicional para usuários finais.     |
| RNF07-230 | Sistema deve suportar até 500 fotos por registro sem degradação significativa de performance.    |
