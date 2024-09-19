## StackSpot Plugin

## Jinja

You can use jinja to make a template-data folder more dynamic.

complete documentation of jinja: https://jinja.palletsprojects.com/en/3.0.x/templates/

### Example Inputs:
- Resource: 
- Method: 
- aplic-3-1909 # recupera o nome do projeto;
- stack-variavel@1.0.0 # recupera o nome da Stack utilizada;
- studio-usage-insights # recupera o nome do Estúdio;
- quality-assurance # recupera o nome do Workspace utilizado;
- app # recupera o tipo do manifesto (app ou infra);
- app # recupera o tipo do Plugin (app ou infra);
- plugin-var-qa # recupera o nome do Plugin;
- 1.0.0 # recupera a versão utilizada do Plugin;
- studio-usage-insights/stack-variavel@1.0.0/plugin-var-qa # recupera o Plugin qualifier (studio/stack@semantic-version/plugin@semantic-version);
- test # recupera o nome da conta utilizada.
- Flavia QA ACCOUNT HOLDER # recupera o nome de usuário.
- flavia-qa-account@test.com # recupera o email do usuário.