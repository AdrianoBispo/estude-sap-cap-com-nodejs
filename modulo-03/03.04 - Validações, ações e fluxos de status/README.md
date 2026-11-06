# Validações, ações e fluxos de status

> **Comece pelos slides: [Validações, ações e fluxos de status](./03.04_Validacoes_acoes_e_fluxos_de_status.pptx)**
>
> **Referência oficial (Capire):** [Constraints](https://cap.cloud.sap/docs/guides/services/constraints) · [Custom Actions](https://cap.cloud.sap/docs/guides/services/custom-actions) · [Status Flows](https://cap.cloud.sap/docs/guides/services/status-flows)

Regras de validação declarativas, operações próprias do domínio e transições de status controladas pelo runtime.

## O que você vai aprender

- `@mandatory` e `@assert` validam a entrada de forma **declarativa**, sem JavaScript
- Regras `@assert` viram uma **única consulta** no banco e desfazem a transação se falharem
- Coloque as restrições em arquivo próprio, separado do serviço
- **Actions** alteram dados e **functions** consultam; ambas exigem handler
- Operações **vinculadas** recebem a chave da entidade, como um `this`
- `@flow.status`, `@from` e `@to` validam e aplicam as transições de status

## Seções da aula

1. **Restrições declarativas:** Com `@assert` e `@mandatory`, as regras ficam **legíveis** e a validação é empurrada para o banco.
2. **Ações e funções:** Operações além do CRUD sempre exigem **implementação própria**.
3. **Fluxos de status:** Transições modeladas em CDS dispensam verificações manuais de estado.

---

[Voltar ao Módulo 03](../README.md) · Próxima aula: [03.05 Transações com cds.tx](../../modulo-03/03.05%20-%20Transa%C3%A7%C3%B5es%20com%20cds.tx/README.md)
