## Questão 1

> Cloud Kicks has the organization-wide defaults for Opportunity set to Private. Which two features should the administrator use to open up access to opportunity records for sales users working on collaborative deals? Choose 2 answers.

> O Cloud Kicks tem os padrões de toda a organização para Oportunidade definidos como Privado. Quais são os dois recursos que o administrador deve usar para abrir o acesso aos registros de oportunidades para usuários de vendas que trabalham em negócios colaborativos? Escolha 2.

A. Sharing rules

(*Use regras de compartilhamento para estender o acesso de compartilhamento a usuários em grupos, funções (é o caso dessa questão - sales users) ou territórios públicos. As regras de compartilhamento dão a usuários específicos maior acesso criando exceções automáticas às configurações de compartilhamento em toda a organização.*)

B. Sharing set 

(*Os conjuntos de compartilhamento usam perfis para fornecer acesso de registro a um grupo de usuários, diferentemente das regras de compartilhamento da letra A, que usam funções - como sales users - e grupos públicos.*)

C. Role hierarchy

(*Uma hierarquia de papéis funciona em conjunto com as Sharing set para determinar os níveis de acesso que os usuários têm aos seus dados do Salesforce*)

D. Profiles

(*Os perfis definem como os usuários acessam objetos e dados e o que eles podem fazer no aplicativo. Ao criar usuários, você atribui um perfil a cada um.*)

<details>
  <summary>Gabarito:</summary>
  A e C
</details>

___
## Questão 2
> Northern Trail Outfitters has requested that when the Referral Date field is updated on the custom object Referral Source, the parent object Referral also needs to be updated. Which automation solution should an administrator use to meet this request?

> A Northern Trail Outfitters solicitou que, quando o campo Data de referência for atualizado na Origem de referência do objeto personalizado, a referência do objeto pai também precise ser atualizada. Qual solução de automação um administrador deve usar para atender a essa solicitação?

A. Workflow Field Update

B. Lightning Web Component

C. Process Builder

D. Approval Process

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 3
> Northern has two different sales processes: one for business opportunities with four stages and one for partner opportunities with eight stages. Both processes will vary in page layouts and picklist value options. What should an administrator configure to meet these requirements?

> A Northern possui dois processos de vendas diferentes: um para oportunidades de negócios com quatro etapas e outro para oportunidades de parceiros com oito etapas. Ambos os processos variam em layouts de página e opções de valor da lista de opções. O que um administrador deve configurar para atender a esses requisitos?

A. Public groups to limit record types and sales processes for opportunities

B. Validation rules that ensure that users are entering accurate sales stage information

C. Separate record types and sales processes for the different types of opportunities

D. Diferent page layouts that control the picklist values for the opportunity types

<details>
  <summary>Gabarito:</summary>
  C (check)
</details>

___
## Questão 4
> The administrator at Cloud has been asked to replace two old workflow rules that are doing simple field updates when a lead is created to improve processing time. What tool should the administrator use to replace the workflow rules?

> O administrador da Cloud foi solicitado a substituir duas regras de fluxo de trabalho antigas que fazem atualizações de campo simples quando um lead é criado para melhorar o tempo de processamento. Qual ferramenta o administrador deve usar para substituir as regras de fluxo de trabalho?

A. Scheduled Flow

B. Quick Action Flow

C. Before Save Flow

D. Screen Flow

<details>
  <summary>Gabarito:</summary>
  C (checked)

  > **Before Save Flow:** Before Save (Fast Field Updates) Se você precisa apenas atualizar campos no registro que aciona o fluxo, esta é a opção certa. Ele pode ser acionado quando o registro é criado, criado ou atualizado, atualizado ou excluído. O fluxo antes de salvar é executado muito mais rápido (10 vezes) do que o fluxo depois de salvar.

  > **Scheduled Flow:** Um fluxo acionado por agendamento é iniciado na hora e na frequência especificadas para um lote de registros.

  > **Screen Flow:** Os fluxos de tela fornecem uma maneira de orientar os usuários por meio de um processo de negócios; eles fornecem instruções ou scripts de chamada, solicitam aos usuários que preencham determinados campos e, em seguida, executam ações nos bastidores, como Criação de Registro ou Atualização de Registro

</details>

___
## Questão 5
> An administrator has assigned a permission set group with the two-factor authentication for User Interface Logins permission and the two-factor authentication for API Logins permission to a group of users. Which two prompts will happen when one of the users attempts to log in to Data Loader? Choose 2

> Um administrador atribuiu um grupo de conjunto de permissões com autenticação de dois fatores para permissão de logins da interface do usuário e autenticação de dois fatores para permissão de logins de API a um grupo de usuários. Quais dois prompts ocorrerão quando um dos usuários tentar fazer login no Data Loader?

A. Users need to get a security token from a trusted network using Reset My Security Token

B. Users need to download and install an authenticator app on their mobile device

C. Users need to connect an authenticator app to their Salesforce account

D. Users need to enter a verification code from email or SMS, whichever has higher priority

<details>
  <summary>Gabarito:</summary>
  B e C (checked)
</details>

___
## Questão 6
> AW has six sales teams in a region. These teams always consist of the same account manager, engineer, and assistant. What should the administrator configure to make it easier for teams to collaborate with the same customer?

> AW tem seis equipes de vendas em uma região. Essas equipes sempre consistem no mesmo gerente de contas, engenheiro e assistente. O que o administrador deve configurar para facilitar a colaboração das equipes com o mesmo cliente?

A. Propose the users manually share all their accounts with their teammates

(*Proponha que os usuários compartilhem manualmente todas as suas contas com seus colegas de equipe*)

B. Enable account teams and show the users how to set up a default account team

(*Habilite equipes de contas e mostre aos usuários como configurar uma equipe de contas padrão*)

C. Create a queue for each team and assign account ownership to the queue

(*Crie uma fila para cada equipe e atribua a propriedade da conta à fila*)

D. Enable and configure standard opportunity teams with splits

(*Habilite e configure equipes de oportunidades padrão com divisões*)

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 6.2

> Sales representatives at Universal Containers need assistance from product managers when selling certain products. Product managers do not have access to opportunities, but need to gain access when they are assisting with a specific deal. How can a system administrator accomplish this?

> Os representantes de vendas da Universal Containers precisam de assistência dos gerentes de produto ao vender determinados produtos. Os gerentes de produto não têm acesso a oportunidades, mas precisam ter acesso quando estão auxiliando em um negócio específico. Como um administrador de sistema pode fazer isso?

A. Notify the product manager using opportunity update reminders.
 
B. Enable opportunity teams and allow users to add the product manager.
 
C. Use similar opportunities to show opportunities related to the product manager. 

D. Enable account teams and allow users to add the product manager.

<details>
  <summary>Gabarito:</summary>
  B (checked)
  </details>

## Questão 7
> Users at Cloud Kicks are reporting different options when updating a custom picklist on the Opportunity object based on the kind of opportunity. Where should an administrator update the option in the picklist?

> Os usuários do Cloud Kicks estão relatando diferentes opções ao atualizar uma picklist personalizada no objeto Oportunidade, com base no tipo de oportunidade. Onde um administrador deve atualizar a opção na picklist?

A. Related lookup filters

B. Record type

C. Picklist value sets

D. Fields and relationships

<details>
  <summary>Gabarito:</summary>
  B (checked)

  > Os tipos de registro do Salesforce são formas de agrupar registros em um objeto específico. Utilizando record types podemos fazer uma picklist ter diferentes opções pra um mesmo objeto.
</details>

___
## Questão 8
> At Universal, users would like to be able to share Salesforce records with other members of their team, while collaborating around general topics as well. Which are two considerations for enabling this functionality? Choose 2

> Na Universal, os usuários gostariam de poder compartilhar registros do Salesforce com outros membros de sua equipe, ao mesmo tempo em que colaboram em tópicos gerais. Quais são as duas considerações para habilitar essa funcionalidade? Escolha 2

A. An administrator needs to create a group to enable record sharing

B. Object layouts should be configured to include the groups related list

C. The Add Record action must be configured in the group publisher

D. Collaboration groups are created automatically for every department

<details>
  <summary>Gabarito:</summary>
  A e B 
</details>

___
## Questão 9
> An administrator created a record trigger flow to update contacts. How should the administrator reference the values of the active record the flow is running on? 

> Um administrador criou um fluxo de gatilho de registro para atualizar os contatos. Como o administrador deve referenciar os valores do registro ativo no qual o fluxo está sendo executado?

A. Use the Get Records element to find the Id

B. Use the {!Contact.Id} global variable

C. Use the $Record global variable

D. Use the {!Account.Id} record variable

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 10
> The administrator at DreamHouse Realty added an email quick action to the Case page layout and is unable to see the action on the case feed. Which feature must be enabled to ensure the quick action will be displayed as expected?

> O administrador da DreamHouse Realty adicionou uma ação rápida de e-mail ao layout da página do caso e não consegue ver a ação no feed do caso. Qual recurso deve ser ativado para garantir que a ação rápida seja exibida conforme o esperado?

A. Email Templates

B. Email-to-Case

C. Email Notifications

D. Email Alerts

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 11
> Sales users at Universal Containers are reporting that it is taking a long time to edit opportunity records. Normally, the only field they are editing is the Stage field. Which two options should the administrator recommend to help simplify the process? Choose 2

> Os usuários de vendas da Universal Containers estão relatando que está demorando muito para editar os registros de oportunidade. Normalmente, o único campo que eles estão editando é o campo Stage. Quais são as duas opções que o administrador deve recomendar para ajudar a simplificar o processo? Escolha 2

A. Use a Kanban list view for Opportunity

B. Add a Path for stage to the opportunity record page

C. Configure an autolaunched flow for Opportunity editing

D. Create a simplified Opportunity page layout

<details>
  <summary>Gabarito:</summary>
  A, B, C <- 2 dessas
</details>

___
## Questão 12
> Which two capabilities are considerations when marking a field as required in Object Manager? Choose 2 answers

> Quais dois recursos são considerados ao marcar um campo como necessário no Gerenciador de objetos? Escolha 2 respostas

A. The field is not required to save records via API on that object

B. The field is added to every page layout on that object

C. The field is universally required to save a record on that object

D. The field is optional when saving records via web-to-lead and web-to-case 

(*Web-to-lead: The process of using a website form to capture visitor information and store that information as a new lead in Salesforce.*)

<details>
  <summary>Gabarito:</summary>
  B e C (checked)
</details>

___
## Questão 13
> Northern Trail Outfitters is using one profile for all of its marketing users, providing read-only access to the Campaign object. A few marketing users now require comprehensive edit access on Campaigns.
How should an administrator fulfil this request?

> A Northern Trail Outfitters está usando um perfil para todos os seus usuários de marketing, fornecendo acesso somente leitura ao objeto Campanha. Alguns usuários de marketing agora exigem acesso de edição abrangente em campanhas. Como um administrador deve atender a essa solicitação?

A. Permission sets

B. Organization-wide defaults

C. Marketing user checkbox

D. Field-level security

<details>
  <summary>Gabarito:</summary>
  C (checked)

  > **Marketing user checkbox:** When enabled, the user can create, edit, and delete campaigns, configure advanced campaign setup, import leads, and update campaign history via the member import wizards.  If this option isn't selected, the user can only view campaigns and advanced campaign setup, edit the Campaign History for a single lead or contact, and run campaign reports
</details>

___
## Questão 14
> DreamHouse Realty regularly processes customer requests for warranty work and would like to offer customers a self-serve option to generate cases. Which two solutions should an administrator use to meet this request? Choose 2 answers

> A DreamHouse Realty processa regularmente as solicitações dos clientes para a garantia de trabalho e gostaria de oferecer aos clientes uma opção de autoatendimento para gerar casos. Quais duas soluções um administrador deve usar para atender a essa  solicitação? Escolha 2 respostas

A. Web-to-Case

B. Email-to-Case

C. Case Escalation

D. Case Queues

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___
## Questão 15
> An administrator has been asked to update a flow that was created as part of a recent update. When the administrator opens the flow for editing, the Flow Bunder toolbox offers only four elements: Assignment, Decision, Get Records, and Loop. What would cause this?

> Um administrador foi solicitado a atualizar um fluxo que foi criado como parte de uma atualização recente. Quando o administrador abre o fluxo para edição, a caixa de ferramentas Flow Bunder oferece apenas quatro elementos: Atribuição, Decisão, Obter Registros e Loop. O que causaria isso?

A. The version of the flow is inactive

B. The flow is a screen flow

C. The flow is a before save flow

D. The version of the flow is activate

<details>
  <summary>Gabarito:</summary>
  C (checked)

  > **Before Save Flow (Fast Field Updates)** If you just need to update fields on the record that triggers the flow, this is the right option. It can be triggered when the record is created, created or updated, updated, or deleted. Before save flow runs much faster (10 times) than the after save flow. First of all, the only thing that you can perform is to update the record that triggers the flow. As you can see, there are no options to create or delete records, or any interaction elements like calling a subflow, or performing an action (for example, sending an email).
</details>

___
## Questão 16
> The marketing team wants a new picklist value added to the Campaign Member Status field for the upsell promotional campaign. Which two solutions should the administrator use to modify the picklist field values? Choose 2 answers

> A equipe de marketing deseja que um novo valor de lista de opções seja adicionado ao campo Status do membro da campanha para a campanha promocional de upsell. Quais duas soluções o administrador deve usar para modificar os valores do campo da lista de opções? Escolha 2 respostas

A. Edit the picklist values for the Campaign Status in Object Manager 

B. Modify the picklist value on the Campaign Member Statuses related list

C. Mass modify the Campaign Member Statuses related list

D. Add the Campaign Member Statuses related list to the Page Layout

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 17
> What are three characteristics of a master-detail relationship? Choose 3 answers

A. Permissions for the detail record are set independently of the master

B. The master object can be a standard or custom object

C. Roll-up summaries are supported in master-detail relationships

D. Each object can have up to five master-detail relationships

E. The owner field on the detail records is the owner of the master record

<details>
  <summary>Gabarito:</summary>
  B, C e E (checked)

  > **Roll-up summaries:** Um campo de resumo de totalização calcula valores de registros relacionados, como os de uma lista relacionada. Você pode criar um campo de resumo de totalização para exibir um valor em um registro mestre com base nos valores dos campos em um registro de detalhes. O registro de detalhes deve estar relacionado ao mestre por meio de um relacionamento mestre-detalhe.
</details>

___
## Questão 18
> The sales manager at Cloud Kicks wants to set up a business process where opportunity discounts over 30% need to be approved by the VP of sales. Any discounts above 10% need to be approved by the user’s manager. The administrator has been tasked with creating an approval process. Which are two considerations the administrator needs to review before setting up this approval process?

> O gerente de vendas da Cloud Kicks deseja configurar um processo de negócios em que descontos de oportunidade acima de 30% precisem ser aprovados pelo vice-presidente de vendas. Quaisquer descontos acima de 10% precisam ser aprovados pelo gerente do usuário. O administrador foi encarregado de criar um processo de aprovação. Quais são as duas considerações que o administrador precisa revisar antes de configurar esse processo de aprovação?

A. Create a custom Discount field on the opportunity to capture the discount amount

B. Populate the Manager standard field on the sales users' User Detail page

(*Preencha o campo padrão Gerente na página Detalhes do usuário dos usuários de vendas*)

C. Configure two separate approval processes

D. Allow the submitter choose the approver manually

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___
## Questão 19
> AW Computing (AWC) occasionally works with independent contractors, who the company stores as Contacts in Salesforce. Contractors often change agencies, and AWC wants to maintain the historical accuracy of the record. What should AWC use to track Contacts?

> A AW Computing (AWC) trabalha ocasionalmente com contratados independentes, que a empresa armazena como Contatos no Salesforce. Os contratados geralmente mudam de agência e a AWC deseja manter a precisão histórica do registro. O que o AWC deve usar para rastrear contatos?

A. Use a partner community to track the Contacts

B. Create a new Contact record for each agency

C. Create a Junction object to track many-to-many relationship

D. Enable Contacts to multiple Accounts

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 20
> A sales rep has a list of 300 accounts with contacts that they want to load at one time. Which tool should the administrator utilize to import the records to salesforce?

> Um representante de vendas tem uma lista de 300 contas com contatos que deseja carregar de uma só vez. Qual ferramenta o administrador deve utilizar para importar os registros para o salesforce?

A. Data Loader

B. Manual Import

C. Dataloader.io

D. Data Import Wizard

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 21
> Ursa Major Solar wants to automatically notify a manager about any cases awaiting a response from an agent for more than 2 hours after case creation. Which feature should an administrator use to fulfill this requirement?

> A Ursa Major Solar deseja notificar automaticamente um gerente sobre todos os casos que aguardam uma resposta de um agente por mais de 2 horas após a criação do caso. Qual recurso um administrador deve usar para atender a esse requisito?

A. Formula Field

B. Case escalation rule

C. Assignment rule

D. Omni-Channel Supervisor

<details>
  <summary>Gabarito:</summary>
  B
</details>

___
## Questão 22
> The Client services and customer support teams share the same profile but have different permission sets. The Custom Object Retention related list needs to be restricted to the client services team on the Lightning record page layout. What should the administrator use to fulfil this request?

> As equipes de atendimento ao cliente e suporte ao cliente compartilham o mesmo perfil, mas têm conjuntos de permissões diferentes. A lista relacionada Retenção de objeto personalizado precisa ser restrita à equipe de atendimento ao cliente no layout de página de registro do Lightning. O que o administrador deve usar para atender a essa solicitação?

A. Sharing settings

B. Record type assignment

C. Page layout assignment

D. Component visibility

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 23
> An administrator has reviewed an upcoming critical update.
How should the administrator proceed with activation of the critical update?

> Um administrador revisou uma atualização crítica futura.
Como o administrador deve proceder com a ativação da atualização crítica?

A. Allow the critical update to auto-activate In a sandbox.

B. Activate the critical update in production.

C. Activate the critical update in a sandbox

D. Allow the critical update to auto-activate.

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 24
> The Sales Director at Cloud Kicks wants to be able to predict upcoming revenue in the next several fiscal quarters so they can set goals and benchmark how reps are performing. Which two features should the administrator configure?

> O Diretor de Vendas da Cloud Kicks quer ser capaz de prever a receita futura nos próximos trimestres fiscais para que possam definir metas e comparar o desempenho dos representantes. Quais dois recursos o administrador deve configurar?

A. Sales Quotes (*cotação de vendas**)

B. Opportunity List View

C. Forecasting (*previsão*)

D. Opportunity Stages

<details>
  <summary>Gabarito:</summary>
  A e C (checked)
</details>

___
## Questão 25
> The administrator for Cloud Kicks has created a screen flow to help service reps ask the same set of questions when customers call in with issues. This screen should be visible from cases. How should the screen flow be distributed?

> O administrador do Cloud Kicks criou um fluxo de tela para ajudar os representantes de serviço a fazer o mesmo conjunto de perguntas quando os clientes ligam com problemas. Esta tela deve ser visível nos casos. Como o fluxo de tela deve ser distribuído?

A. Page Layout

B. Component Filter

C. Lightning Page

D. Home page

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 26
> Cloud Kicks has decided to delete a custom field. What will happen to the data in the field when it is deleted?

A. The data in the field is stored for 20 days

B. The data is permanently deleted

C. The data associated with the field is removed

D. The data is restorable from the recycle bin

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 27
> Universal Containers requires a different Lightning page to be displayed when Accounts are viewed In the Sales Console and In the Service Console. How should meet this requirement?

> O Universal Containers exige que uma página diferente do Lightning seja exibida quando as contas são exibidas no Sales Console e no Service Console.

A. Update page layout assignments

(*Atualizar atribuições de layout de página*)

B. Define multiple record types

C. Assign Lightning pages as app default

D. Create different user profiles

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 28
> The VP of safes at Universal Containers wants to prevent members of the sales team from changing an opportunity to a date in the past. What should an administrator configure to meet this requirement?

> O vice-presidente de cofres da Universal Containers quer impedir que os membros da equipe de vendas alterem uma oportunidade para uma data no passado. O que um administrador deve configurar para atender a esse requisito?

A. Assignment Rule

B. Approval Process

C. Field-Level Security

D. Validation Rule

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 29
> What should a system administrator use to disable an application for a group of users in Salesforce?

A. Profile

B. Sharing rules

C. Web tabs

D. Page layouts

<details>
  <summary>Gabarito:</summary>
  A (checked)

  > Sharing rules: acess ADICIONAL

  > Web tabs: guias que dão acesso a certas funcionalidades da web 

  > Page layout: Controla o layout da página ou como a página aparece, mas isso não é usado para desabilitar acesso ao app personalizado
</details>

___
## Questão 30

> Universal Containers needs to track the Manufacturer and Model for specific car companies. How can the system administrator ensure that the selected Manufacturer provides the values available for the Model? 

> A Universal Containers precisa rastrear o fabricante e o modelo para empresas de automóveis específicas. Como o administrador do sistema pode garantir que o Fabricante selecionado forneça os valores disponíveis para o Modelo?

A. Create the Manufacturer field as a dependent picklist and the Model as a controlling picklist.

B. Create a lookup field from the Manufacturer object to the Model object. 

C. Create the Manufacturer field as a controlling picklist and the Model as a dependent picklist. 

D. Create a multi-select picklist field that includes both Manufacturers and Models.

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 31
> In order to gather better data, Universal Containers would like to gather data around their Closed Lost opportunities. They want to ensure that when an opportunity stage is Closed Lost the reason is captured in a custom ‘Reason Lost’ field before the record can be saved. What is the best approach to meet this requirement?

A. Create a workflow rule that fires on the Closed Lost state and populates the Reason Lost field with a predefined value.

B. Create a trigger that requires Reason Lost to the populated once the opportunity stage is changed to Closed Lost.

C. Create a new page layout for Closed Lost opportunities and make Reason Lost a required field.

D. Create a validation rule that requires Reason Lost to be populated once the opportunity stage is Closed Lost.

<details>
  <summary>Gabarito:</summary>
  D (checked)

Observando as 4 respostas fornecidas, você pode resolver o problema com várias delas. Mas das 4, há claramente uma única melhor resposta. Você pode escrever uma trigger para manipular coisas ou criar um layout de página separado com esse campo obrigatório e, em seguida, usar alguma automação para alterar o tipo de registro.

Mas o que a pergunta quer é realmente uma prática recomendada. Por que você usaria qualquer uma das outras, quando uma regra de validação (D) é uma funcionalidade padrão que pode atender aos requisitos facilmente?
</details>

___
## Questão 32

> Universal Containers was bought by a larger company and needs to provide information on a monthly basis to the new parent company to help predict sales. Which data should the new parent company review? Choose one answer

> A Universal Containers foi comprada por uma empresa maior e precisa fornecer informações mensalmente à nova controladora para ajudar a prever as vendas. Quais dados a nova empresa-mãe deve revisar? Escolha uma resposta

A. Dashboard of user login history 

B. Count of new lead records created 

C. Number of activities tied to opportunities 

D. Opportunity pipeline report grouped by month

<details>
  <summary>Gabarito:</summary>
  D (checked)

  Esta pergunta não pergunta sobre recursos da plataforma ou práticas recomendadas. Ele quer que você entenda o que seria benéfico para a empresa. Você pode criar relatórios ou painéis para qualquer um deles, mas do que uma empresa se beneficiaria mais? A questão é sobre 'prever vendas', então sabemos que é em torno de dados de leads ou oportunidades (o que elimina A). Embora a contagem de leads possa prever as vendas, seria menos benéfica do que os dados de oportunidade (eliminando B). C são atividades sobre oportunidades que mostram um nível de engajamento, mas não prevêem vendas. D é o pipeline de oportunidades, que daria às partes interessadas a melhor visão.
  </details>

  ___
  # Questão 33

  > What should a system administrator consider before importing a set of records into Salesforce? (There are two correct answers.) 

A. The import file should include a record owner for each record.
 
B. Currency field values will default to the personal currency of the record owner.

(*Os valores do campo de moeda serão padronizados para a moeda pessoal do proprietário do registro.*)
 
C. Data should be de-duplicated in the import file prior to import.

(*Os dados devem ser desduplicados no arquivo de importação antes da importação.*)
 
D. Validation rules are not triggered when importing data using the import wizard.

(*As regras de validação não são acionadas ao importar dados usando o assistente de importação.*)

<details>
  <summary>Gabarito:</summary>
  A e C (checked)

  A razão pela qual A é importante é que, a menos que um Proprietário seja especificado, o Usuário do Salesforce que fizer a importação se tornará o Proprietário de todos os registros importados. Isso significaria que o administrador teria que fazer outro trabalho de dados ou usar a ferramenta de transferência em massa para alterar os proprietários após a criação dos registros. Isso será muito mais difícil do que definir o Proprietário antes da importação.
 
A : If record owner is not specified, then uploader becomes the owner of the record itself.
 
B: The uploading user's currency will be taken instead of org's currency.
 
C: Duplicate records are allowed and no errors are reported. Hence this should be considered.
 
D: Validations, Workflow & triggers will be fired unless manually disabled.
</details>