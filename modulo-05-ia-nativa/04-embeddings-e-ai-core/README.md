# Embeddings e SAP AI Core

> **Comece pelos slides: [Embeddings e SAP AI Core](./05.04_Embeddings_e_SAP_AI_Core.pptx)**
>
> **Referência oficial (Capire):** [Vector Embeddings](https://cap.cloud.sap/docs/guides/ai/embeddings) · [AI Plugin](https://cap.cloud.sap/docs/plugins/)

Como guardar e comparar vetores no modelo CDS para busca semântica, e o que o plugin @cap-js/ai acrescenta.

## O que você vai aprender

- Embeddings transformam conteúdo em vetores, que permitem comparar por **significado**
- `Vector` e `vector_embedding(...) stored` mantêm os vetores atualizados ao gravar
- `cosine_similarity` e `l2distance` entram em consultas CQL comuns
- Use `DOCUMENT` no conteúdo, `QUERY` na pergunta e o **mesmo modelo** nos dois
- SAP HANA é nativo, PostgreSQL usa `pgvector`, e o SQLite emula por caracteres
- `@cap-js/ai` traz modelos locais, recomendações em Fiori e o SAP AI Core como serviço

## Seções da aula

1. **No modelo:** Um tipo novo e uma função do banco bastam para gerar vetores sempre atualizados.
2. **Consultando:** As funções de vetor entram na CQL como qualquer outra função, com o comportamento do SAP HANA.
3. **Bancos e testes locais:** O suporte muda bastante de um banco para outro, e o SQLite pede atenção ao interpretar resultados.
4. **Plugin @cap-js/ai:** Além dos testes locais, o plugin leva recomendações às telas e traz o SAP AI Core para o estilo CAP.

---

[Voltar ao Módulo 05](../README.md) · Próxima aula: [06.01 SaaS e extensões](../../modulo-06-avancado/01-saas-e-extensoes/README.md)
