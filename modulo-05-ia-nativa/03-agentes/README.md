# Agentes com @agent

> **Comece pelos slides: [Agentes com @agent](./05.03_Agentes_com_agent.pptx)**
>
> **Referência oficial (Capire):** [CAP Agents](https://cap.cloud.sap/docs/guides/ai/cap-agents) · [The XTravels Sample](https://cap.cloud.sap/docs/guides/ai/xtravels-sample) · [Joule Integration](https://cap.cloud.sap/docs/guides/ai/joule-integration)

Como transformar um serviço em agente com @agent: protocolo A2A, identidade, skills, aprovação humana e limites de uso.

## O que você vai aprender

- `@agent` transforma um serviço em agente, servido por **A2A** em `/a2a/<serviço>`
- `@agent.hitl` pausa a tarefa até uma pessoa aprovar a ação
- `AGENTS.md` define identidade e prompt; `SKILL.md` descreve cada habilidade
- `cds.requires.llm` escolhe o modelo: `auto`, `aicore` ou `mock`
- Persistência, audit log e telemetria vêm integrados no Node.js
- Quotas limitam custo e abuso, com HTTP `429` antes da execução da tarefa

## Seções da aula

1. **Declarando:** Duas linhas de CDS criam o agente e protegem a ação que mexe no estoque.
2. **Identidade e skills:** Dois tipos de arquivo Markdown ao lado do serviço dizem quem o agente é e como ele executa cada tarefa.
3. **Configuração e execução:** Em desenvolvimento, o plugin procura credenciais locais. Em produção, conecta-se ao SAP AI Core.
4. **Pronto para produção:** O plugin já traz memória, auditoria, telemetria e limites. Falta decidir os valores certos para o seu caso.

---

[Voltar ao Módulo 05](../README.md) · Próxima aula: [05.04 Embeddings e SAP AI Core](../../modulo-05-ia-nativa/04-embeddings-e-ai-core/README.md)
