# Desenvolvendo com IA: MCP Server

> **Comece pelos slides: [Desenvolvendo com IA: MCP Server](./05.01_Desenvolvendo_com_IA_MCP_Server.pptx)**
>
> **Referência oficial (Capire):** [Native AI](https://cap.cloud.sap/docs/guides/ai/) · [@cap-js/mcp-server](https://github.com/cap-js/mcp-server)

Como dar a um agente de código acesso ao seu modelo CDS e à documentação oficial, com o MCP Server do CAP.

## O que você vai aprender

- O **MCP Server** ajuda quem desenvolve; o **MCP Adapter** expõe a aplicação a agentes
- O MCP Server é anterior ao CAP 10: o Adapter chegou como beta na versão 10
- Clientes MCP iniciam o servidor com `npx -y @cap-js/mcp-server`, sem mudar o projeto
- `search_model` procura no modelo compilado, incluindo anotações e endpoints
- `search_docs` faz busca semântica local na documentação do CAP
- Consulte modelo e documentação antes de gerar código, e valide com `cds watch` e testes

## Seções da aula

1. **Dois MCPs, dois papéis:** Os nomes são parecidos, mas um atende o desenvolvimento e o outro atende a aplicação em execução.
2. **Instalando o MCP Server:** O cliente MCP inicia o servidor com npx: não há nada para adicionar ao projeto.
3. **As duas ferramentas:** Uma olha para o seu projeto, a outra olha para o Capire. Juntas, reduzem as respostas inventadas.
4. **Trabalhando com o agente:** Um fluxo simples evita que o agente programe de memória em um framework que muda a cada versão.

---

[Voltar ao Módulo 05](../README.md) · Próxima aula: [05.02 MCP Adapter: serviços para agentes](../../modulo-05-ia-nativa/02-mcp-adapter/README.md)
