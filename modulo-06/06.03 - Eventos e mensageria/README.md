# Eventos e mensageria

![Infográfico - Events Zero Code Microservices](./06.03_Events_Zero_Code_Microservices.png)

> **Comece pelos slides: [Eventos e mensageria](./06.03_Eventos_e_mensageria.pptx)**
>
> **Referência oficial (Capire):** [Events & Messaging](https://cap.cloud.sap/docs/guides/events/) · [Messaging](https://cap.cloud.sap/docs/node.js/messaging) · [Event Queues](https://cap.cloud.sap/docs/node.js/event-queues)

Como declarar, emitir e receber eventos, levar mensagens entre processos e garantir a entrega com filas.

## O que você vai aprender

- Todos os serviços **emitem eventos**, e os mecanismos são os mesmos das requisições
- Eventos são declarados no CDS, ao lado da API síncrona
- Emissores usam `srv.emit`, e receptores se conectam e usam `srv.on`
- Mudar de canal é configuração: `file-based-messaging` no desenvolvimento, broker em produção
- Com mensageria, o que é emitido durante uma queda **chega depois**
- `cds.queued` liga o envio à transação, com novas tentativas e dead letter

## Seções da aula

1. **Declarar, emitir e receber:** Serviços têm API **síncrona e assíncrona**. Eventos são declarados no modelo, com foco no domínio.
2. **Entre processos:** Com serviços em processos separados, um **canal de mensagens** repassa os eventos. Só muda a configuração.
3. **Filas de eventos:** Filas persistentes ligam a mensagem à **transação**: só é enviada se a gravação der certo.

## Material complementar

- Infográfico: [Events Zero Code Microservices](./06.03_Events_Zero_Code_Microservices.png)
- Infográfico: [Nodejs Mensageria Assincrona](./06.03_Nodejs_Mensageria_Assincrona.png)

---

[Voltar ao Módulo 06](../README.md) · Próxima aula: [07.01 Autenticação e usuários](../../modulo-07/07.01%20-%20Autentica%C3%A7%C3%A3o%20e%20usu%C3%A1rios/README.md)
