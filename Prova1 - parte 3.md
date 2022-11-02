## Questão 46
> The administrator at Cloud Kicks has been asked to change the company's Shoe Style field to prevent users from selecting more than one style on a record. Which two steps should an administrator do to accomplish this?

> O administrador da Cloud Kicks foi solicitado a alterar o campo Shoe Style da empresa para impedir que os usuários selecionem mais de um estilo em um registro. Quais são as duas etapas que um administrador deve fazer para conseguir isso?

A. Back-up the Shoe Style values in existing records

(*Fazer backup dos valores de estilo de sapato em registros existentes*)

B. Reactivate the appropriate Shoe Style values after the field type changes

(*Reative os valores apropriados de estilo de sapato após as alterações do tipo de campo*)

C. Change the field type from a multi-select picklist field to a picklist field

(*Alterar o tipo de campo de um campo de lista de opções de seleção múltipla para um campo de lista de opções*)

D. Select the "Choose only one value" checkbox on the picklist field

(*Marque a caixa de seleção "Escolher apenas um valor" no campo da lista de opções*)

<details>
  <summary>Gabarito:</summary>
  C e D (checked)
</details>

___
## Questão 47
> Cloud Kicks wants to give credit to Opportunity team members based on the level of effort contributed by each person towards each deal. What feature should the administrator use to meet this requirement?

> A Cloud Kicks quer dar crédito aos membros da equipe do Opportunity com base no nível de esforço contribuído por cada pessoa para cada negócio. Qual recurso o administrador deve usar para atender a esse requisito?

A. List Views (*Visualizações de lista*)

B. Stages (*Estágios*)

C. Splits (*Divisões*)

D. Queues (*Filas*)

<details>
  <summary>Gabarito:</summary>
  C

List view: Em uma exibição de lista, você vê apenas os dados aos quais tem acesso. Você pode ver os registros que possui, tem acesso de leitura ou gravação ou são compartilhados com você. As exibições de lista também incluem registros pertencentes ou compartilhados com usuários em funções abaixo de você na hierarquia.

Stages: Quais são as 5 etapas do processo de vendas?
Aproxime-se do cliente. 
Descubra as necessidades do cliente. 
Dê uma solução. 
Feche a venda. 
Conclua a venda e acompanhe.
 Estágios de oportunidade é simplesmente um campo de lista de opções (ou lista suspensa) no Salesforce. O campo tem um número finito de valores que um usuário pode selecionar e geralmente se move ao longo desses valores de maneira linear. Pronto para uso, o Salesforce tem vários padrões

 Splits: se o administrador do Salesforce habilitou as divisões de oportunidades, você poderá dividir o crédito de uma oportunidade entre os membros de uma equipe de oportunidades. Compartilhe a receita usando divisões de oportunidade. Compartilhe a receita das oportunidades e dê crédito aos membros da equipe por ajudar a fechar negócios.

 Queues: Priorize e atribua registros a equipes que compartilham cargas de trabalho. Não há limite para o número de filas que você pode criar e você pode escolher quando os membros da fila receberão notificações por e-mail.

</details>

___
## Questão 48

> Users at Cloud Kicks want to be able to create a task that will repeat every two weeks. What should an administrator do to meet this requirement?

> Os usuários da Cloud Kicks querem poder criar uma tarefa que se repetirá a cada duas semanas. O que um administrador deve fazer para atender a esse requisito?

A. Enable Creation of Recurring Tasks

(*Ativar a criação de tarefas recorrentes*)

B. Flow to create recurring tasks

(*Fluxo para criar tarefas recorrentes*)

C. Turn on Recurring Activities

(*Ativar atividades recorrentes*)

D. Workflow rule to create recurring tasks

(*Regra de fluxo de trabalho para criar tarefas recorrentes*)

<details>
  <summary>Gabarito:</summary>
  A
</details>

___
## Questão 49
> Ursa Major Solar uses Opportunity to track sales of solar energy products. The company has two separate sales teams that focus on different energy markets. The services team also wants to use Opportunity to track installation. All three teams will need to use different fields and stages. How should the administrator configure this requirement?

> A Ursa Major Solar usa o Opportunity para rastrear as vendas de produtos de energia solar. A empresa tem duas equipes de vendas separadas que se concentram em diferentes mercados de energia. A equipe de serviços também deseja usar o Opportunity para rastrear a instalação. Todas as três equipes precisarão usar campos e estágios diferentes. Como o administrador deve configurar esse requisito?

A. Create one sales process. Create three record types and three page layouts.

B. Create one sales process. Create one record type and three page layouts.

C. Create three sales process. Create three record types and three page layouts.

D. Create three sales process. Create three record types and one page layout.

<details>
  <summary>Gabarito:</summary>
  C
  
  O requisito também menciona que existem três processos de venda diferentes. Como só podemos atribuir um processo de vendas a um tipo de registro, precisaremos criar três! Além disso, eles também gostariam de capturar dados diferentes para cada processo de vendas. Isso exigirá que três layouts de página (além) sejam atribuídos a cada tipo de registro.

  Exemplo A: Os usuários do suporte estão sendo integrados ao Salesforce. Eles são obrigados a visualizar uma extensa quantidade de informações sobre contas em torno da solução técnica do cliente. Esta informação não se aplica a nenhum usuário existente. Eles têm dois perfis de suporte.

Com este exemplo, temos um caso de uso bastante simples. Como os usuários de suporte estão sendo trazidos para o sistema, eles precisam ver informações diferentes dos outros. Como estamos lidando apenas com uma visualização adicional para um grupo de usuários, podemos usar um layout de página adicional e aplicá-lo a ambos os perfis de suporte.

Exemplo B: As vendas agora estão vendendo para contas corporativas e, como tal, têm um processo de lead diferente que precisa ser implementado. Nesta fase, as Vendas exigem apenas diferentes status de Lead. Eles têm dois perfis de vendas.

Existem alguns critérios a serem observados ao avaliar se um tipo de registro deve ser usado ou não. Como o requisito acima menciona uma mudança de processo de lead, precisaremos usar automaticamente um tipo de registro. Não há menção a nenhuma alteração de campo, portanto, podemos aplicar facilmente um único tipo de registro aos dois perfis.

Exemplo C: As vendas têm ainda outro requisito (*Suspiro*) – eles gostariam de implementar um processo de venda diferente em Oportunidades para cada um de seus três níveis de contas (1-100, 101-500, 501+ funcionários). Isso envolve diferentes etapas pelas quais a venda se move, além de capturar diferentes informações ao longo do caminho. Eles têm apenas um perfil de vendas.

Aqui está um requisito mais empolgante. Podemos ver que diferentes processos são mencionados imediatamente, portanto, os tipos de registro terão que ser usados. O requisito também menciona que existem três processos de venda diferentes. **Como só podemos atribuir um processo de vendas a um record type, precisaremos criar três!** Além disso, eles também gostariam de capturar dados diferentes para cada processo de vendas. Isso exigirá que três layouts de página (além) sejam atribuídos a cada tipo de registro.

Exemplo D: A equipe de suporte precisa mostrar informações diferentes no layout da página, dependendo do nível para o qual o caso foi escalado (Nível 1, 2 ou 3). Os agentes de suporte têm três perfis diferentes que correspondem ao nível de escalação.

O requisito parece ser direto, pois eles mencionaram diretamente a necessidade de diferentes layouts de página - por causa das três camadas, sabemos que precisaremos de três layouts de página. O fato de termos três perfis diferentes convenientemente configurados significa que podemos simplesmente atribuir cada layout de página a cada perfil. No entanto, se tivéssemos apenas um perfil aqui, precisaríamos de tipos de registro para atender ao requisito (com alguma automação para alterar os tipos de registro com base no escalonamento!).
</details>

___
## Questão 50
> Cloud Kicks wants users to only be able to choose Opportunity stage closed won if the Lead source has been selected. How should the administrator accomplish this goal?

> A Cloud Kicks quer que os usuários só possam escolher o estágio de oportunidade fechado ganho se a origem do lead tiver sido selecionada. Como o administrador deve atingir esse objetivo?

A. Change the Opportunity stage field to read only on the page layout

(*Altere o campo do estágio da oportunidade para somente leitura no layout da página*)

B. Modify the Opportunity stage a dependent picklist to the Lead source field

(*Modifique o estágio Oportunidade de uma lista de opções dependente para o campo Origem do lead*)

C. Make Lead source a dependent picklist to the Opportunity stage field

(*Tornar a origem do lead uma lista de opções dependente do campo do estágio Oportunidade*)

D. Configure a validation rule requiring Lead source when the stage is set to closed won

(*Configure uma regra de validação que exija a origem do lead quando o estágio estiver definido como fechado ganho*)

<details>
  <summary>Gabarito:</summary>
  D
</details>

___
## Questão 51
> Northern Trail Outfitters has a custom quick action on Account that creates a new Case. How should an administrator make the quick action available on the Salesforce mobile app?

> A Northern Trail Outfitters tem uma ação rápida personalizada na conta que cria um novo caso. Como um administrador deve disponibilizar a ação rápida no aplicativo móvel Salesforce?


A. Add the Salesforce Mobile and Lightning Experience action to the page layout

(*Adicione a ação Salesforce Mobile e Lightning Experience ao layout da página*)

B. Create a custom Lightning App with the action

(*Crie um aplicativo Lightning personalizado com a ação*)

C. Include the action in the Salesforce Mobile Navigation menu

(*Incluir a ação no menu Salesforce Mobile Navigation*)

D. Modify compact Case page layout to include the action

(*Modifique o layout compacto da página Case para incluir a ação*)

<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___
## Questão 52
> The administrator at Cloud Kicks has a custom picklist field on Lead, which is missing on the Contact when leads are converted. Which two items should the administrator do to make sure these values are populated?

> O administrador do Cloud Kicks tem um campo de lista de opções personalizado no Lead, que está ausente no Contato quando os leads são convertidos. Quais são os dois itens que o administrador deve fazer para garantir que esses valores sejam preenchidos?

A. Create a custom picklist field on Contact

(*Crie um campo de lista de opções personalizado em Contato*)

B. Set the picklist field to be required on the Lead object

(*Defina o campo de lista de opções a ser obrigatório no objeto Lead*)

C. Update the picklist value with a validation rule

(*Atualizar o valor da lista de opções com uma regra de validação*)

D. Map the picklist field on the Lead to the Contact

(*Mapeie o campo da lista de opções no lead para o contato*)
<details>
  <summary>Gabarito:</summary>
  A e D (checked)
</details>

___
## Questão 53

> The administrator at Ursa Major Solar imported records into an object by mistake. Which two tools should be used to undo this import? Choose 2 answers

> O administrador da Ursa Major Solar importou registros para um objeto por engano. Quais duas ferramentas devem ser usadas para desfazer essa importação? Escolha 2 respostas

A. Data Loader

B. Mass Delete Records

C. Data Import Wizard

D. Weekly Data Export

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___

## Questão 54
> The events manager at DreamHouse Realty has a hot lead from a successful open house that needs to become a Contact with an associated Opportunity. How should this be accomplished from the Campaign keeping the associated Campaign Member history?

> O gerente de eventos da DreamHouse Realty tem um hot lead de uma casa aberta de sucesso que precisa se tornar um contato com uma oportunidade associada. Como isso deve ser feito a partir da Campanha, mantendo o histórico do Membro da Campanha associado?

A. Convert the lead from the Campaign Member Detail page

(*Converter o lead da página de detalhes do membro da campanha*)

B. Delete the lead and create a new Contact and Opportunity

(*Exclua o lead e crie um novo contato e oportunidade*)

C. Clone the lead and convert the cloned record to a Contact

(*Clone o lead e converta o registro clonado em um contato*)

D. Add a Contact from the Campaign Member Detail page

(*Adicionar um contato na página de detalhes do membro da campanha*)
<details>
  <summary>Gabarito:</summary>
  A (checked)
</details>

___

## Questão 55
> An administrator at Northern Trail Outfitters is creating a validation rule. Which two functions should the administrator use when creating a validation rule? Choose 2 answers

> Um administrador da Northern Trail Outfitters está criando uma regra de validação. Quais duas funções o administrador deve usar ao criar uma regra de validação? Escolha 2 respostas

A. Error message location

(*Localização da mensagem de erro*)

B. Error condition formula

(*Fórmula de condição de erro*)

C. Formula return type

D. Rule active date

(*Data ativa da regra*)

<details>
  <summary>Gabarito:</summary>
  A e B
</details>

___

## Questão 56
> Ursa Major Solar has service local agreements (SLA) that are routed to support queues. Cases that meet the 24 hour SLA need to be automatically re-assigned to the next tier queue. Which feature should be used to fulfill this requirement?

> A Ursa Major Solar tem acordos locais de serviço (SLA) que são roteados para filas de suporte. Os casos que atendem ao SLA de 24 horas precisam ser reatribuídos automaticamente para a fila do próximo nível. Qual recurso deve ser usado para atender a esse requisito?

A. Case escalation rule

B. Einstein Case Routing

C. Auto-response rule

D. Case assignment rule

<details>
  <summary>Gabarito:</summary>
  A (checked)

  It's definitely escalation rules, the case has already been assigned and needs to be re assigned after an interval of time to the next "tier queue"
</details>

___

## Questão 57
> Universal Containers requires that when an opportunity is closed won, all other open opportunities on the same account must be marked as closed lost. Which automation solution should an administrator use to implement this request?

> A Universal Containers exige que, quando uma oportunidade for fechada, todas as outras oportunidades abertas na mesma conta sejam marcadas como fechadas e perdidas. Qual solução de automação um administrador deve usar para implementar essa solicitação?

A. Outbond Message

B. Workflow Rule

C. Quick Action

D. Flow Builder

<details>
  <summary>Gabarito:</summary>
  D (checked)
</details>

___

## Questão 58
> A sales rep at Ursa Major Solar has launched a series of networking events. They are hosting one event per month and want to be able to report on Campaign ROI by month and series. How should the administrator set up the Campaign to simplify reporting?

> Um representante de vendas da Ursa Major Solar lançou uma série de eventos de networking. Eles estão organizando um evento por mês e desejam relatar o ROI da campanha por mês e por série. Como o administrador deve configurar a Campanha para simplificar a geração de relatórios?

A. Create individual Campaigns that all have the same name

(*Crie campanhas individuais que tenham o mesmo nome*)

B. Use Campaign Hierarchy where the monthly events roll up to a parent Campaign

(*Use a Hierarquia de campanha em que os eventos mensais são acumulados em uma campanha principal*)

C. Configure Campaign Member Statuses to record which event Members attended

(*Configure os status dos membros da campanha para registrar em qual evento os membros compareceram*)

D. Add different record types for the monthly event types

(*Adicione diferentes tipos de registro para os tipos de eventos mensais*)

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___

## Questão 59
> Universal Container's administrator has been asked to create a many-to-many relationship between two existing custom objects. Which two steps should the administrator take when enabling the many-to-many relationship? Choose 2 answers

> O administrador do Universal Container foi solicitado a criar um relacionamento muitos-para-muitos entre dois objetos personalizados existentes. Quais são as duas etapas que o administrador deve seguir ao habilitar o relacionamento muitos-para-muitos? Escolha 2 respostas

A. Create a junction with a custom object

(*Criar uma junção com um objeto personalizado*)

B. Create two master-detail relationships on the new object

(*Crie dois relacionamentos mestre-detalhe no novo objeto*)

C. Create two lookup relationships on the new object

(*Crie dois relacionamentos de pesquisa no novo objeto*)

D. Create URL fields on a custom object

(*Criar campos de URL em um objeto personalizado*)

<details>
  <summary>Gabarito:</summary>
  A e B (checked)
</details>

___

## Questão 60
> Universal Containers has enabled Data Protection and Privacy for its org. Which page layouts will have the Individual field available for tracking data privacy information?

> A Universal Containers habilitou a Proteção e Privacidade de Dados para sua organização. Quais layouts de página terão o campo Individual disponível para rastrear informações de privacidade de dados?

A. Contact, Lead, and Person Account

B. Individual, User and Account

C. Account and User

D. Case and Opportunity

<details>
  <summary>Gabarito:</summary>
  C (check)
</details>

___

## Questão 61
> An administrator supporting a global team of Salesforce users has been asked to configure company settings. Which two options should the administrator configure? Choose 2 answers

> Um administrador que dá suporte a uma equipe global de usuários do Salesforce foi solicitado a definir as configurações da empresa. Quais duas opções o administrador deve configurar?

A. Default Language

B. Password Policy

C. Currency Locale

D. Login Hours

<details>
  <summary>Gabarito:</summary>
  A e C (checked)
</details>

___

## Questão 62
> Cloud Kicks needs to be able to show different picklist values for sales and marketing users. Which two options will meet this requirement? Choose 2 

> O Cloud Kicks precisa mostrar valores de lista de opções diferentes para usuários de vendas e marketing. Quais duas opções atenderão a esse requisito? Escolha 2

A. Two page layouts, one record type, two picklists

(*Dois layouts de página, um tipo de registro, duas listas de opções*)

B. One page layout, two record types, one picklist

(*Um layout de página, dois tipos de registro, uma lista de opções*)

C. Two permission sets, one record type, one picklist

(*Dois conjuntos de permissões, um tipo de registro, uma lista de opções*)

D. One record type, two profiles, one picklist

(*Um tipo de registro, dois perfis, uma lista de opções*)

<details>
  <summary>Gabarito:</summary>
  A e B (checked)

  - 2 páginas de layout com a informação da picklist de acordo com o usuário (cria-se 2 picklists portanto) e um record type
  - 1 página de layout, 1 picklist e 2 record type (uma pra cada perfil de usuário)

  Record Type: Os tipos de registro permitem que você ofereça diferentes processos de negócios, valores de picklists e layouts de página para diferentes usuários. Por exemplo, um dos casos de uso mais comuns de Tipos de registro seria criar dois processos de vendas diferentes no objeto Oportunidade – cada um com diferentes estágios de vendas e layouts de página. Isso significa que, com os Tipos de registro, agora você pode aplicar vários layouts de página por objeto, por perfil de usuário.

  Page layout: Os layouts de página determinam quais campos são exibidos para seus usuários em um registro. Eles permitem que você adicione campos, seções, links e botões personalizados, além de alguns outros recursos. Muitos layouts de página podem ser criados e aplicados a diferentes grupos de usuários, com o objetivo de criar uma experiência personalizada. Você pode ter um registro de conta, por exemplo. Acme Corp, mas com informações diferentes dependendo do seu perfil de usuário. É importante observar que você só pode aplicar um layout de página a um grupo de usuários por objeto, por tipo de registro. Por exemplo, se você tiver um tipo de registro no objeto Contas, poderá aplicar apenas um layout de página por perfil. Os tipos de registro entram em jogo para estender isso.


</details>

___

## Questão 63
> An administrator needs to create a one-to-many relationship between two objects with limited access to child records. What type of field should the administrator use?

> Um administrador precisa criar um relacionamento um-para-muitos entre dois objetos com acesso limitado a registros filho. Que tipo de campo o administrador deve usar?

A. Roll-up summary (*Um campo de resumo de totalização calcula valores de registros relacionados, como os de uma lista relacionada. Você pode criar um campo de resumo de totalização para exibir um valor em um registro mestre com base nos valores dos campos em um registro de detalhes. O registro de detalhes deve estar relacionado ao mestre por meio de um relacionamento mestre-detalhe.*)

B. Cross object formula (*Uma fórmula de objeto cruzado é uma fórmula que abrange dois objetos relacionados e faz referência a campos de mesclagem nesses objetos. Uma fórmula de objeto cruzado pode fazer referência a campos de mesclagem de um objeto mestre ("pai") se um objeto estiver no lado de detalhes de um relacionamento entre mestre e detalhes.*)

C. Master-detail field (*O relacionamento mestre-detalhe no Salesforce é um relacionamento pai-filho no qual o objeto mestre controla determinados comportamentos do objeto de detalhe. Quando um registro do objeto mestre é excluído, seus registros de detalhes relacionados também são excluídos.*)

D. Lookup field (*Os campos de pesquisa permitem associar dois registros em um relacionamento. Por exemplo, um registro de contato inclui um campo de pesquisa de conta que associa o contato à sua conta.*)

<details>
  <summary>Gabarito:</summary>
  C (checked)
</details>

___

## Questão 64
> Universal Containers has a Contact Lightning record page with a component that shows Linkedin data. The sales team would like to only show this component to sales users when they are on their mobile phones. Which two solutions should the administrator use to fulfill this requirement? Choose 2 answers.

> A Universal Containers tem uma página de registro do Contact Lightning com um componente que mostra os dados do Linkedin. A equipe de vendas gostaria de mostrar esse componente apenas aos usuários de vendas quando estiverem em seus telefones celulares. Quais duas soluções o administrador deve usar para atender a esse requisito?

A. Filter the component visibility with View = Mobile/Tablet

B. Filter the component visibility with User > Role > Name = Sales User

C. Filter the component visibility with User > Profile > Name = Sales User

D. Filter the component visibility with Form Factor = Phone

<details>
  <summary>Gabarito:</summary>
  C e D (checked)
</details>

___

## Questão 65
> An administrator at Universal Containers needs an automated way to delete records based on field values. What automated solution should the administrator use?

A. Flow Builder

B. Automation Studio

C. Process Builder

D. Workflow

<details>
  <summary>Gabarito:</summary>
  A (checked)

  Flow: coleta dados e ajuda a realizar ações em uma organização ou sistema externo. Ele oferece dois tipos de fluxo: fluxo de tela e fluxo iniciado automaticamente. O fluxo de tela é usado quando uma organização deseja coletar dados de seus usuários. Por outro lado, um fluxo iniciado automaticamente é usado para iniciar um fluxo internamente para registrar alterações depois que um usuário clica em um botão. O Flow Builder é a interface declarativa para criar fluxos individuais. Ele pode ser usado para criar lógica semelhante a código sem uma linguagem de programação. Ajuda essencialmente a reduzir o tempo, permitindo que você traga a automação para o ciclo de trabalho. Ele ajuda os administradores do Salesforce a concluir tarefas com eficiência de tempo, alta precisão e pequenos bloqueios. **Os fluxos são diversos, pois não estão vinculados a nenhum objeto ou processo.**

  Workflow: O Salesforce Workflow é um mecanismo de lógica de negócios que permite ao usuário definir algumas regras que automatizarão ações específicas quando um determinado critério ou condição for atendido. Em palavras simples, o Salesforce Workflow executa essencialmente algumas atividades automatizadas quando um determinado padrão ou condição é atendido. O uso do Salesforce Workflow economiza tempo, pois atua como uma solução para avaliar e concluir diferentes processos internos de uma empresa de forma automatizada, proporcionando uma saída muito mais rápida do que o trabalho manual. Essa automação também ajuda na otimização de vários procedimentos sistemáticos. A essência do Workflow está nas regras do Workflow que fornecem critérios específicos que devem ser necessariamente atendidos para acionar ações automatizadas. Por exemplo - Uma alteração de registro, como uma alteração no campo "Hora" pode ser definida para acionar o processo de envio de um alerta de e-mail de notificação automática para um usuário.

  Automation studio: O Automation Studio é um aplicativo do Marketing Cloud usado para executar atividades de gerenciamento de dados e marketing em várias etapas de forma imediata, acionada ou programada. Use a tela de fluxo de trabalho do Automation Studio para criar automações simples ou de várias etapas.
</details>