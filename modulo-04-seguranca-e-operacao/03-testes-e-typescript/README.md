# Testes e TypeScript

> **Comece pelos slides: [Testes e TypeScript](./04.03_Testes_e_TypeScript.pptx)**
>
> **Referência oficial (Capire):** [Testing with cds.test](https://cap.cloud.sap/docs/node.js/cds-test) · [Using TypeScript](https://cap.cloud.sap/docs/node.js/typescript) · [CDS Typer](https://cap.cloud.sap/docs/tools/cds-typer)

Como testar serviços CAP de ponta a ponta com cds.test e ligar TypeScript no projeto, com tipos gerados do modelo.

## O que você vai aprender

- `cds.test()` inicia um **servidor real** e deve ser a primeira chamada do teste
- `GET`, `POST` e `defaults` simplificam chamadas HTTP autenticadas
- `data.reset` reimplanta o banco, e `cds.test.log()` captura a saída
- Compare códigos e subconjuntos, e não mensagens nem respostas inteiras
- Com Node 24 e `@sap/cds` 10.2, handlers `.ts` rodam direto; em produção, **sempre** pré-compile com `cds build`
- `cds-typer` gera tipos do modelo, disponíveis em `#cds-models`

## Seções da aula

1. **Primeiro teste:** Instale o pacote de desenvolvimento e escreva um teste que inicia o servidor na primeira linha.
2. **Testando serviços:** Teste pela **API HTTP**, ou chame o serviço direto no código quando for testar a lógica interna.
3. **Boas práticas:** Testes resistentes verificam **apenas o que importa** e se mantêm independentes do runner.
4. **TypeScript:** Como ligar TypeScript no projeto, rodar sem configuração e gerar tipos a partir do modelo.

---

[Voltar ao Módulo 04](../README.md) · Próxima aula: [04.04 Logs e boas práticas](../../modulo-04-seguranca-e-operacao/04-logs-e-boas-praticas/README.md)
