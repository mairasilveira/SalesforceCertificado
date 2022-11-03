## Questão 1

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 2
> Which tool should an administrator use to identify and fix potential session vulnerabilities?

> Qual ferramenta um administrador deve usar para identificar e corrigir possíveis vulnerabilidades de sessão?

A. Field History Tracking 

(*O histórico do campo respeita as permissões do usuário atual e não registra as alterações que ocorrem no contexto do sistema. O Salesforce tenta rastrear todas as alterações em um campo rastreado pelo histórico, mesmo que uma alteração específica nunca seja armazenada no banco de dados.*)

B. Security Health Check

C. Organization-Wide Defaults

(*Padrões de toda a organização*)

D. Setup Audit Trail

(*Configurar trilha de auditoria*)

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 3
> Northern Trail Outfitters wants to calculate how much revenue has been generated for each of its marketing campaigns. How should an administrator deliver this information?

> A Northern Trail Outfitters deseja calcular quanta receita foi gerada para cada uma de suas campanhas de marketing. Como um administrador deve entregar essas informações?

A. Perform periodic data jobs to update campaign records

(*Execute trabalhos de dados periódicos para atualizar os registros da campanha*)

B. Create a roll-up summary field on Opportunity to Campaign

(*Crie um campo de resumo de totalização em Oportunidade para campanha*)

C. Add a Total Value field on Campaign and use a workflow rule to update the value when an opportunity is won

(*Adicione um campo Valor total na campanha e use uma regra de fluxo de trabalho para atualizar o valor quando uma oportunidade for ganha*)

D. Design a standard Campaign report and add the Value Won Opportunities in Campaign field

(*Crie um relatório de campanha padrão e adicione o campo Value Won Opportunities in Campaign*)

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 4
> What should an administrator use as an identifier when importing and updating records from a separate financial system?

> O que um administrador deve usar como identificador ao importar e atualizar registros de um sistema financeiro separado?

A. Rich Text field

B. Record ID

C. Auto-Number field (*Campo de numeração automática*)

D. External ID

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 5
> An administrator at Cloud Kicks wants to deactivate a user who has left the company. What are two reasons that would prevent a user from being deactivated? Choose 2 answers

> Um administrador da Cloud Kicks deseja desativar um usuário que deixou a empresa. Quais são os dois motivos que impediriam um usuário de ser desativado?

A. The user is the highest role in the role hierarchy

(*O usuário é o papel mais alto na hierarquia de papéis*)

B. The user is assigned in a workflow email alert

(*O usuário é atribuído em um alerta de e-mail de fluxo de trabalho*)

C. The user is in a custom hierarchy field

(*O usuário está em um campo de hierarquia personalizado*)

D. The user is part of a territory hierarchy

(*O usuário faz parte de uma hierarquia de territórios*)

<details>
  <summary>Gabarito:</summary>
  B e C (checked)
</details>

___
## Questão 6
> The Sales manager at DreamHouse Realty wants the sales users to have a quick way to view and edit the Opportunities in their pipeline expected to close in the next 90 days. What should an administrator do to accomplish this request?

> O gerente de vendas da DreamHouse Realty quer que os usuários de vendas tenham uma maneira rápida de visualizar e editar as oportunidades em seu pipeline que devem ser fechadas nos próximos 90 dias. O que um administrador deve fazer para atender a essa solicitação?

A. Create a custom report and schedule the sales users to receive it each day as a reminder to update their opportunities

B. Enable Sales Console and show users how to open a tab for each opportunity in the pipeline that meets the requirements

C. Create a list view on the Opportunitiy object and recommend users switch the view to Kanban to edit by drag and drop

D. Make a new Sales dashboard and add a component that shows all opportunities that meet the criteria

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 7
> Cloud Kicks wants to track shoe design by products. Shoe design should be unable to be deleted, and there can be multiple designs for one product across various stages. Which two steps should the administrator configure to meet this requirement? Choose 2 answers

> A Cloud Kicks quer rastrear o design de calçados por produtos. O design do sapato não pode ser excluído e pode haver vários designs para um produto em vários estágios. Quais são as duas etapas que o administrador deve configurar para atender a esse requisito? Escolha 2 respostas

A. Add a custom master-detail field for shoe designs on the Product object

(*Adicione um campo de detalhes mestre personalizado para designs de calçados no objeto Produto*)

B. Create a custom object for shoe designs

(*Crie um objeto personalizado para designs de sapatos*)

C. Use the standard object for designs

(*Use o objeto padrão para designs*)

D. Configure a custom lookup field for shoe designs on the Product object

(*Configure um campo de pesquisa personalizado para designs de calçados no objeto Product*)

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___
## Questão 8
> AW Computing would like to improve its Case Lightning record page by including:
>> A filtered component to display a message in bold font when a Case is saved as a critical record type
>>> A quick way to update the Account status from the Case layout
Which two components should an administrator use to satisfy these requests?
Choose 2 answers

> A AW Computing gostaria de melhorar sua página de registro Case Lightning incluindo:
>> Um componente filtrado para exibir uma mensagem em negrito quando um Caso é salvo como um tipo de registro crítico
>>>Uma maneira rápida de atualizar o status da conta no layout do caso
Quais dois componentes um administrador deve usar para atender a essas solicitações?
Escolha 2 respostas

A. Related list

B. Related record

C. Record detail

D. Rich text

<details>
  <summary>Gabarito:</summary>
  B e D (checked)

  Related list: mostra uma lista de registros relacionados com base em um objeto específico. Por exemplo, se você estiver visualizando uma página de detalhes de contato, poderá especificar para ver os casos relacionados a esse contato.

  Related record: The Related Record List component shows, in a list, a single type of record related to a record. For example, if you're looking at an account, you can see a related list of contacts for that account.

  Rich text: Os campos rich text do artigo de conhecimento fornecem funções adicionais, como a capacidade de exibir e editar o HTML de origem, suporte para mais estilos HTML e links inteligentes entre artigos. Com um editor de rich text, você pode editar ou adicionar conteúdo, tabelas, links, imagens e outros componentes da Web em uma página da Web sem escrever uma única linha de código
</details>

___
## Questão 9
> Ursa Major Solar offers amazing experiences for all of its employees. The employee engagement committee to post updates while restricting other employees from posting. What should the administrator create to meet this request?

> A Ursa Major Solar oferece experiências incríveis para todos os seus colaboradores. O comitê de engajamento de funcionários para postar atualizações enquanto restringe outros funcionários de postar. O que o administrador deve criar para atender a essa solicitação?

A. Chatter Broadcast Group

B. Chatter Recommendations

C. Chatter Unlisted Group

D. Chatter Stream

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 10
> Northern Trail Outfitters wants to initiate expense reports from Salesforce to the external HR system. This process needs to be reviewed by managers and directors. Which two tools should an administrator configure? Choose 2 answers

> A Northern Trail Outfitters deseja iniciar relatórios de despesas do Salesforce para o sistema externo de RH. Esse processo precisa ser revisto por gerentes e diretores. Quais duas ferramentas um administrador deve configurar?

A. Outbound Message

B. Approval Process

C. Email Alert Action

D. Quick Action

<details>
  <summary>Gabarito:</summary>
  A e B (checked)

Outbond message:
Uma mensagem de saída envia informações para um endpoint designado, como um serviço externo. Você configura outbond messages em setup. Você deve configurar o endpoint externo e criar um listener para as mensagens usando a API SOAP.

Quick action:
Com ações rápidas personalizadas, você pode facilitar ao máximo a navegação e o fluxo de trabalho de seus usuários, dando a eles acesso conveniente às informações mais importantes. Por exemplo, você pode permitir que os usuários criem ou atualizem registros e registrem chamadas diretamente no feed do Chatter ou no dispositivo móvel.
</details>

___
## Questão 11
> The administrator at AW Computing wants Account details, related lists, and Chatter feeds to each appear or separate tabs when viewing an Account. Which type of page should the administrator create?

> O administrador da AW Computing deseja que os detalhes da conta, listas relacionadas e feeds do Chatter apareçam ou abas separadas ao visualizar uma conta. Que tipo de página o administrador deve criar?

A. Lightning app page

B. Lightning page component

C. Lightning page tab

D. Lightning record page

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 12
> Ursa Major Solar has a path on Case. The company wants to require its users to follow the status values as they are on the path. Agents should be prohibited from reverting the Case back to a previous status. Which feature should an administrator use to fulfill this request?

> A Ursa Major Solar tem um caminho no Case. A empresa deseja exigir que seus usuários sigam os valores de status conforme estão no caminho. Os agentes devem ser proibidos de reverter o caso para um status anterior. Qual recurso um administrador deve usar para atender a essa solicitação?

A. Global Value Picklists

B. Predefined Field Values

C. Dependent Picklists

D. Validation Rules

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 13
> Ursa Major Solar is noticing a decrease in deals with a cross-sell opportunity type and wants to share all cross-sell opportunities with a team of subject matter experts in their organization. The company has different roles, and the organisation-wide default opportunity is set to private. How should the administrator accomplish this?

> A Ursa Major Solar está percebendo uma diminuição nos negócios com um tipo de oportunidade de venda cruzada e deseja compartilhar todas as oportunidades de venda cruzada com uma equipe de especialistas no assunto em sua organização. A empresa tem funções diferentes e a oportunidade padrão em toda a organização é definida como privada. Como o administrador deve fazer isso?

A. Enable territory management, assign the subject matter experts to the same territory, and give them access to the records with manual sharing

(*Habilite o gerenciamento de território, atribua os especialistas no assunto ao mesmo território e dê a eles acesso aos registros com compartilhamento manual*)

B. Add the subject matter experts to a public group and give them access to the records with a criteria-based sharing rule

(*Adicione os especialistas no assunto a um grupo público e dê a eles acesso aos registros com uma regra de compartilhamento baseada em critérios*)

C. Create a new role for the subject matter experts and give them access to the records with an owner-based sharing rule

(*Crie uma nova função para os especialistas no assunto e dê a eles acesso aos registros com uma regra de compartilhamento baseada no proprietário*)

D. Change the organization-wide default for Opportunity from Private to Public Read/Write to open up access for the subject matter experts

(*Altere o padrão de toda a organização para Oportunidade de Privada para Leitura/Gravação Pública para abrir o acesso para os especialistas no assunto*)

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 14
> The administrator for Cloud Kicks needs to give access to a new custom object with custom fields to more than one User. Which two options should an administrator use to meet this requirement?

> O administrador do Cloud Kicks precisa dar acesso a um novo objeto personalizado com campos personalizados para mais de um usuário. Quais são as duas opções que um administrador deve usar para atender a esse requisito?

A. Create a permission set

B. Edit organization-wide defaults

(*Editar padrões de toda a organização*)

C. Assign permission set group to Users

(*Atribuir grupo de conjunto de permissões a usuários*)

D. Add to manual sharing list

(*Adicionar à lista de compartilhamento manual*)

<details>
  <summary>Gabarito:</summary>
  A e D (checked)
</details>

___
## Questão 15
> Sales reps at Northern Trail Outfitters have asked for a way to change the Probability field value of their Opportunities. What should an administrator suggest to meet this request?

> Os representantes de vendas da Northern Trail Outfitters pediram uma maneira de alterar o valor do campo Probabilidade de suas Oportunidades. O que um administrador deve sugerir para atender a essa solicitação?

A. Make the field editable on page layouts

B. Create a custom field on Opportunity

C. Configure Forecasting support

D. Define a new Stage picklist value

<details>
  <summary>Gabarito:</summary>
  A (checked)

  Forecasting support - suporte de previsão:
É uma funcionalidade específica que permite aos usuários prever e planejar o ciclo de vendas desde o pipeline até as vendas fechadas e gerenciar as expectativas de vendas em toda a sua organização de vendas.
</details>

___
## Questão 16
> Northern Trail Outfitters wants to encourage employees to choose secure and appropriate passwords for their salesforce accounts. Which three password policies should an administrator configure?

> A Northern Trail Outfitters quer incentivar os funcionários a escolherem senhas seguras e apropriadas para suas contas da força de vendas. Quais são as três políticas de senha que um administrador deve configurar?

A. Number of days until expiration

B. Password complexity requirements

C. Require use of Password Manager App

D. Prohibited password values

E. Maximum invalid login attempts

<details>
  <summary>Gabarito:</summary>
  A, B e E (checked)
</details>

___
## Questão 17
> An administrator installed a managed package that contains a permission set group. The permission set group that was installed includes Delete access on several objects, and the administrator needs to prevent users in the permission set group from being able to delete records. What should the administrator do to control Delete access?

> Um administrador instalou um pacote gerenciado que contém um grupo de conjuntos de permissões. O grupo de conjuntos de permissões que foi instalado inclui acesso Excluir em vários objetos, e o administrador precisa impedir que os usuários do grupo de conjuntos de permissões possam excluir registros. O que o administrador deve fazer para controlar o acesso de exclusão?

A. Edit the profile for the users to remove Delete access from the objects

(*Edite o perfil para os usuários removerem o acesso Excluir dos objetos*)

B. Create a new permission set that has Delete access deselected for the objects

(*Crie um novo conjunto de permissões que tenha o acesso Excluir desmarcado para os objetos*)

C. Use a muting permission set with a permission set group to mute selected permissions

(*Use um conjunto de permissões de silenciamento com um grupo de conjuntos de permissões para silenciar as permissões selecionadas*)

D. Create a new role that prevents Delete permissions from rolling up to the users

(*Crie uma nova função que impeça que as permissões de exclusão sejam acumuladas para os usuários*)

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 18
> A team of support users at Cloud Kicks is helping inside sales reps make follow-up calls to prospects that filled an interest form online. The team currently does not have access to the Lead object. How should an administrator provide proper access?

> Uma equipe de usuários de suporte da Cloud Kicks está ajudando os representantes de vendas internos a fazer ligações de acompanhamento para clientes em potencial que preencheram um formulário de interesse online. A equipe atualmente não tem acesso ao objeto Lead. Como um administrador deve fornecer acesso adequado?

A. Configure permission sets

B. Create a new profile

C. Set up Manual sharing

D. Assign a new role

<details>
  <summary>Gabarito:</summary>
  A (checked)


  Permission sets: A permission set is a collection of settings and permissions that give users access to various tools and functions. Permission sets extend users' functional access without changing their profiles. Users can have only one profile but, depending on the Salesforce edition, they can have multiple permission sets.

  Manual sharing: Manual sharing gives other users access to certain **types of records**, including accounts, contacts, and leads. Sometimes, granting access to one record includes access to all its associated records. For example, if you grant another user access to an account, the user automatically has access to all the opportunities and cases associated with that account
</details>

___
## Questão 19
> Cloud Kicks has a screen flow with two questions on the same screen, but only one is necessary at a time. The administrator has been asked to show only the question that is needed. How should an administrator complete this?

> Cloud Kicks tem um fluxo de tela com duas perguntas na mesma tela, mas apenas uma é necessária por vez. O administrador foi solicitado a mostrar apenas a pergunta necessária. Como um administrador deve concluir isso?

A. Use conditional visibility to hide the unnecessary question

(*Use a visibilidade condicional para ocultar a pergunta desnecessária*)

B. Use branching in the flow screen to show the proper scenario

(*Use a ramificação na tela de fluxo para mostrar o cenário adequado*)

C. Use a decision element and a new screen to show the proper question

(*Use um elemento de decisão e uma nova tela para mostrar a pergunta correta*)

D. Use a new version of the flow for each scenario

(*Use uma nova versão do fluxo para cada cenário*)

<details>
  <summary>Gabarito:</summary>
  A (check)
</details>

___
## Questão 20
> The administrator at AW Computing wants to send off client welcome tasks and a welcome email to the primary contact automatically when an opportunity is closed won. What automation tool best accomplishes this?

> O administrador da AW Computing deseja enviar automaticamente tarefas de boas-vindas ao cliente e um e-mail de boas-vindas para o contato principal quando uma oportunidade é fechada. Qual ferramenta de automação melhor faz isso?

A. Approval Process

B. Process Builder

C. Outbond Message

D. Validation Rule

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 21
> Users at Cloud Kicks are repporting different options when updating a custom picklist on the Opportunity object based on the kind of opportunity. Where should an administrator update the option in the picklist?

> Os usuários do Cloud Kicks estão relatando diferentes opções ao atualizar uma lista de opções personalizada no objeto Oportunidade com base no tipo de oportunidade. Onde um administrador deve atualizar a opção na lista de opções?

A. Picklist value sets

B. Related lookup filters

C. Fields and relationships

D. Record type

<details>
  <summary>Gabarito:</summary>
  D (checked)


  Os record types do Salesforce são formas de agrupar registros em um objeto específico. Normalmente, eles se concentram no que fará mais sentido para o usuário final. Exemplos de quando os record types podem ser necessários: Tipos de contas que diferentes grupos precisam acessar – contas de clientes, contas de parceiros, etc.
</details>

___
## Questão 22
> Cloud Kicks (CK) is partnering with a used shoe and second-hand bicycle emporium. CK has an automated business process it wants to run once a week to count the number of open cases related to an account. How should the administrator recommend automating this business process?

> Cloud Kicks (CK) está fazendo parceria com um empório de calçados usados e bicicletas de segunda mão. A CK tem um processo de negócios automatizado que deseja executar uma vez por semana para contar o número de casos abertos relacionados a uma conta. Como o administrador deve recomendar a automatização desse processo de negócios?

A. Configure a scheduled flow in Flow Builder

B. Create a workflow rule with an outbound message

C. Set up a scheduled process in Process Builder

D. Use a process to update the account when it is edited

<details>
  <summary>Gabarito:</summary>
  B (checked)


  Outbound messaging uses the notifications() call to send SOAP messages over HTTP(S) to a designated endpoint when triggered by a workflow rule.

  A Cloud Kicks (CK) está usando o salesforce enquanto o parceiro pode não estar usando salesforce (loja de sapatos e empório de bicicletas de segunda mão). Agora, o Salesforce deve se comunicar com o provedor de serviços externo, que pode ser uma organização da salesforce OU uma organização que não seja da salesforce. A melhor maneira de automatizar esse recurso é via mensagem de saída. As mensagens de saída permitem especificar que as alterações nos campos no Salesforce podem fazer com que as mensagens com valores de campo sejam enviadas para servidores externos designados. As mensagens de saída fazem parte da funcionalidade da regra de fluxo de trabalho no Salesforce. As regras de fluxo de trabalho observam tipos específicos de alterações de campo e acionam ações automáticas do Salesforce, como enviar alertas por email, criar registros de tarefas ou enviar uma mensagem de saída.

  > link outbound message and workflow rule: https://www.apexhours.com/outbound-message-in-salesforce/
</details>

___
## Questão 23
> The administrator for Cloud Kick has created a screen flow to help service reps ask the same set of questions when customers call in with issues. This screen should be visible from cases. How should the screen flow be distributed?

> O administrador do Cloud Kick criou um fluxo de tela para ajudar os representantes de serviço a fazer o mesmo conjunto de perguntas quando os clientes ligam com problemas. Esta tela deve ser visível nos casos. Como o fluxo de tela deve ser distribuído?

A. Home page

B. Page layout

C. Component filter

D. Lightning page

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 24
> Sales users at Universal Containers are reporting that it is taking a long time to edit opportunity records. Normally, the only field they are editing is the Stage field. Which two options should the administrator recommend to help simplify the process? Choose 2 answers.

> Os usuários de vendas da Universal Containers estão relatando que está demorando muito para editar os registros de oportunidade. Normalmente, o único campo que eles estão editando é o campo Stage. Quais são as duas opções que o administrador deve recomendar para ajudar a simplificar o processo? Escolha 2 respostas.

A. Add a Path for stage to the opportunity record page

(*Adicionar um caminho para o estágio na página de registro da oportunidade*)

B. Use a Kanban list view for Opportunity

C. Create a simplified Opportunity page layout

D. Configure an autolaunched flow for Opportunity editing

(*Configurar um fluxo iniciado automaticamente para edição de oportunidade*)

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 25
> Universal Containers introduced a new product and wants to track all associated cases that get logged. They are looking for an automated solution that would give the product's two lead engineers read/write access to all new cases that reference the new product. What should an administrator do to satisfy this requirement?

> A Universal Containers lançou um novo produto e deseja rastrear todos os casos associados que são registrados. Eles estão procurando uma solução automatizada que dê aos dois engenheiros líderes do produto acesso de leitura/gravação a todos os novos casos que fazem referência ao novo produto. O que um administrador deve fazer para atender a esse requisito?

A. Create an auto-response rule and a public group

B. Create a predefined case team and an assignment rule

C. Create a user-based sharing rule and an ad-hoc case team

D. Create a queue and a criteria-based sharing rule

<details>
  <summary>Gabarito:</summary>
  B 

  > link: https://help.salesforce.com/s/articleView?id=sf.creating_assignment_rules.htm&type=5
</details>

