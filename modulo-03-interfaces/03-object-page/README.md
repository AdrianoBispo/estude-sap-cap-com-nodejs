# Object Page: cabeçalho, seções e regras

> **Comece pelos slides: [Object Page: cabeçalho, seções e regras](./03.03_Object_Page_cabecalho_secoes_e_regras.pptx)**
>
> **Referência oficial (Capire):** [Curso SAP: Fiori Elements com CAP OData V4](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service) · [Soluções do curso](https://github.com/SAP-samples/fiori-elements-v4-cap-advanced) · [Feature Showcase](https://github.com/SAP-samples/fiori-elements-feature-showcase)

Como montar o cabeçalho, organizar as seções e aplicar regras dinâmicas e validações na Object Page.

## O que você vai aprender

- `UI.HeaderInfo` define título e descrição; `UI.HeaderFacets` traz os indicadores
- `UI.Identification` lista ações, e `Determining: true` as leva ao rodapé
- `UI.Facets` organiza seções, e `PartOfPreview: false` cria o **Exibir mais**
- `@UI.Hidden` aceita expressões, avaliadas na própria tela
- `Common.SideEffects` relê valores quando a origem muda
- Regras ficam no serviço, com `@assert` e handlers, e o `target` leva a mensagem ao campo

## Seções da aula

1. **Cabeçalho:** O topo da página responde à primeira pergunta do usuário: o que é este registro e como ele está?
2. **Corpo da página:** Seções e grupos de campos organizam o conteúdo. O que é secundário pode ficar escondido atrás de um botão.
3. **Regras dinâmicas:** A tela reage aos dados: campos somem, viram obrigatórios e são recalculados sem recarregar a página.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [03.04 Extensões, navegação e análise](../../modulo-03-interfaces/04-extensoes-navegacao-e-analise/README.md)
