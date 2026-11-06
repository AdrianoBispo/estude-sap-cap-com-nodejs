# UI5 Web Components: fundamentos

> **Comece pelos slides: [UI5 Web Components: fundamentos](./03.05_UI5_Web_Components_fundamentos.pptx)**
>
> **Referência oficial (Capire):** [UI5 Web Components](https://ui5.github.io/webcomponents/docs/) · [First Steps](https://ui5.github.io/webcomponents/docs/getting-started/first-steps/) · [Components](https://ui5.github.io/webcomponents/components/)

O framework web da SAP: componentes HTML padrão, com visual Fiori, que funcionam em qualquer stack.

## O que você vai aprender

- UI5 Web Components são elementos HTML padrão, com visual Fiori e sem amarrar o framework
- Use SAPUI5 e Fiori Elements em apps de gestão; Web Components em stacks próprias
- Não há CDN: instale pelo npm e importe só o que vai usar
- Importar um módulo registra a tag, e nem sempre o nome é igual, como em `ui5-li`
- A API tem atributos, propriedades, slots, eventos e métodos
- Um proxy no Vite e um `fetch` bastam para ler um serviço CAP

## Seções da aula

1. **Pacotes:** Os componentes são módulos ES6 publicados no npm. Não há CDN: cada aplicação importa e empacota só o que usa.
2. **Primeiros passos:** Com Vite, bastam quatro passos: criar, instalar, importar e usar a tag.
3. **As APIs de um componente:** Como são elementos HTML, tudo funciona com DOM padrão. Na prática, o seu framework faz isso por você.
4. **Lendo dados do CAP:** Sem framework: um proxy no Vite, um fetch e elementos criados com o DOM.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [03.06 UI5 Web Components: temas e recursos](../../modulo-03-interfaces/06-ui5-web-components-avancado/README.md)
