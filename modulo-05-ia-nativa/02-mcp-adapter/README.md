# MCP Adapter: serviços para agentes

> **Comece pelos slides: [MCP Adapter: serviços para agentes](./05.02_MCP_Adapter.pptx)**
>
> **Referência oficial (Capire):** [MCP Services](https://cap.cloud.sap/docs/guides/ai/cap-mcp)

Como expor um serviço CAP a agentes de IA com uma anotação, o que o adaptador serve e o que ainda fica por sua conta.

## O que você vai aprender

- `@mcp` torna o serviço acessível a agentes, como mais um protocolo do CAP
- O endpoint padrão é `/mcp/<serviço>`, e `@mcp: 'nome'` troca o caminho
- Doc comments e `@mcp.instructions` dão ao agente o contexto do domínio
- `describe`, `query` e `call` cobrem descoberta, leitura com CQL e ações não vinculadas
- Em desenvolvimento, `cds watch` registra os endpoints nos clientes locais
- Autorização, *prompt injection* e governança continuam sendo sua responsabilidade

## Seções da aula

1. **Declarando:** Instale o plugin, anote o serviço e escreva o contexto que o modelo de linguagem precisa ler.
2. **As ferramentas:** Toda consulta passa pelo serviço. Testamos as três em um projeto real com a livraria.
3. **Limites e segurança:** O adaptador é fino de propósito. Muito do que protege uma aplicação em produção continua sendo seu trabalho.

---

[Voltar ao Módulo 05](../README.md) · Próxima aula: [05.03 Agentes com @agent](../../modulo-05-ia-nativa/03-agentes/README.md)
