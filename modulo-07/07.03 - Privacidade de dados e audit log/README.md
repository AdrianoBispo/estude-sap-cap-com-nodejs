# Privacidade de dados e audit log

![Infográfico - Privacidade de Dados](./07.03_Privacidade_de_Dados.png)

> **Comece pelos slides: [Privacidade de dados e audit log](./07.03_Privacidade_de_dados_e_audit_log.pptx)**
>
> **Referência oficial (Capire):** [Data Privacy](https://cap.cloud.sap/docs/guides/security/data-privacy) · [Annotations](https://cap.cloud.sap/docs/guides/security/dpp-annotations) · [Audit Logging](https://cap.cloud.sap/docs/guides/security/dpp-audit-logging)

Como anotar dados pessoais uma vez e obter audit log, gestão de dados pessoais e apoio à conformidade.

## O que você vai aprender

- Anotar `@PersonalData` é a primeira, e muitas vezes a única, tarefa do desenvolvedor
- Entidades são `DataSubject`, `DataSubjectDetails` ou `Other`
- `DataSubjectID` identifica o titular em toda entidade anotada
- O plugin `@cap-js/audit-logging` audita alterações e leituras automaticamente
- A fila transacional garante a entrega e evita logs de operações desfeitas
- Um serviço dedicado integra a aplicação ao SAP Personal Data Manager

## Seções da aula

1. **Anotando dados pessoais:** A primeira, e muitas vezes a **única**, tarefa do desenvolvedor é identificar dados pessoais no modelo.
2. **Audit logging:** Com o modelo anotado, um **plugin** registra as operações sobre dados pessoais automaticamente.
3. **Gestão de dados pessoais:** Os mesmos metadados apoiam os direitos de **acesso** e de **esquecimento**.

## Material complementar

- PDF: [Privacidade de Dados](./07.03_Privacidade_de_Dados.pdf)
- Infográfico: [Privacidade de Dados](./07.03_Privacidade_de_Dados.png)

---

[Voltar ao Módulo 07](../README.md) · Próxima aula: [08.01 Testes automatizados com cds-test](../../modulo-08/08.01%20-%20Testes%20automatizados%20com%20cds-test/README.md)
