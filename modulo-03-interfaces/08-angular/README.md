# Angular com CAP

> **Comece pelos slides: [Angular com CAP](./03.08_Angular_com_CAP.pptx)**
>
> **Referência oficial (Capire):** [UI5 Web Components & Angular](https://ui5.github.io/webcomponents/docs/frameworks/Angular/) · [Fundamental NGX](https://sap.github.io/fundamental-ngx/)

Como consumir um serviço CAP em Angular, com os wrappers de UI5 Web Components, proxy e HttpClient.

## O que você vai aprender

- Não há `cds add angular`: use o Angular CLI e consuma o CAP como API
- A versão de `@fundamental-ngx/ui5-webcomponents` acompanha a do Angular
- O `proxy.conf.json` encaminha `/browse` ao CAP, sem precisar de CORS
- `HttpClient` e `signal` trazem os dados tipados para o template
- Eventos dos wrappers têm prefixo, como `(ui5Click)`
- Wrappers dispensam `CUSTOM_ELEMENTS_SCHEMA` e integram formulários

## Seções da aula

1. **Preparando:** A versão do wrapper acompanha a versão do Angular. Comece escolhendo as duas.
2. **A tela:** Os wrappers são componentes standalone: basta importá-los onde forem usados.
3. **Formulários e alternativas:** Os wrappers aproveitam recursos do Angular que tags puras não oferecem.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [04.01 Autenticação e autorização](../../modulo-04-seguranca-e-operacao/01-autenticacao-e-autorizacao/README.md)
