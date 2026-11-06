# List Report: filtros, ações e visões

> **Comece pelos slides: [List Report: filtros, ações e visões](./03.02_List_Report_filtros_acoes_e_visoes.pptx)**
>
> **Referência oficial (Capire):** [Curso SAP: Fiori Elements com CAP OData V4](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service) · [Soluções do curso](https://github.com/SAP-samples/fiori-elements-v4-cap-advanced) · [Feature Showcase](https://github.com/SAP-samples/fiori-elements-feature-showcase)

Como configurar a barra de filtros, as ações, o conteúdo das colunas e as múltiplas visões de um List Report.

## O que você vai aprender

- `UI.SelectionFields` escolhe os filtros, e `@title` evita nomes técnicos
- Semântica fica no CDS; `initialLoad` e `hideFilterBar` ficam no `manifest.json`
- `DataFieldForAction` cria o botão, e `Core.OperationAvailable` decide quando ele vale
- Depois de uma ação, `Common.SideEffects` atualiza a tela
- `DataPoint` e `UI.Chart` levam progresso e micro charts às colunas
- `SelectionVariant` cria recortes, exibidos em abas com `views`

## Seções da aula

1. **Barra de filtros:** Os filtros vêm do modelo: você escolhe quais aparecem, quais são obrigatórios e como as datas funcionam.
2. **Ações:** Uma ação do serviço vira botão com uma linha de anotação. A disponibilidade também pode vir dos dados.
3. **Conteúdo das colunas:** Colunas mostram mais do que texto: progresso, gráficos e cartões de contato também são anotações.
4. **Múltiplas visões:** A mesma lista pode oferecer recortes prontos, em uma tabela ou em abas com tabelas próprias.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [03.03 Object Page: cabeçalho, seções e regras](../../modulo-03-interfaces/03-object-page/README.md)
