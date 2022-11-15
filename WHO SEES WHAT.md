# Permission sets x Profile

User permissions and access settings are specified in profiles and permission sets. To use them effectively, understand the differences between profiles and permission sets.

Every user is assigned only one profile, but can also have multiple permission sets. When determining access for your users, use profiles to assign the minimum permissions and access settings for specific groups of users. Then use permission sets to grant more permissions as needed.

Users can have only one profile but, depending on the Salesforce edition, they can have multiple permission sets. If a permission isn’t enabled in a profile but is enabled in a permission set, users with that profile and permission set have the permission. For example, if Manage Password Policies isn’t enabled in a user’s profile but is enabled in one of their permission sets, they can manage password policies.

User permissions, Object permissions, Field permissions

## Profile
Profiles define how users access objects and data, and what they can do within the application. When you create users, you assign a profile to each one.
Exemplos de standard profiles: **SALES USER**, System Administrator, Read Only, etc.

## Permission sets (Conjunto de permissão)
A permission set is a collection of settings and permissions that give users access to various tools and functions. Permission sets extend users’ functional access without changing their profiles.
Users can have only one profile but, depending on the Salesforce edition, they can have multiple permission sets. You can assign permission sets to various types of users, regardless of their profiles.

Create permission sets to grant access among logical groupings of users, regardless of their primary job function. For example, let’s say you have several users who must delete and transfer leads. You can create a permission set based on the tasks that these users must perform and include the permission set within permission set groups based on job functions.

# Role Hierarchy
Salesforce offers a user role hierarchy that you can use with sharing settings to determine the levels of access that users have to your Salesforce org’s data. Roles within the hierarchy affect access on key components such as records and reports.

Users at any role level can view, edit, and report on all data that’s owned by or shared with users below them in their role hierarchy, unless your org’s sharing model for an object specifies otherwise.

- For each role in your hierarchy, Salesforce automatically creates *sharing groups*, which you can use in **sharing rules and manual sharing**.
- If Enterprise Territory Management is enabled for your org, each territory has sharing groups.

## Manual Sharing
Manual sharing gives other users access to certain types of records, including accounts, contacts, and leads.

Sometimes, granting access to one record includes access to all its associated records. For example, if you grant another user access to an account, the user automatically has access to all the opportunities and cases associated with that account.

## Sharing rules
Da acesso ADICIONAL
Use sharing rules to extend sharing access to users in public groups, roles, or territories. Sharing rules give particular users greater access by making automatic exceptions to your org-wide sharing settings.

- **Owner-Based Sharing Rules:**
An owner-based sharing rule opens access to records owned by certain users. For example, a company’s sales managers need to see opportunities owned by sales managers in a different region. The U.S. sales manager could give the APAC sales manager access to the opportunities owned by the U.S. team using owner-based sharing.

- **Criteria-Based Sharing Rules:**
A criteria-based sharing rule determines with whom to share records **based on field values.** For example, you have a custom object for job applications, with a custom picklist field named “Department.” A criteria-based sharing rule could share all job applications in which the Department field is set to “IT” with all IT managers in your organization.

>  Sharing set X Sharing rules
>> Os Sharing set usam perfis (ex. usuário padrão, administrador etc) para fornecer acesso de registro a um grupo de usuários, diferentemente das sharing rules, que usam funções (ex. sales users) e grupos públicos

## Page layout

Controla o layout da página ou como a página aparece

## DESABILITAR ACESSO EM UM APPLICATION FOR A GROUP OF USERS

Utiliza profile
