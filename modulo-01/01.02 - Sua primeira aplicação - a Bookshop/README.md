# Sua primeira aplicação: a Bookshop

> **Comece pelos slides: [Sua primeira aplicação: a Bookshop](./01.02_Primeira_aplicacao_Bookshop.pptx)**
>
> **Referência oficial (Capire):** [Bookshop Sample](https://cap.cloud.sap/docs/get-started/bookshop) · [Getting Started](https://cap.cloud.sap/docs/get-started/)

Do cds init ao serviço no ar: projeto, modelo, dados iniciais, serviços e o primeiro handler.

## O que você vai aprender

- `cds init` cria o projeto, `cds watch` recarrega a cada arquivo salvo e `cds add` faz crescer
- O modelo vai em `db/`, os serviços em `srv/` e as UIs em `app/`, sem configuração extra
- Arquivos **CSV** em `db/data` seguem o padrão `namespace-Entidade.csv`
- Cada serviço atende **um caso de uso**, com projeções, `@readonly` e `excluding`
- Restrições como `@mandatory` e `@assert` resolvem validação sem JavaScript
- Ações próprias precisam de um **handler** registrado com `this.on`

## Seções da aula

1. **O projeto:** O CAP prefere **convenção a configuração**: pastas com nomes padrão funcionam sem nenhum ajuste.
2. **Modelo e dados:** Ao salvar o modelo, o `cds watch` compila e implanta tudo em um **SQLite em memória**.
3. **Serviços:** Serviços são **orientados a casos de uso**: cada persona enxerga só o que precisa.
4. **Lógica própria:** Primeiro **declare** o que for possível. Escreva código para o que uma restrição não expressa.

---

[Voltar ao Módulo 01](../README.md) · Próxima aula: [01.03 Configuração e perfis com cds.env](../../modulo-01/01.03%20-%20Configura%C3%A7%C3%A3o%20e%20perfis%20com%20cds.env/README.md)
