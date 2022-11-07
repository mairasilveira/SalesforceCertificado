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

___
## Questão 26
> Cloud Kicks has a custom object called Shipments. The company wants to see all the shipment items from an Account page. When an Account is deleted, the shipments should remain. What type of relationship should the administrator make between Shipments and Accounts?

> Cloud Kicks tem um objeto personalizado chamado Shipments. A empresa deseja ver todos os itens de shipment de uma Account page. Quando uma conta é excluída, os itens shipment devem permanecer. Que tipo de relacionamento o administrador deve estabelecer entre Remessas e Contas?

A. Accounts should have a master detail to Shipments

(*As contas devem ter um detalhe mestre para Remessas*)

B. Shipments should have a master detail to Accounts

(*As remessas devem ter um detalhe mestre para Contas*)

C. Shipments should have a lookup to Account

(*As remessas devem ter um detalhe mestre para Contas*)

D. Accounts should have a lookup to Shipments

(*As contas devem ter uma pesquisa para Remessas*)

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 27
> Sales and Customer Care at Ursa Major Solar need to see different fields on the Case related list from the Account record. Sales users want to see Case created date and status while Customer Care would like to see owner, status and contact. What should the administrator use to achieve this?

> As vendas e o atendimento ao cliente da Ursa Major Solar precisam ver campos diferentes na lista relacionada ao caso do registro da conta. Os usuários de vendas desejam ver a data e o status de criação do caso, enquanto o Atendimento ao cliente deseja ver o proprietário, o status e o contato. O que o administrador deve usar para conseguir isso?

A. Page Layout Editor

B. Search Layout Editor

C. Related Lookup Filters

D. Compact Layout Editor

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 28
> Ursa Major Solar has service level agreements (SLA) that are routed to support queues. Cases that meet the 24 hour SLA need to be automatically re-assigned to the next tier queue. Which feature should be used to fulfill this requirement?

> > A Ursa Major Solar possui acordos de nível de serviço (SLA) que são roteados para filas de suporte. Os casos que atendem ao SLA de 24 horas precisam ser reatribuídos automaticamente para a fila do próximo nível. Qual recurso deve ser usado para atender a esse requisito?

A. Case escalation rule

B. Case assignment rule

C. Auto-response rule

D. Einsten Case Routing

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 30
> An administrator at Northern Trail Outfitters is unable to add a new user in Salesforce. What could cause this issue?

> Um administrador da Northern Trail Outfitters não consegue adicionar um novo usuário no Salesforce. O que pode causar esse problema?

A. The username is restricted to a domain specific to my domain

(*O nome de usuário está restrito a um domínio específico do meu domínio*)

B. The username is already in use another organization

(*O nome de usuário já está em uso em outra organização*)

C. The email address used for the username has a contact record

(*O endereço de e-mail usado para o nome de usuário tem um registro de contato*)

D. The email used for the username is not a corporate email address

(*O e-mail usado para o nome de usuário não é um endereço de e-mail corporativo*)

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 31
> An administrator at Universal Containers has been asked to prevent users from accessing Salesforce from of their network. What are two considerations for this configuration? Choose 2 

> Um administrador da Universal Containers foi solicitado a impedir que os usuários acessem o Salesforce de sua rede. Quais são as duas considerações para esta configuração? Escolha 2

A. Restrict U2F Security Keys on the user's profile to enforce login hours

(*Restrinja as chaves de segurança U2F no perfil do usuário para impor as horas de login*)

B. IP address restrictions are set on the profile or globally for the org

(*As restrições de endereço IP são definidas no perfil ou globalmente para a organização*)

C. Enforce Login IP Ranges on Every Request must be selected to enforce IP restrictions

(*Aplicar intervalos de IP de login em cada solicitação deve ser selecionado para impor restrições de IP*)

D. Assign single sign-on to a permission set to allow users to log in when outside the network

(*Atribuir logon único a um conjunto de permissões para permitir que os usuários façam login quando estiverem fora da rede*)

<details>
  <summary>Gabarito:</summary>
  B e C (checked)
</details>

___
## Questão 32
> What are three settings an administrator should configure to make it easy for approvers to respond to approval requests? Choose 3 answers

> Quais são as três configurações que um administrador deve configurar para facilitar a resposta dos aprovadores às solicitações de aprovação? Escolha 3 respostas

A. Enable the organization's email approval response setting

(*Habilite a configuração de resposta de aprovação de e-mail da organização*)

B. Update the organization's Chatter settings to allow approvals

(*Atualize as configurações do Chatter da organização para permitir aprovações*)

C. Specify initial submission actions within the approval process

(*Especifique as ações iniciais de envio dentro do processo de aprovação*)

D. Create a flow to automatically approve all records

(*Crie um fluxo para aprovar automaticamente todos os registros*)

E. Add the Items to Approve component to the approvers' home page

(*Adicione o componente Itens a Aprovar à página inicial dos aprovadores*)

<details>
  <summary>Gabarito:</summary>
  A, B e E (checked)
</details>

___
## Questão 33
> The administrator at Ursa Major Solar needs to make sure that unassigned cases from VIP customers get transferred to the appropriate service representative within 5 hours. VIP customers have access to support 24 hours a day. How should this be configured?

> O administrador da Ursa Major Solar precisa garantir que os casos não atribuídos de clientes VIP sejam transferidos para o representante de serviço apropriado dentro de 5 horas. Clientes VIP têm acesso ao suporte 24 horas por dia. Como isso deve ser configurado?

A. Business Hours

B. Escalation Rules

C. Case Queues

D. Assignment Rules

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 34
> The support manager at Cloud Kicks wants to respond to customers as quickly as possible. They have requested that the response include the top five troubleshooting tips that could help solve the customer's issue. What should the administrator suggest to meet these requirements?

> O gerente de suporte da Cloud Kicks quer responder aos clientes o mais rápido possível. Eles solicitaram que a resposta incluísse as cinco principais dicas de solução de problemas que poderiam ajudar a resolver o problema do cliente. O que o administrador deve sugerir para atender a esses requisitos?

A. Auto-Response Rules

B. Knowledge Articles

C. Assignment Rules

D. Email Alerts

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 35
> Users at DreamHouse Realty are only allowed to see opportunities they own. Leadership wants an enterprise dashboard of all open opportunities in the pipeline so that users can see how the company is performing at any point in time. How should an administrator create the dashboard without changing any sharing settings?

> Os usuários da DreamHouse Realty só podem ver as oportunidades que possuem. A liderança quer um painel corporativo de todas as oportunidades abertas no pipeline para que os usuários possam ver o desempenho da empresa a qualquer momento. Como um administrador deve criar o painel sem alterar as configurações de compartilhamento?

A. Add a filter to the dashboard to filter the opportunities by owner role

(*Adicione um filtro ao painel para filtrar as oportunidades por função de proprietário*)

B. Create a dashboard with the running user set as someone who can see all opportunities

(*Crie um painel com o usuário em execução definido como alguém que pode ver todas as oportunidades*)

C. Build individual dashboards for profiles that need to see the enterprise results

(*Crie painéis individuais para perfis que precisam ver os resultados corporativos*)

D. Update the dashboard folder settings to manager for the sales reps role

(*Atualize as configurações da pasta do painel para gerente da função de representantes de vendas*)

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 36
> A sales rep has left the company and an administrator has been asked to re-assign all their accounts and opportunities to a new sales rep and keep the teams as is. Which tool should an administrator use to accomplish this?

> Um representante de vendas deixou a empresa e um administrador foi solicitado a reatribuir todas as suas contas e oportunidades a um novo representante de vendas e manter as equipes como estão. Qual ferramenta um administrador deve usar para fazer isso?

A. Data Loader

B. Dataloader.io

C. Mass Transfer Tool

D. Data Import Wizard

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 37
> Sales reps at Ursa Major Solar are having difficulty managing deals. The leadership team has asked the administrator to help sales reps prioritize and close more deals. What should the administrator configure to help with these issues?

> Os representantes de vendas da Ursa Major Solar estão tendo dificuldades para gerenciar negócios. A equipe de liderança pediu ao administrador para ajudar os representantes de vendas a priorizar e fechar mais negócios. O que o administrador deve configurar para ajudar com esses problemas?

A. Einsten Search Personalization

B. Einsten Lead Scoring

(*O Einstein Lead Scoring adiciona um campo Lead Score aos leads. O Lead Score permite que os representantes de vendas priorizem seu trabalho classificando os leads de acordo com suas semelhanças com os leads convertidos anteriormente. Leads com pontuações mais altas têm mais em comum com leads que converteram no passado.*)

C. Einsten Activity Capture

(*O Einstein Activity Capture é uma ferramenta de aumento de produtividade que ajuda a manter atualizados os dados entre o Salesforce e seus aplicativos de email e calendário. Para manter os dados atualizados entre os aplicativos, o Einstein Activity Capture se concentra em três tipos de dados: e-mails, eventos e contatos. Saiba mais sobre como o Einstein Activity Capture lida com cada tipo de dados.*)

D. Einsten Opportunity Scoring

(*As pontuações de oportunidade indicam a probabilidade de uma oportunidade ser ganha. Para cada pontuação de oportunidade, o Einstein mostra os fatores que mais contribuíram para a pontuação, tanto positiva quanto negativamente.*)

<details>
  <summary>Gabarito:</summary>
  D (Checked)
</details>

___
## Questão 38
> Northern Trail Outfitters has a custom quick action on Account that creates a new Case. How should an administrator make the quick action available on the Salesforce mobile app?

> A Northern Trail Outfitters tem uma ação rápida personalizada na conta que cria um novo caso. Como um administrador deve disponibilizar a ação rápida no aplicativo móvel Salesforce?

A. Create a custom Lightning App with the action

B. Modify compact Case page layout to include the action

C. Include the action in the Salesforce Mobile Navigation menu

D. Add the Salesforce Mobile and Lightning Experience action to the page layout

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 39
> Universal Containers wants to increase the security of their org by requiring stricter user passwords. Which two of the following should an administrator configure? Choose 2 answers.

> A Universal Containers deseja aumentar a segurança de sua organização exigindo senhas de usuário mais rígidas. Quais das duas opções a seguir um administrador deve configurar? 

A. Password different than username

B. Password complexity requirement

C. Prevent common words

D. Minimum password length

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 40
> An administrator has been asked to change the data type of an auto number to a text field. What should the administrator be aware of before changing the field?

A. Existing Auto Number field to Text is prevented

B. Existing field values will be deleted

C. Existing field values will be converted

D. Existing field values will remain unchanged

<details>
  <summary>Gabarito:</summary>
  D
</details>

___
## Questão 41
> Cloud Kicks is working on a better way to track its product shipments utilizing Salesforce. Which field type should an administrator use to capture coordinates?

> A Cloud Kicks está trabalhando em uma maneira melhor de rastrear suas remessas de produtos utilizando o Salesforce. Qual tipo de campo um administrador deve usar para capturar coordenadas?

A. External lookup

B. Geolocation

C. Geofence

D. Custom address

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 42
> The marketing director at Northern Trail Outfitters has requested that the Budget field is populated in order for the Lead Status field to be marked as qualified. What tool should the administrator use to fulfill this request?

> O diretor de marketing da Northern Trail Outfitters solicitou que o campo Orçamento seja preenchido para que o campo Status do lead seja marcado como qualificado. Qual ferramenta o administrador deve usar para atender a essa solicitação?

A. Workflow Rule

B. Validation Rule

C. Require Field

D. Lead Conversion

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 43
> The administrator at Ursa Major Solar has created a custom report type and built a report for the sales operations team. However, none of the users are able to access the report. Which two options could cause this issue? Choose 2 answers

> O administrador da Ursa Major Solar criou um tipo de relatório personalizado e criou um relatório para a equipe de operações de vendas. No entanto, nenhum dos usuários pode acessar o relatório. Quais duas opções podem causar esse problema?

A. The report is saved in a private folder

B. The custom report type is in development

C. The user's profile is missing View access

D. The org has reached its limit for custom report types

<details>
  <summary>Gabarito:</summary>
  A e C (checked)
</details>

___
## Questão 44
> Northern Trail Outfitters (NTO) has deployed my domain. The Chief Marketing Officer wants to make sure that all of the Salesforce users log in using the branded login URL. There needs to be a grace period for the user's bookmarks to be updated. How should the administrator configure the policies in my domain settings?

> A Northern Trail Outfitters (NTO) implantou meu domínio. O diretor de marketing quer garantir que todos os usuários do Salesforce façam login usando o URL de login da marca. É necessário que haja um período de carência para que os favoritos do usuário sejam atualizados. Como o administrador deve configurar as políticas nas configurações do meu domínio?

A. Set the login policy to require login from https://nto.my.salesforce.com

B. Set the redirect policy to Redirect with a warning to the same page within the domain

C. Set the login policy to prevent login from https://login.salesforce.com

D. Set the Redirect policy to Do Not redirect

<details>
  <summary>Gabarito:</summary>
  B

No fim das contas, você quer forçar todos a usar as URLs da marca do Meu domínio da Jedeye Tech. Mas, por enquanto, você quer dar a seus usuários algum tempo para que atualizem seus favoritos. Ou seja, selecione a política de redirecionamento, Redirecionamento para a mesma página do domínio com um aviso. Agora, quando os usuários tentam acessar sua organização usando uma URL de instância, eles recebem uma mensagem **incentivando-os a atualizar seus favoritos**. Essa opção é boa por alguns dias para ajudar os usuários a migrar para as URLs do Meu domínio da sua organização. Depois disso, você pode atualizar o Meu domínio novamente para usar a política de redirecionamento recomendada: Não redirecionar.

  > Alternativa B - Redirecionar com um aviso para a mesma página no domínio – Lembre os usuários de usar as URLs do Meu domínio antes de redirecioná-los para sua organização. Isso pode ajudar a alterar o comportamento do usuário para que os usuários façam a transição para as URLs da marca.

  > Alternativa D - Não redirecionar (recomendado) – Exigir que o usuário utilize a URL de login do Meu domínio ao acessar sua organização. Essa configuração pressupõe que seus usuários fizeram a transição para usar as novas URLs do Meu domínio. Se não tiverem feito isso, eles receberão uma mensagem de erro quando tentarem usar a URL de instância do Salesforce.


  Ter um Meu domínio vai muito além de aproveitar uma solução conveniente e criar uma experiência personalizada de login naquela organização. O que importa é conseguir controlar melhor seu processo de login e simplificar os procedimentos de autenticação. Na verdade, o Salesforce exige que você tenha um Meu domínio para:
- Trabalhar em várias organizações do Salesforce no mesmo navegador.
- Configurar um login único (SSO) com terceiros provedores de identidade.
- Definir provedores de autenticação, como o Google ou o Facebook, para seus usuários poderem fazer o login na sua organização do Salesforce com as credenciais das contas sociais que já usam.
- Personalizar a página de login da sua organização com sua marca.
</details>

___
## Questão 45
> Northern Trail Outfitters has the Case object set to private. The support manager raised a concern that reps has a broader view of data than expected and can see all cases on their group's dashboards. What could be causing reps to have inappropriate access to data on dashboards?

> A Northern Trail Outfitters tem o objeto Case definido como privado. O gerente de suporte levantou uma preocupação de que os representantes têm uma visão mais ampla dos dados do que o esperado e podem ver todos os casos nos painéis de seus grupos. O que pode estar fazendo com que os representantes tenham acesso inadequado aos dados nos painéis?

A. Public Dashboards

B. Dynamic Dashboards

C. Dashboard Filters

D. Dashboard Subscriptions

<details>
  <summary>Gabarito:</summary>
  B (checked)

  Dynamic Dashboards: Digamos que seu pessoal de vendas possa visualizar apenas suas próprias oportunidades, mas você gostaria de revisar todas as oportunidades fechadas no último trimestre. Crie um painel e permita que as pessoas vejam o painel como você (ou qualquer outra pessoa que possa ver todas as oportunidades). Quando seus vendedores abrem o painel, eles veem informações sobre todas as oportunidades em vez de apenas suas oportunidades. (O acesso a dados deles no Salesforce permanece inalterado. Eles só podem ver mais dados em seu painel.)
</details>

___
## Questão 46
> Support agents at Cloud Kicks are spending too much time finding resources to solve customer cases. The agents need a more efficient way to find documentation and similar cases from the Case page layout. How should an administrator meet this requirement?

> Os agentes de suporte da Cloud Kicks estão gastando muito tempo procurando recursos para resolver casos de clientes. Os agentes precisam de uma maneira mais eficiente de localizar documentação e casos semelhantes no layout da página Caso. Como um administrador deve atender a esse requisito?

A. Use an interview flow to capture Case details

B. Configure Knowledge with articles and data categories

C. Direct users to Global Search to look for similar cases

D. Create a custom object to capture popular Case resolutions

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 47
> What are two considerations an administrator should keep in mind when working with Salesforce objects? Choose 2 answers

> Quais são as duas considerações que um administrador deve ter em mente ao trabalhar com objetos do Salesforce? Escolha 2 respostas

A. Only standard objects support master-detail relationships

B. Custom and standard objects have standard fields

C. A new standard object can be created

D. Standard objects are included with Salesforce

(*Standard objects are included with Salesforce*)

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 48
> The administrator at Cloud Kicks has been told that users are unable to add repeating tasks in Salesforce. Which two solutions should the administrator use to ensure users are able to do this? Choose 2 answers

> O administrador da Cloud Kicks foi informado de que os usuários não estão conseguindo adicionar tarefas repetidas no Salesforce. Quais são as duas soluções que o administrador deve usar para garantir que os usuários possam fazer isso? Escolha 2 respostas

A. Turn on Task Notifications Service

B. Enable Creation of Recurring Tasks in Activity Settings

C. Disable Shared Activities

D. Add Create Recurring Series of Tasks field on page layout

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 49
> The marketing team at Ursa Major Solar wants to send a personalized email whenever a lead fills out the web-to-Lead form on their website. They want to send different messages based on the Lead Industry field value. What should an administrator configure to meet this requirement?

> A equipe de marketing da Ursa Major Solar deseja enviar um e-mail personalizado sempre que um lead preencher o formulário web-to-Lead em seu site. Eles querem enviar mensagens diferentes com base no valor do campo Lead Industry. O que um administrador deve configurar para atender a esse requisito?

A. Create an assignment rule to email the lead

B. Add a public group and Process Builder to email the lead

C. Use a validation rule to trigger workflow to email the lead

D. Configure an auto-response rule to email the lead

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 50
> AW Computing needs to capture a loss reason in a rich text field when an opportunity is closed lost. How should an administrator configure this requirement?

> A AW Computing precisa capturar um motivo de perda em um campo de rich text quando uma oportunidade é fechada e perdida. Como um administrador deve configurar esse requisito?

A. Create a validation rule to display an error if stage is closed lost and Lost Reason is blank

B. Select the required checkbox next to the Loss Reason field on the page layout

C. Check the required checkbox on the Loss Reason field in Object Manager

D. Configure a workflow rule to display an error if Loss Reason is blank

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 51
> The administrator at Ursa Major Solar has been asked to change the Work Item and Project custom object relationship from a master-detail to a lookup. Which scenario could prevent the administrator from fulfilling this requirement?

> O administrador da Ursa Major Solar foi solicitado a alterar o relacionamento de objeto personalizado de item de trabalho e projeto de um mestre-detalhe para uma pesquisa. Qual cenário poderia impedir o administrador de cumprir esse requisito?

A. Roll-up summary fields exist on the master object

(*Existem campos de resumo de totalização no objeto mestre*)

B. The lookup field in all the records contains a value

(*O campo de pesquisa em todos os registros contém um valor*)

C. The lookup field is required for saving records

(*O campo de pesquisa é obrigatório para salvar registros*)

D. A junction object is required to support the lookup

(*Um objeto de junção é necessário para dar suporte à pesquisa*)

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 52
>  Which two solutions could an administrator find on the AppExchange to enhance their organization? Choose 2 answers

> Quais são as duas soluções que um administrador pode encontrar no AppExchange para aprimorar sua organização? Escolha 2 respostas

A. Components

B. Communities

C. Consultants

D. Customers

<details>
  <summary>Gabarito:</summary>
  A e C (checked)
</details>

___
## Questão 53
> At Universal Containers, there is a custom field on the Lead named Product Category. Management wants this information to be part of the Opportunity upon lead conversion. What action should the administrator take to satisfy the request?

> Na Universal Containers, há um campo personalizado no Lead chamado Product Category. A gerência deseja que essas informações façam parte da Oportunidade na conversão de leads. Que ação o administrador deve tomar para satisfazer a solicitação?

A. Create a custom field on the Opportunity and map the two fields

B. Configure the product categories picklist field on the product

C. Create a workflow to update Opportunity fields based on the lead

D. Map the lead custom field to the product's product category field

<details>
  <summary>Gabarito:</summary>
  A (checked)

  Este mapeamento sincroniza as atualizações entre os campos de todos os registros compartilhados
</details>

___
## Questão 54
> Universal Containers has three separate lines of business. Each line has specific fields that must be displayed to users. However, the fields needed by the sales team are different than the fields needed by the service team. How should the administrator configure this requirement?

> A Universal Containers tem três linhas de negócios separadas. Cada linha possui campos específicos que devem ser exibidos aos usuários. No entanto, os campos necessários para a equipe de vendas são diferentes dos campos necessários para a equipe de serviço. Como o administrador deve configurar esse requisito?

A. Create two record types, each with 3 pages layouts

B. Create three record types, each with 2 page layouts

C. Create six record types, each with 2 page layouts

D. Create one record type, with six Page Layouts

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 55
> Cloud Kicks wants its reports to show a Fiscal Year that starts on February 1 and has 12 months. How should the administrator address this requirement?

> A Cloud Kicks quer que seus relatórios mostrem um ano fiscal que comece em 1º de fevereiro e tenha 12 meses. Como o administrador deve lidar com esse requisito?

A. Set the Fiscal Year to Standard and the duration to 12 months

B. Set the Fiscal Year to Standard and the starting month as February

C. Set the Fiscal Year to Custom and the starting month as February

D. Set the Fiscal Year to Custom and the duration to 4 quarters

<details>
  <summary>Gabarito:</summary>
  B (checked)
</details>

___
## Questão 56
> An administrator creates a custom text area field on the Account object and adds it to the service team's page layout. The service team manager loves the addition of this field and wants it to appear in the highlights panel so that the service reps can quickly find it when on the Account page. How should the administrator accomplish this?

> Um administrador cria um campo de área de texto personalizado no objeto Conta e o adiciona ao layout de página da equipe de serviço. O gerente da equipe de serviço adora a adição desse campo e deseja que ele apareça no painel de destaques para que os representantes de serviço possam encontrá-lo rapidamente na página Conta. Como o administrador deve fazer isso?

A. In the Account object manager, create a custom compact layout

B. From the page layout editor, drag the field to the hightlights panel

C. Make the field required and move it to the top of the page

D. Create a new page layout and a new section titled highlights panel

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 57
> The administrator at Universal Containers wants to add branding to Salesforce. Which two considerations should the administrator keep in mind? Choose 2 answers

> O administrador da Universal Containers deseja adicionar identidade visual ao Salesforce. Quais são as duas considerações que o administrador deve ter em mente? Escolha 2 respostas

A. Only one theme can be active at a time, and a theme applies to the entire org

B. Up to 150 custom themes can be created, modified, or cloned from the built-in-themes

C. Themes apply to Salesforce Classic and to the Salesforce mobile app

D. Chatter external users see the built-in Lightning blue theme only

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___
## Questão 58
> When a sales rep clicks a button on an opportunity, a simple discount calculator screen should be launched. Which automation tool should an administrator use to build this discount calculator screen?

> Quando um representante de vendas clica em um botão em uma oportunidade, uma tela simples de calculadora de descontos deve ser iniciada. Qual ferramenta de automação um administrador deve usar para construir esta tela de calculadora de descontos?

A. Workflow Rule

B. Process Builder

C. Platform Event

D. Flow Builder

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___
## Questão 59
> An administrator at AW Computing has been asked to help the Support team with report folders. They want a folder called Support Reports and two folders underneath called Helpdesk and R&D. The Support organization uses public groups for Support Agents, R&D, and Managers. Support agents should be able to run Helpdesk reports, but should not be able to view R&D reports. Support managers should be able to view and edit all reports. Which two ways should these folders be shared? Choose 2 answers.

> Um administrador da AW Computing foi solicitado a ajudar a equipe de suporte com pastas de relatórios. Eles querem uma pasta chamada Relatórios de Suporte e duas pastas abaixo chamadas Helpdesk e R&D. A organização de suporte usa grupos públicos para agentes de suporte, P&D e gerentes. Os agentes de suporte devem ser capazes de executar relatórios do Helpdesk, mas não devem ser capazes de visualizar relatórios de P&D. Os gerentes de suporte devem poder visualizar e editar todos os relatórios. De quais duas maneiras essas pastas devem ser compartilhadas? Escolha 2 respostas.

A. Share the R&D folder with Support Managers with Edit Access

B. Share the Helpdesk folder with Support Agents with View access

C. Share the Support Reports folder with Support Managers with Edit Access

D. hare the Support Reports folder with Support Agents with View Access

<details>
  <summary>Gabarito:</summary>
  B e C (checked)
</details>

___
## Questão 60
> When a Cloud Kicks opportunity closes, the company would like to automatically create a renewal opportunity. Which two automation tools should an administrator use to accomplish this request? Choose 2 answers

> Quando uma oportunidade Cloud Kicks é fechada, a empresa gostaria de criar automaticamente uma oportunidade de renovação. Quais duas ferramentas de automação um administrador deve usar para realizar essa solicitação? Escolha 2 respostas

A. Approval Proccess

B. Process Builder

C. Workflow Rule

D. Flow Builder

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 61
> Ursa Major Solar has its business hours set from 9:00 AM to 5:00 PM for the reps that are on Pacific Time. The reps on Eastern Time need business hours set to start 3 hours earlier to cover for support. How should an administrator solve for this issue?

> A Ursa Major Solar tem seu horário comercial definido das 9h às 17h para os representantes que estão no horário do Pacífico. Os representantes no horário do leste precisam de horário comercial definido para começar 3 horas antes para cobrir o suporte. Como um administrador deve resolver esse problema?

A. Adjust the current business hours to accomodate the Eastern Time Zone

B. Set temporary business hours for each time zone

C. Create one set of business hours per time zone

D. Allow the reps to set business hours manually

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 62
> At cloud kicks sales reps use discounts on the opportunity record to help win sales on products. When an opportunity is won, they then have to manually apply the discount up the related opportunity products. The sales manager has asked if there is a way to automate this time-consuming task. What should the administrator use to deliver this requirement?

> Na cloud kicks, os representantes de vendas usam descontos no registro de oportunidades para ajudar a ganhar vendas de produtos. Quando uma oportunidade é ganha, eles precisam aplicar manualmente o desconto nos produtos de oportunidade relacionados. O gerente de vendas perguntou se existe uma maneira de automatizar essa tarefa demorada. O que o administrador deve usar para entregar esse requisito?

A. Approval Process

B. Prebuilt Macro

C. Flow Builder

D. Formula Field

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 63
> An administrator at Cloud Kicks is building a flow that needs to search for records that meet certain conditions and store values from those records in variables for use later in the flow. What flow element should the administrator add?

> Um administrador da Cloud Kicks está construindo um fluxo que precisa procurar registros que atendam a determinadas condições e armazenar valores desses registros em variáveis para uso posterior no fluxo. Qual elemento de fluxo o administrador deve adicionar?

A. Update Records

B. Assignment

C. Get Records

D. Create Records

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___
## Questão 64
> Which two actions should an administrator perform with Case escalation rules? Choose 2 answers

> Quais são as duas ações que um administrador deve executar com as regras de escalonamento de caso? Escolha 2 respostas

A. Re-open the Case

B. Send email notifications

C. Change the Case Priority

D. Re-assign the Case

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

___
## Questão 65
> Executives at Cloud Kicks have reported that their dashboards are showing inaccurate data. The administrator has discovered that users have been changing the source reports. Which two actions should the administrator take to preserve the integrity of the source reports? Choose 2 answers

> Executivos da Cloud Kicks relataram que seus painéis estão mostrando dados imprecisos. O administrador descobriu que os usuários estão alterando os relatórios de origem. Quais são as duas ações que o administrador deve tomar para preservar a integridade dos relatórios de origem? Escolha 2 respostas

A. Move the dashboard to the user's private folder

B. Move the dashboard reports to the view-only folder

C. Change the dashboard to be a dynamic dashboard

D. Create a new report folder with viewer access

<details>
  <summary>Gabarito:</summary>
  B e D (checked)
</details>

