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

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 12

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 13

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 14

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 15

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 16

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 17

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 18

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 19

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 20

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 21

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 22

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 23

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 24

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 25

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 26

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 27

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 28

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 29

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 30

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 31

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 32

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 33

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 34

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 35

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 36

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 37

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 38

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___
## Questão 39

A.

B.

C.

D.

<details>
  <summary>Gabarito:</summary>
  
</details>

___