# Guia de Estudos SAP CAP com Node.js

![Infografico - Guia Rapido de Desenvolvimento SAP CAP (Node.js)](./Infografico%20-%20Guia%20de%20Desenvolvimento%20SAP%20CAP%20com%20Nodejs.png)

> **Este repositório é um curso completo para desenvolvedores que desejam aprender e dominar o SAP Cloud Application Programming Model (CAP) com Node.js. Ele parte da primeira aplicação e segue até a produção, com slides guiados, infográficos e referências à documentação oficial.**

## Estrutura do Curso

São 10 módulos e 40 aulas, na ordem recomendada de estudo. Os módulos 1 a 8 seguem o caminho de uma aplicação real, do projeto vazio à produção. O módulo 9 trata de SaaS e extensões, e o módulo 10 é um aprofundamento nos internos do CAP, para estudar depois que os conceitos estiverem firmes.

| Módulo | Aulas | Descrição |
| :--- | :---: | :--- |
| **[Módulo 01: Primeiros Passos com CAP](./modulo-01/README.md)** | 3 | O que é o CAP, como ele pensa e como criar, rodar e configurar a primeira aplicação. |
| **[Módulo 02: Modelagem de Domínio com CDS](./modulo-02/README.md)** | 5 | A linguagem CDL, os tipos, os aspectos e as decisões de modelo que definem a aplicação. |
| **[Módulo 03: Serviços e Lógica de Negócio](./modulo-03/README.md)** | 6 | Do contrato do serviço às regras de negócio em Node.js, com handlers, erros, validações e transações. |
| **[Módulo 04: Consultas e Persistência](./modulo-04/README.md)** | 5 | CQL, cds.ql, bancos de dados e localização: como os dados entram, saem e mudam de idioma. |
| **[Módulo 05: Interfaces com SAP Fiori](./modulo-05/README.md)** | 2 | Como as anotações viram telas e como o draft dá ao usuário uma edição segura. |
| **[Módulo 06: Integração e Eventos](./modulo-06/README.md)** | 3 | Como conectar a aplicação a sistemas externos e desacoplar serviços com mensageria. |
| **[Módulo 07: Segurança e Privacidade](./modulo-07/README.md)** | 3 | Quem é o usuário, o que ele pode fazer e como proteger dados pessoais. |
| **[Módulo 08: Testes, Deploy e Operação](./modulo-08/README.md)** | 4 | Da suíte de testes à produção: logs, build, Cloud Foundry, Kyma, CI/CD e boas práticas. |
| **[Módulo 09: SaaS e Extensibilidade](./modulo-09/README.md)** | 3 | Aplicações multitenant, extensões por cliente, feature toggles e plugins reutilizáveis. |
| **[Módulo 10: Por Dentro do CAP](./modulo-10/README.md)** | 6 | Aprofundamento: as notações, o compilador, a reflexão e o runtime por baixo das APIs. |

Todos os exemplos usam a livraria (*bookshop*) da documentação oficial, para que uma aula continue de onde a anterior parou.

## Como Estudar Cada Aula

Cada pasta de aula traz:

1. **Slides (`.pptx`):** o material principal, no Design System SAP Horizon, dividido em seções e com um resumo no último slide. As anotações do apresentador de cada slide apontam para a referência oficial.
2. **README:** objetivos, seções da aula e links para o Capire.
3. **Infográficos:** resumo visual para consulta rápida.

## Organização e Nomenclatura dos Arquivos

Para garantir a organização, a rastreabilidade e a sequência lógica de leitura dos arquivos do projeto, foi definida a seguinte **Regra de Nomenclatura Hierárquica**: **`DD.SS_Slug_Descritivo`**

1. **DD (Módulo)**: Dois dígitos representando a pasta `modulo-DD`.
2. **SS (Aula)**: Dois dígitos representando a aula dentro do módulo.
3. **Slug Descritivo**: O nome original ou simplificado do tópico, separado por underlines para legibilidade.

## Como Contribuir

Contribuições são bem-vindas! Se você encontrar erros, tiver sugestões de melhoria ou quiser adicionar novo conteúdo, siga estes passos:

1.  **Fork** este repositório.
2.  Crie uma nova **branch** para sua feature (`git checkout -b feature/nova-feature`).
3.  Faça suas alterações e **commit** (`git commit -m 'feat: Adiciona nova feature'`).
4.  Envie para a sua branch (`git push origin feature/nova-feature`).
5.  Abra um **Pull Request**.

## Links Úteis

  ### Documentação Oficial
  - [Capire - Documentação Oficial da SAP CAP](https://cap.cloud.sap/docs/)
  - [capire/bookshop - Exemplo usado nas aulas](https://github.com/capire/bookshop)

  ### Cursos Oficiais da SAP
  - [SAP Learning - Introduction to SAP Cloud Application Programming Model](https://learning.sap.com/courses/introduction-to-sap-cloud-application-programming-model)
  - [SAP Learning - Develop extensions with SAP Cloud Application Programming Model](https://learning.sap.com/courses/develop-extensions-with-sap-cloud-application-programming-model)
  - [SAP Learning - Desenvolva extensões com CAP seguindo o Guia do desenvolvedor SAP BTP](https://learning.sap.com/courses/develop-extensions-with-cap-following-the-sap-btp-developer-s-guide)
  - [SAP Learning - Desenvolvendo um aplicativo SAP Fiori Elements baseado em um serviço CAP OData V4](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service)

  ### Tutoriais Oficiais da SAP
  - [Tutorial SAP - Crie um aplicativo de negócios CAP utilizando o VS Code e Nodejs](https://developers.sap.com/mission.cp-starter-extensions-cap.html)
  - [Tutorial SAP - Desenvolva uma aplicação CAP Full-Stack seguindo o Guia do Desenvolvedor SAP BTP](https://developers.sap.com/group.cap-application-full-stack.html)
  - [Tutorial SAP - Como Criar uma Aplicação SAP CAP Full Stack utilizando o BAS, Nodejs e Banco Hana](https://developers.sap.com/mission.hana-cloud-cap.html)
  - [Tutorial SAP - Desenvolva um aplicativo Node.js no SAP BTP Kyma Runtime](https://developers.sap.com/mission.cp-kyma-node-js.html)
  - [Tutorial SAP - Crie um aplicativo com Cloud Foundry Node.js Buildpack](https://developers.sap.com/tutorials/btp-cf-buildpacks-node-create.html)
  - [Tutorial SAP - Como desenvolver um App de Mensagens dentro do SAP BTP utilizando o Nodejs ou Java](https://developers.sap.com/mission.cp-enterprisemessaging-app-develop.html)

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

_Os slides foram escritos a partir da [documentação oficial do CAP (Capire)](https://cap.cloud.sap/docs/). Os infográficos foram gerados pelo Notebook LM com base na mesma documentação._
