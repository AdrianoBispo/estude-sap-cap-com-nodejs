# Consumindo serviços remotos

![Infográfico - Dominando a Conexão de Serviços com CAP](./06.01_Dominando_a_Conex%C3%A3o_de_Servi%C3%A7os_com_CAP.png)

> **Comece pelos slides: [Consumindo serviços remotos](./06.01_Consumindo_servicos_remotos.pptx)**
>
> **Referência oficial (Capire):** [Consuming Services](https://cap.cloud.sap/docs/guides/services/consuming-services) · [Calesi](https://cap.cloud.sap/docs/guides/integration/calesi) · [Remote Services](https://cap.cloud.sap/docs/node.js/remote-services)

Como trazer APIs externas para o modelo, desenvolver com mocks, consultar e combinar dados locais e remotos.

## O que você vai aprender

- `cds import` transforma EDMX, OpenAPI e AsyncAPI em modelo CDS
- `cds watch` simula o serviço, com dados em `srv/external/data`
- Serviços remotos usam as **mesmas APIs** de consulta do CAP
- Projeções próprias isolam seu código e mapeiam campos automaticamente
- Exposição e `$expand` entre local e remoto exigem handlers próprios
- Em produção, destinations no perfil `[production]` apontam para o sistema real

## Seções da aula

1. **Importando a API:** `cds import` transforma uma especificação externa em **modelo CDS**, com a declaração do serviço pronta.
2. **Desenvolvendo com mocks:** Com o modelo importado, o `cds watch` **simula** o serviço remoto. Não é preciso acesso ao sistema real.
3. **Consultando:** Serviços remotos usam a **mesma API de consulta**. Projeções próprias isolam seu código do formato externo.
4. **Integrando:** Associações entre local e remoto precisam de **tratamento manual**, porque as fontes de dados são diferentes.
5. **Conectando de verdade:** Em produção, uma **destination** aponta para o sistema real, e o cliente HTTP cuida do resto.

## Material complementar

- Infográfico: [Dominando a Conexão de Serviços com CAP](./06.01_Dominando_a_Conex%C3%A3o_de_Servi%C3%A7os_com_CAP.png)
- Infográfico: [Remote Service Masterclass](./06.01_Remote_Service_Masterclass.png)

---

[Voltar ao Módulo 06](../README.md) · Próxima aula: [06.02 Conexões e service bindings](../../modulo-06/06.02%20-%20Conex%C3%B5es%20e%20service%20bindings/README.md)
