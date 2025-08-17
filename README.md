# SC-300
Microsoft Certified: Identity and Access Administrator Associate
Role: Security Engineer

# Introduction
Please note at the time of the documentation I am writing the content may have changed, data may have moved so please refer to the official documentation within Microsoft to see the lastest changes. If this study guide has been helpful, please do show your support and follow me or if you are very generous to donate to kofi page: https://Ko-fi.com/misanzx Thank you

# Useful First Starting Links
- [Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-300)
- [MS Learning](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/?practice-assessment-type=certification)

# Other Notes
As of 2025, the most recent changes are Azure AD is now known as Entra ID, if you see any documentation that references this, please be aware they do change the naming from time to time.

# How Do I Learn?
Get an account, its free to sign up as a 30day free trial and after that, make sure you have set it to not renew which you can still go in to see the blades anf follow along with the learning content.
My plan is to go through each section and make sure I understand how to do a specific function and document how to do it.

# MS Entra ID (formerly known as Azure AD)

First Home page when you log into Entra Admin Center
<img width="1850" height="707" alt="image" src="https://github.com/user-attachments/assets/7a98f283-1d87-48a6-ac1e-a906a2455b6c" />


## Manage rules for dynamic membership groups in Microsoft Entra ID
They can only be:
- user-based
- device-based
> [!Note]
> - Max of 15,000 dynamic membership groups in a single tenant.

<img width="688" height="544" alt="image" src="https://github.com/user-attachments/assets/1c834cc3-5395-46f8-9956-5a8b3f898869" />

- In Entra ID
- Expand the Entra ID blade
- Click on Groups then new groups

> [!Tip]
> - When attriutes of a user or a device changes, the system rechecks the all rules for the dynamic membership groups within the director. You cannot manually add or rember a member of a dynamic membership group.

> [!Warning]
> - You can only create dynamic membership groups for one or the other, but you cannot create a rule for both.
> - You cannnot reference user attributes of the device owner. Device membership can only refrence itself.


### License Requirements
You require on of the following licences:
- Microsoft Entra ID P1
- Intune for Education License

> [!Tip]
> - Licenses are only required once for the users, not the devices.


### Rule builder in the Azure portal
MS Entra ID gives you a rule builder to make it easier to create your dynamic grouping.
- Supports up tp 5 expressions
- If it does not support the rule, use the custom rule by adding an expression.
<img width="839" height="487" alt="image" src="https://github.com/user-attachments/assets/609a8d04-853d-4e49-893d-7b40ff4c90f7" />

For more information about Dynamic membership groups please go here: https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership
