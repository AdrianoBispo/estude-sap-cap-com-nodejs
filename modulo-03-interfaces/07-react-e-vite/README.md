# React e Vite com CAP

> **Comece pelos slides: [React e Vite com CAP](./03.07_React_e_Vite_com_CAP.pptx)**
>
> **Referência oficial (Capire):** [Serving Vue.js or React](https://cap.cloud.sap/docs/guides/uis/vue-react) · [UI5 Web Components for React](https://github.com/UI5/webcomponents-react) · [UI5 Web Components & React](https://ui5.github.io/webcomponents/docs/frameworks/React/)

Como criar uma interface React com Vite em um projeto CAP e usar os wrappers de UI5 Web Components.

## O que você vai aprender

- `cds add react` cria um app com Vite, e `cds watch` o serve em `/catalog/`
- `ThemeProvider` envolve a aplicação, e `Assets.js` traz temas e idiomas
- Os wrappers expõem slots e eventos como propriedades React
- Serviços CAP são consumidos com `fetch` e a resposta OData em `value`
- Ações usam `POST` e respeitam `@requires`: 401 sem usuário
- `cds add app-frontend` e `cds up` levam a interface para a nuvem

## Seções da aula

1. **O projeto:** Um comando gera o app. O `cds watch` entende o Vite e serve tudo na mesma porta.
2. **A tela:** Os wrappers trazem componentes React de verdade, com propriedades e eventos naturais.
3. **Wrappers, Vue e implantação:** Vale conhecer as alternativas aos wrappers e o caminho até a nuvem.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [03.08 Angular com CAP](../../modulo-03-interfaces/08-angular/README.md)
