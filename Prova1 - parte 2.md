## Questão 21

> Sales users at Cloud Kicks are requesting that the data in the Industry field on the Account object displays on the Opportunity page layout. Which type of field should an administrator create to accomplish this?

> Os usuários de vendas do Cloud Kicks estão solicitando que os dados no campo Setor no objeto Conta sejam exibidos no layout da página Oportunidade. Que tipo de campo um administrador deve criar para fazer isso?

A. Cross-object formula field (*Campo de fórmula de objeto cruzado*)

B. Master-detail relationship field (*Campo de relacionamento mestre-detalhe*)

C. Custom Account field (*Campo de conta personalizada*)

D. Standard Account field (*Campo de conta padrão*)

<details>
  <summary>Gabarito:</summary>
  A (checked)

  CROSS-OBJECT FORMULA FIELD 


  Uma fórmula de objeto cruzado é uma fórmula que abrange dois objetos relacionados e faz referência a campos de mesclagem nesses objetos. Uma fórmula de objeto cruzado pode fazer referência a campos de mesclagem de um objeto mestre ("pai") se um objeto estiver no lado de detalhes de um relacionamento entre mestre e detalhes.


  MASTER-DETAIL RELATIONSHIP FIELD X LOOKUP FIELD


 Lookup field relationship:

Até 25 permitidos para o objeto
Pai não é um campo obrigatório.
Nenhum impacto em uma segurança e acesso.
Nenhum impacto na exclusão.
Pode ter várias camadas de profundidade.
O campo de pesquisa não é obrigatório.

 Master-detail relationship:

O relacionamento Master Detail é o relacionamento Pai-filho. Em que o Mestre representa o Pai e o detalhe representa o Filho. Se o Pai for excluído, o Filho também será excluído. Os campos de resumo de rollup só podem ser criados em registros mestre que calcularão a SUM, AVG, MIN dos registros filho.
Até 2 permitidos para objetar.
O campo pai no filho é obrigatório.
O acesso ao pai determina o acesso aos filhos.
A exclusão do pai exclui automaticamente o filho.
Um filho de um relacionamento de detalhes mestre não pode ser pai de outro.
O campo de pesquisa no layout da página é obrigatório.
</details>

___

## Questão 22

> Once an opportunity reaches the negotiation stage at Cloud Kicks, the Amount field becomes required for sales users. Sales managers need to be able to move opportunities into this stage without knowing the amount. How should the administrator require this field during the negotiation stage for sales users but allow their managers to make changes?

> Quando uma oportunidade atinge o estágio de negociação no Cloud Kicks, o campo Valor se torna obrigatório para os usuários de vendas. Os gerentes de vendas precisam ser capazes de mover as oportunidades para esse estágio sem saber o valor. Como o administrador deve exigir esse campo durante a fase de negociação para usuários de vendas, mas permitir que seus gerentes façam alterações?

A. Assign the Administrator profile to the managers

(*Assign the Administrator profile to the managers*)

B. Create a formula field to fill in the field for managers

(*Criar um campo de fórmula para preencher o campo para gerentes*)

C. Make the field required for all users

(*Tornar o campo obrigatório para todos os usuários*)

D. Configure a validation rule to meet the criteria

(*Configure uma regra de validação para atender aos critérios*)

<details>
  <summary>Gabarito:</summary>
  D
</details>

___
## Questão 23

> The sales team at Ursa Major Solar has asked the administrator to automate an outbound message. What should the administrator utilize to satisfy the request?

> A equipe de vendas da Ursa Major Solar pediu ao administrador para automatizar uma mensagem de saída. O que o administrador deve utilizar para satisfazer a solicitação?

A. Task Assignment (Atribuição de tarefa)

B. Flow Builder

C. Process Builder

D. Workflow Rule

<details>
  <summary>Gabarito:</summary>
  D.

  Workflow Rule
- É o contêiner principal de um conjunto de instruções de fluxo de trabalho, que pode ser dividido em dois componentes principais.

- Critérios: o que deve ser verdade do registro para que a regra de fluxo de trabalho execute as ações associadas. Os critérios de uma regra de fluxo de trabalho estão sempre vinculados a um objeto.
- Ações: o que fazer quando o registro atende aos critérios.


Flow Builder
- Um flow é um aplicativo que automatiza um processo de negócios coletando dados e fazendo algo em sua organização do Salesforce ou em um sistema externo. **Ao contrário das regras de fluxo de trabalho, que sempre são executadas nos bastidores, os fluxos podem fornecer telas para orientar os usuários pelo processo de negócios.
Os fluxos não estão vinculados a nenhum objeto. Eles podem pesquisar, criar, atualizar e excluir registros de vários objetos. Você cria fluxos usando o Flow Builder, que é uma ferramenta de apontar e clicar.**
</details>

___
## Questão 24
> Users have noticed that when they click on a report in a dashboard to view the report details, the values in the report are different from the values displayed on the dashboard. What are the two reasons this is likely to occur? Choose 2

> Os usuários notaram que, quando clicam em um relatório em um painel para visualizar os detalhes do relatório, os valores no relatório são diferentes dos valores exibidos no painel. Quais são as duas razões pelas quais é provável que isso ocorra? Escolha 2

A. The running dashboard user and viewer have different permissions

B. The current user does not have access to the report folder

C. The dashboard needs to be refreshed

D. The report needs to be refreshed

<details>
  <summary>Gabarito:</summary>
  A e C (checked)
</details>

___
## Questão 25

> An administrator at DreamHouse Realty wants an easier way to assign cases based on agent capacity and skill set. Which feature should the administrator enable to meet this requirement?

> Um administrador da DreamHouse Realty deseja uma maneira mais fácil de atribuir casos com base na capacidade e no conjunto de habilidades do agente. Qual recurso o administrador deve habilitar para atender a esse requisito?

A. Escalation Rules (*Regra de escalação*)

B. Knowledge Management (*ferramenta de suporte final. Crie e gerencie uma base de conhecimento com as informações da sua empresa e compartilhe com segurança quando e onde for necessário. A base de conhecimento do Salesforce é desenvolvida a partir de artigos do Knowledge, que são documentos informativos. Os artigos podem incluir informações sobre processos – por exemplo, como redefinir o produto para os valores padrão — ou perguntas frequentes, como a quantidade de armazenamento que seu produto suporta.*)

C. Territory Management (*Gerenciamento de território corporativo do Salesforce dá aos vendedores acesso aos clientes com base no código postal, setor, receita ou um parâmetro personalizado. Com territórios de vendas, fica fácil rastrear os representantes que estão atribuídos a determinadas contas e oportunidades. Se você gerenciar os territórios com eficiência, alocará recursos também com eficiência e aumentará a probabilidade de maximizar vendas e lucros.*)

D. Omni-Channel (*Use o Omni-Channel para gerenciar a prioridade dos itens de trabalho, o que facilita o roteamento rápido de itens de trabalho importantes para os agentes. Distribui trabalhos para agentes em tempo real, diretamente do Console do Salesforce. O Omni-Channel possibilita tudo isso usando objetos, que são apenas uma palavra especial para qualquer coisa que possa ser direcionada para seus agentes. Casos, bate-papos, leads e postagens sociais são exemplos de objetos.*)

<details>
  <summary>Gabarito:</summary>
  D.

**Como funciona a solução Omni-Channel do Salesforce**

  | Recursos  |  Definição | 
|---|---|
| Presença  |Os agentes definem sua disponibilidade aqui para receberem os casos certos quando disponíveis.   |  
| Roteamento  | Os agentes recebem casos via um modelo de push, que atribui trabalho de vários canais. As empresas podem rotear casos com base em: Prioridade mais alta, Itens mais antigos primeiro, Disponibilidade de um agente, Capacidade do agente  |  
|  Supervisor |  Gerentes de atendimento veem e gerenciam dados relacionados às suas prioridades comerciais. Rastreiam dados como: Tempo de espera, Casos abertos, Quem está trabalhando em quê, Quem tem capacidade para mais casos | 
</details>

___
## Questão 26

> Northern Trail Outfitters wants to know the average stage duration for all closed opportunities. How should an administrator support this request?

> A Northern Trail Outfitters quer saber a duração média da etapa para todas as oportunidades fechadas. Como um administrador deve dar suporte a essa solicitação?

A. Run the Opportunity Stage Duration report

(*Executar o relatório de duração do estágio da oportunidade*)

B. Refresh weekly reporting shapshots for Closed Opportunities

(*Atualize os shapshots de relatórios semanais para oportunidades fechadas*)

C. Use Process Builder to capture the daily average on each Opportunity

(*Use o Process Builder para capturar a média diária em cada oportunidade*)

D. Add formula fields to track Stages on each Opportunity

(*Adicione campos de fórmula para rastrear estágios em cada oportunidade*)

<details>
  <summary>Gabarito:</summary>
  A.
</details>

___
## Questão 27

> Universal Containers is trying to improve the user experience when searching for the right status on a case. The company currently has one support process that is used for all record types on cases. The support process has 10 status values. Service reps say they never need more than five depending on what kind of case they are working on. How should the administrator improve on the current implementation?

> A Universal Containers está tentando melhorar a experiência do usuário ao pesquisar o status correto em um caso. Atualmente, a empresa possui um processo de suporte que é usado para todos os tipos de registro em casos. O processo de suporte tem 10 valores de status. Os representantes de serviço dizem que nunca precisam de mais de cinco, dependendo do tipo de caso em que estão trabalhando. Como o administrador deve melhorar a implementação atual?

A. Edit the status choices directly on the record type

(*Edite as opções de status diretamente no tipo de registro*)

B. Review which status choices are needed for each record type and create support processes for each that is necessary

(*Revise quais opções de status são necessárias para cada tipo de registro e crie processos de suporte para cada um que for necessário*)

C. Create a Screen Flow that shows only the correct values for status and surface the flow in the utility bar of the console

(*Crie um fluxo de tela que mostre apenas os valores corretos para status e exiba o fluxo na barra de utilitários do console*)

D. Reduce the number of case status values to five

(*Reduza o número de valores de status do caso para cinco*)

<details>
  <summary>Gabarito:</summary>
  B.
</details>

___
## Questão 28

> DreamHouse Realty (DHR) wants a templated process with a mortgage calculator that generates leads for loans. DHR needs to complete the project within 30 days and has maxed out its budget for the year. Which AppExchange item should help the administrator meet the request?

> A DreamHouse Realty (DHR) quer um modelo de processo com uma calculadora de hipoteca que gere leads para empréstimos. O DHR precisa concluir o projeto em 30 dias e atingiu seu orçamento para o ano. Qual item do AppExchange deve ajudar o administrador a atender à solicitação?

A. Bolt Solutions 

(*É um pacote, pode combinar aplicativos Lightning personalizados, fluxos de processos de negócios e modelos e páginas do Experience Builder de forma fácil de construir e distribuível.*)

B. Lightning Community 

(*Os modelos de comunidade do Lightning permitem que você crie espaços de marca onde seus funcionários, clientes e parceiros podem se conectar. Construídos na estrutura de componentes do Lightning, os modelos do Lightning incluem muitos recursos e componentes do Lightning prontos para uso.*)

C. Flow Solutions 

(*Amplie o poder da automação de processos sem código do Lightning Flow com soluções de fluxo. Faça download de processos de negócios pré-criados configuráveis com modelos de fluxo e instale blocos de construção autônomos com ações de fluxo.*)

D. Lightning Data 

(*O Lightning Data Service é uma estrutura de cache de dados centralizada usada para carregar, salvar, criar e excluir um registro sem código apex do lado do servidor. Ele também suporta as regras de compartilhamento e a segurança em nível de campo.*)

<details>
  <summary>Gabarito:</summary>
  C.
</details>

___
## Questão 29

> Cloud Kicks has the organization-wide defaults for Opportunity set to Private. Which two features should the administrator use to open up access to opportunity records for sales users working on collaborative deals? Choose 2 answers.

> O Cloud Kicks tem os padrões de toda a organização para Oportunidade definidos como Privado. Quais são os dois recursos que o administrador deve usar para abrir o acesso aos registros de oportunidades para usuários de vendas que trabalham em negócios colaborativos? Escolha 2.

A. Sharing rules

(*Use regras de compartilhamento para estender o acesso de compartilhamento a usuários em grupos, funções ou territórios públicos. As regras de compartilhamento dão a usuários específicos maior acesso criando exceções automáticas às configurações de compartilhamento em toda a organização.*)

B. Sharing set 

(*Os conjuntos de compartilhamento usam perfis para fornecer acesso de registro a um grupo de usuários, diferentemente das regras de compartilhamento da letra A, que usam funções e grupos públicos.*)

C. Role hierarchy

(*Uma hierarquia de papéis funciona em conjunto com as Sharing set para determinar os níveis de acesso que os usuários têm aos seus dados do Salesforce*)

D. Profiles

(*Os perfis definem como os usuários acessam objetos e dados e o que eles podem fazer no aplicativo. Ao criar usuários, você atribui um perfil a cada um.*)

<details>
  <summary>Gabarito:</summary>
  A e C (check)
</details>

___
## Questão 30

> The Sales manager at DreamHouse Realty wants the sales users to have a quick way to view and edit the Opportunities in their pipeline expected to close in the next 90 days. What should an administrator do to accomplish this request?

> O gerente de vendas da DreamHouse Realty quer que os usuários de vendas tenham uma maneira rápida de visualizar e editar as oportunidades em seu pipeline que devem ser fechadas nos próximos 90 dias. O que um administrador deve fazer para atender a essa solicitação?

A. Create a custom report and schedule the sales users to receive it each day as a reminder to update their opportunities

(*Crie um relatório personalizado e programe os usuários de vendas para recebê-lo todos os dias como um lembrete para atualizar suas oportunidades*)

B. Create a list view on the Opportunity object and recommend users switch the view to Kanban to edit by drag and drop

(*Crie uma exibição de lista no objeto Oportunidade e recomende que os usuários alternem a exibição para Kanban para editar arrastando e soltando*)

C. Enable Sales Console and show users how to open a tab for each opportunity in the pipeline that meets the requirements

(*Ative o Sales Console e mostre aos usuários como abrir uma guia para cada oportunidade no pipeline que atenda aos requisitos*)

D. Make a new Sales dashboard and add a component that shows all opportunities that meet the criteria

(*Crie um novo painel de vendas e adicione um componente que mostre todas as oportunidades que atendem aos critérios*)

<details>
  <summary>Gabarito:</summary>
  B.
</details>

___
## Questão 31
> Ursa Solar Major is evaluating Salesforce for its service team and would like to know what objects were available out of the box. Which three of the standard objects are available to an administrator considering a support use case? Choose 3 answers.

> A Ursa Solar Major está avaliando o Salesforce para sua equipe de serviço e gostaria de saber quais objetos estavam disponíveis imediatamente. Quais dos três objetos padrão estão disponíveis para um administrador considerando um caso de uso de suporte? Escolha 3 respostas.

A. Request

B. Account

C. Contract

D. Case

E. Ticket

<details>
  <summary>Gabarito:</summary>
  B, C, D
</details>

___
## Questão 32
> The administrator for AW Computing is working with a user who is having trouble logging in to Salesforce. What should the administrator do to identify why the use is unable to log in?

> O administrador da AW Computing está trabalhando com um usuário que está tendo problemas para fazer login no Salesforce. O que o administrador deve fazer para identificar por que o usuário não consegue fazer login?

A. Pull the password history to ensure the password policy was followed

(*Puxe o histórico de senhas para garantir que a política de senhas foi seguida*)

B. Reset the security token for the profile

(*Redefinir o token de segurança para o perfil*)

C. Check the attempted logins by running the setup audit trail

(*Verifique as tentativas de login executando a trilha de auditoria de configuração*)

D. Review the login history for the user

(*Revise o histórico de login do usuário*)

<details>
  <summary>Gabarito:</summary>
  B
</details>

___
## Questão 33
> Universal Containers wants to prevent its service team from accessing deal records. While service users are unable to access deal list views, they are able to find deal records via a search. What option should the administrator adjust to fully rescrict access?

> A Universal Containers quer impedir que sua equipe de serviço acesse os registros de negócios. Embora os usuários do serviço não consigam acessar as visualizações da lista de negócios, eles podem encontrar registros de negócios por meio de uma pesquisa. Qual opção o administrador deve ajustar para restringir totalmente o acesso?

A. Record settings and search index

(*Configurações de registro e índice de pesquisa*)

B. Page layouts and field-level security

(*Layouts de página e segurança em nível de campo*)

C. Permissions and tab visibility

(*Permissões e visibilidade da guia*)

D. App permissions and search terms

(*Permissões de aplicativos e termos de pesquisa*)

<details>
  <summary>Gabarito:</summary>
  B.
</details>

___
## Questão 34
> Cloud Kicks intends to protect data with backups by using the data export service. Which two considerations should the administrator remember when scheduling the export? Choose 2 

> Cloud Kicks pretende proteger os dados com backups usando o serviço de exportação de dados. Quais são as duas considerações que o administrador deve se lembrar ao programar a exportação? Escolha 2

A. Data export service should be run from a sandbox

(*O serviço de exportação de dados deve ser executado a partir de um sandbox*)

B. Metadata backups must be run via a separate process

(*Os backups de metadados devem ser executados por meio de um processo separado*)

C. Metadata backups are limited to sandbox refresh intervals

(*Os backups de metadados são limitados a intervalos de atualização de sandbox*)

D. Data backups are limited to weekly or monthly intervals

(*Os backups de dados são limitados a intervalos semanais ou mensais*)

<details>
  <summary>Gabarito:</summary>
  C e D.
</details>

___
## Questão 35
> An administrator is planning to use Data Loader to mass import new records to a custom object from a new API. What will the administrator need to do to use the Data Loader?

> Um administrador está planejando usar o Data Loader para importar em massa novos registros para um objeto personalizado de uma nova API. O que o administrador precisará fazer para usar o Data Loader?

A. Append their security token at the end of their password to login

(*Acrescente o token de segurança no final da senha para fazer login*)

B. Use the Data Import Tool to mass import custom object records

(*Use a Ferramenta de importação de dados para importar em massa registros de objetos personalizados*)

C. Reset their password and their security token

(*Redefinir a senha e o token de segurança*

D. Add a permission set that allows them to import data

(*Adicione um conjunto de permissões que permita importar dados*)

<details>
  <summary>Gabarito:</summary>
  C.
</details>

___
## Questão 36

> An administrator wants to create a form in Salesforce for users to fill out when they lose a client. Which automation tool supports creating a wizard to accomplish this goal?

Um administrador deseja criar um formulário no Salesforce para os usuários preencherem quando perderem um cliente. Qual ferramenta de automação oferece suporte à criação de um assistente para atingir esse objetivo?

A. Outbound Message (Mensagem de saída)

B. Flow Builder

C. Approval Process

D. Process Builder

<details>
  <summary>Gabarito:</summary>
  B
</details>

___
## Questão 37

> An administrator at Cloud Kicks has a flow in production that is supposed to create new records. However, no new records are being created. What could the issue be?

> Um administrador da Cloud Kicks tem um fluxo em produção que deve criar novos registros. No entanto, nenhum novo registro está sendo criado. Qual poderia ser o problema?

A. The flow is inactive

B. The flow trigger is missing

C. The flow url is desactivated

D. The flow is read only

<details>
  <summary>Gabarito:</summary>
  A
</details>

___
## Questão 38

> Northern Trail Outfitters has hired interns to enter Leads into Salesforce and has requested a way to identify these new records from existing Leads. What approach should an administrator take to meet this requirement?

> A Northern Trail Outfitters contratou estagiários para inserir leads no Salesforce e solicitou uma maneira de identificar esses novos registros de leads existentes. Que abordagem um administrador deve adotar para atender a esse requisito?

A. Set up Web-to-Lead for the interns use 

(*Configure o Web-to-Lead para uso dos estagiários*)

B. Define a record type and assign it to the interns

(*Definir um tipo de registro e atribuí-lo aos estagiários*)

C. Update the active Lead Assignment Rules

(*Atualizar as Regras de Atribuição de Leads ativas*)

D. Create a separate Lead Lightning App

(*Criar um aplicativo Lead Lightning separado*)

<details>
  <summary>Gabarito:</summary>
  B
</details>

___
## Questão 39

> An administrator gets a request from Human Resources to remove a user's access to Salesforce immediately. The user is a part of a hierarchy field called Direct Manager. What should the administrator do to fulfill the request?

> Um administrador recebe uma solicitação do Recursos Humanos para remover o acesso de um usuário ao Salesforce imediatamente. O usuário faz parte de um campo de hierarquia chamado Direct Manager. O que o administrador deve fazer para atender a solicitação?

A. Freeze the user to prevent them from logging in while removing them from being referenced in the Direct Manager field.

(*Congele o usuário para impedir que ele efetue login ao removê-lo de ser referenciado no campo Direct Manager.*)

B. Deactivate the user and delete any records where they are referenced in the Direct Manager field.

(*Desative o usuário e exclua todos os registros onde eles são referenciados no campo Direct Manager.*)

C. Remove the user from the allowlist on the restricted user email domain on the user's email field.

(*Remova o usuário da lista de permissões no domínio de e-mail do usuário restrito no campo de e-mail do usuário.*)

D. Restrict the user's profile to read-only while removing them from being referenced in the Direct Manager field.

(*Restrinja o perfil do usuário a somente leitura ao removê-los de serem referenciados no campo Direct Manager.*)

<details>
  <summary>Gabarito:</summary>
  A
</details>

___
## Questão 40

> An administrator has been asked to change the data type of an auto number to a text field. What should the administrator be aware of before changing the field?

> Um administrador foi solicitado a alterar o tipo de dados de um número automático para um campo de texto. O que o administrador deve estar ciente antes de alterar o campo?

A. Existing field values will be deleted

B. Existing Auto Number field to Text is prevented 

(*O campo de numeração automática existente para texto é impedido de ser trocado*)

C. Existing field values will remain unchanged

(*Os valores de campo existentes permanecerão inalterados*)

D. Existing field values will be converted

<details>
  <summary>Gabarito:</summary>
  C
</details>

___
## Questão 41

> The administrator has been asked to automate a simple field update on the account. When a support agent changes the status of the account to 'Audited', they would like the system to automatically update the Audited Date field on the account with today's date. Which tool should the administrator use to complete this automation?

> O administrador foi solicitado a automatizar uma atualização de campo simples na conta. Quando um agente de suporte altera o status da conta para 'Auditado', ele deseja que o sistema atualize automaticamente o campo Data da auditoria na conta com a data de hoje. Qual ferramenta o administrador deve usar para concluir essa automação?

A. Formula Field

B. Validation Rule

C. Approval Process

D. Flow Builder

<details>
  <summary>Gabarito:</summary>
  D
</details>

___
## Questão 42

> Ursa Major Solar offers amazing experiences for all of its employees. The employee engagement committee wants to post updates while restricting other employees from posting. What should the administrator create to meet this request?

> A Ursa Major Solar oferece experiências incríveis para todos os seus colaboradores. O comitê de engajamento de funcionários deseja publicar atualizações enquanto restringe a publicação de outros funcionários. O que o administrador deve criar para atender a essa solicitação?

A. Chatter Stream (Fluxo do Chatter)

B. Chatter Recommendations (Chatter Recommendations)

C. Chatter Broadcast Group (Grupo de transmissão do Chatter)

D. Chatter Unlisted Group (Grupo não listado do Chatter)

<details>
  <summary>Gabarito:</summary>
  C
</details>

___
## Questão 43
> The VP of sales at Cloud Kicks is receiving an error message that prevents them from saving an opportunity. The administrator attempted the same edit without receiving an error. How can the administrator validate the error the user is receiving?

> O vice-presidente de vendas da Cloud Kicks está recebendo uma mensagem de erro que o impede de salvar uma oportunidade. O administrador tentou a mesma edição sem receber um erro. Como o administrador pode validar o erro que o usuário está recebendo?

A. View the setup audit trail

(*Veja a trilha de auditoria de configuração*)

B. Review the sharing model

(*Revise o modelo de compartilhamento*)

C. Log in as the user

(*Faça login como o usuário*)

D. Edit the page layout

(*Editar o layout da página*)

<details>
  <summary>Gabarito:</summary>
  C
</details>

___
## Questão 44
> Cloud Kicks wants to update a screen flow so that if the checkbox field High Value Costumer is set to true, the first screen is skipped and the user is directed to the second screen. How should the administrator configure the decision element?

> O Cloud Kicks deseja atualizar um fluxo de tela para que, se o campo de caixa de seleção Cliente de alto valor estiver definido como verdadeiro, a primeira tela seja ignorada e o usuário seja direcionado para a segunda tela. Como o administrador deve configurar o elemento de decisão?

A. Use the contains operator and {!$GlobalConstant.False} as the value

B. Use the contains operator and "High Value Customer" as the value

C.Use the contains operator and {!$GlobalConstant.True} as the value

D. Use the equals operator and "High Value Customer" as the value

<details>
  <summary>Gabarito:</summary>
  C
</details>

___
## Questão 45

> The support manager at Cloud Kicks wants to respond to customers as quickly as possible. They have requested that the response include the top five troubleshooting tips that could help solve the customer's issue. What should the administrator suggest to meet these requirements?

> O gerente de suporte da Cloud Kicks quer responder aos clientes o mais rápido possível. Eles solicitaram que a resposta incluísse as cinco principais dicas de solução de problemas que poderiam ajudar a resolver o problema do cliente. O que o administrador deve sugerir para atender a esses requisitos?

A. Assignment Rules

B. Knowledge Articles

C. Email Alerts

D. Auto-Response Rules

<details>
  <summary>Gabarito:</summary>
  D
</details>

