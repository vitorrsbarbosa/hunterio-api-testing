# Projeto de automação (HealthCheck)

---

## Passo a passo:

1. Ler documentação da API; ✅
1. Criar Workspace; ✅
1. Convidar membros;
1. Criar ambientes e variáveis; ✅
1. Criar estrutura da coleção; ✅
1. Criar requisições conforme a [tabela](https://docs.google.com/spreadsheets/d/1IUXoidAsZU_sek6IOepk8JCQuWW5Cn8NLsSUHfEwvtY/edit#gid=803971452); ✅
1. Parametrizar variáveis; ✅
1. Criar arquivo de dados; ✅
1. Parametrizar autenticação; ✅
1. Criar pré-request scripts; ✅
1. Criar testes; ✅
1. Criar e executar com monitor (criar um monitor para cada ambiente) - [monitor criado](https://barbosa-vitor.postman.co/workspace/Health-Check-HUNTER.IO~5addf443-e071-42f8-8997-bf0a599fda21/monitor/1ed2bbf7-1c7f-40b0-890f-8ed414789db5);
1. Exportar resultados das execuções; ✅
1. Exportar coleção e ambiente; ✅
1. Instalar, caso não tenha, [node.js](https://nodejs.org/), [newman](https://www.npmjs.com/package/newman), [html-reporter](https://www.npmjs.com/package/newman-reporter-html) e [htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
1. Criar estrutura de pastas para newman;
1. Executar via newman coleção e ambiente exportados tanto pelo path quanto pela url.

`newman run hunter.io.postman_collection.json -e Desenvolvimento.postman_environment.json -d data_file.json`
