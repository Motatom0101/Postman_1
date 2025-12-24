# 🎯Teste em APIs com Postman📝
[![Cypress](https://api.devicons.dev.br/icon?icons=Postman%2CVSCode&size=48&theme=light&perline=30)](https://devicons.dev.br/)

Este repositório contém a documentação dos meus estudos em **testes de APIs com Postman** e projeto.

## 📚 Artigos onde documentei o que fiz:

[Postman do Básico ao Avançado com Projetos — parte 1](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-parte-1-75e937d37998?postPublishedType=initial)

Neste artigo trago o início da documentação do meu aprendizado no curso “Postman do Básico ao Avançado com Projetos”, do prof.: Gustavo Eduardo Silva Machado.

**Veremos:**

   - Definição de API a analogia para aplicabilidade e fixação do conceito.
   - Como um QA testaria uma API no Postman e quais tipos de teste poderia fazer.
   - Principais tipos de APIs.
   - Relação das APIS com o Postman.
   - Introdução ao Postman e sua estrutura básica.

 
[Postman do Básico ao Avançado com Projetos — parte 2](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-parte-2-3c85a21c056b) 

Neste artigo, migramos da teoria para como iniciar a estruturação profissional de testes. Abordo melhores práticas, essenciais no dia a dia do QA moderno, como:

   - **Organização e Governança**: Estruturação de Workspaces e Collections para projetos escaláveis, incluindo onde criar documentação e o rastreamento do histórico de modificações (Changelog).
   - **Reutilização e Segurança (Environments)**: O domínio de Variáveis de Ambiente (Environments) para tornar Collections flexíveis, reutilizáveis e seguras, permitindo a simulação de autenticação e a rápida alternância entre ambientes (Desenvolvimento/Produção).
   - Conheceremos os **3 escopos de Variáveis** e suas **prioridades**.
   - **Integração e Automação**: Demonstração de como realizar o Export de Collections e Environments para fins de automação e integração em **pipelines de CI/CD** (Continuous Integration/Continuous Delivery).


[Postman do Básico ao Avançado com Projetos — parte 3](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-parte-3-ea6af702931f?postPublishedType=initial)

   **Nele veremos:**
   
   - **Pré-request** Script e **Post-response** Script e suas funções.
   - **Criação de variáveis** nestas sessões.
   - **Snippets** na criação de código JavaScript para teste.
   - **Análise de alguns códigos**.
   - Breve **introdução ao framework de teste interno do Postman**, **baseado na** biblioteca de asserções **Chai do JS**.
   - Criação e execução do **1º teste funcional no Postman**.
 

[Postman do Básico ao Avançado com Projetos — parte 4](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-parte-4-9830b05a5dfa?postPublishedType=initial)

**Veremos:**

O recurso Runner, que permite executar uma Coleção, uma Pasta ou um grupo de requisições de forma sequencial e automatizada.
#
#
## Exercícios📝
[Postman do Básico ao Avançado com Projetos — Exercício 1](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-exerc%C3%ADcio-1-e880bb2739bc?postPublishedType=initial)

**Veremos:**

Agora que conhecemos a interface Do Postman e as principais features, vamos fazer alguns exercícios. Neste primeiro, validaremos o status code 200 e os parâmetros ‘page’ e ‘per_page’ em um teste funcional de contrato, para validarmos os valores acordados nos parâmetros já citados. Para tanto, usaremos a API pública ‘ReqRes’, que eu penei um pouco até entender que, diferente de quando o professor executou o teste, agora precisava criar uma key para criar uma variável no ‘Headers’.

[Postman do Básico ao Avançado com Projetos — Exercício 2](https://medium.com/@atom.free/postman-do-b%C3%A1sico-ao-avan%C3%A7ado-com-projetos-exerc%C3%ADcio-2-cf27f5eb5d85?postPublishedType=initial)

**Veremos:**

Vamos usar a API pública ReqRes e seu Swagger para desenvolver o exercício. Faremos uma busca em um conjunto de informações fictícias de 2 usuários não randômicos, a fim de validarmos se o email que virá na request é o mesmo que esperávamos e uma asserção para o status code 200.

Loading...
