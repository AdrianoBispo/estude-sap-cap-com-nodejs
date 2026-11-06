# Definindo e servindo serviços

![Infográfico - Definindo e servindo serviços](./02.01_Infografico.png)

> **Comece pelos slides: [Definindo e servindo serviços](./02.01_Definindo_e_servindo_servicos.pptx)**
>
> **Referência oficial (Capire):** [Providing Services](https://cap.cloud.sap/docs/guides/services/providing-services) · [Served Out of the Box](https://cap.cloud.sap/docs/guides/services/served-ootb) · [cds.ApplicationService](https://cap.cloud.sap/docs/node.js/app-services)

Como desenhar serviços por caso de uso e o que o provedor genérico faz sem nenhuma linha de código.

## O que você vai aprender

- Uma definição de serviço basta para um **servidor completo**, sem código
- Serviços são **fachadas**: projeções moldam e escondem dados para cada uso
- Crie **um serviço por caso de uso**; evite expor tudo em 1:1
- Composições são criadas em profundidade; associações só recebem a chave
- `cds.ApplicationService` registra os handlers genéricos no `init()`
- Desde o cds 10, escritas devolvem um array com `.affected`, e o resultado de `CREATE` precisa ser iterado antes de ler as chaves

## Seções da aula

1. **Definindo serviços:** Serviços expõem **projeções** sobre o domínio, moldadas para quem vai consumir.
2. **Servido pronto:** Os handlers genéricos atendem **a maioria das requisições**. O código próprio fica restrito à lógica específica do seu negócio.
3. **cds.ApplicationService:** O provedor padrão é uma classe comum. Entender seu `init()` explica de onde vem o comportamento pronto.

---

[Voltar ao Módulo 02](../README.md) · Próxima aula: [02.02 Handlers, requisições e erros](../../modulo-02-servicos-e-dados/02-handlers-requisicoes-e-erros/README.md)
