# New-AzureADServicePrincipal

> /servicePrincipals

## Data

+ AAD Command: [New-AzureADServicePrincipal](https://docs.microsoft.com/en-us/powershell/module/AzureADPreview/New-AzureADServicePrincipal)
+ AAD Module: AzureADPreview
+ Graph Command: [New-MgServicePrincipal](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/New-MgServicePrincipal)
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Application.ReadWrite.All|
|Delegate|Application.ReadWrite.All, Directory.AccessAsUser.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|DisplayName|DisplayName|System.String|System.String||
|AppId|AppId|System.String|System.String||
|AlternativeNames|AlternativeNames|System.Collections.Generic.List/System.String|System.String[]||
|ErrorUrl||System.String|||
|ServicePrincipalType|ServicePrincipalType|System.String|System.String||
|Homepage|Homepage|System.String|System.String||
|AppRoleAssignmentRequired|AppRoleAssignmentRequired|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|LogoutUrl|LogoutUrl|System.String|System.String||
|KeyCredentials|KeyCredentials|System.Collections.Generic.List/Microsoft.Open.AzureAD.Model.KeyCredential|Microsoft.Graph.PowerShell.Models.IMicrosoftGraphKeyCredential[]||
|PasswordCredentials|PasswordCredentials|System.Collections.Generic.List/Microsoft.Open.AzureAD.Model.PasswordCredential|Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPasswordCredential[]||
|SamlMetadataUrl||System.String|||
|Tags|Tags|System.Collections.Generic.List/System.String|System.String[]||
|ServicePrincipalNames|ServicePrincipalNames|System.Collections.Generic.List/System.String|System.String[]||
|ReplyUrls|ReplyUrls|System.Collections.Generic.List/System.String|System.String[]||
|PublisherName||System.String|||
|AccountEnabled|AccountEnabled|System.String|System.Management.Automation.SwitchParameter||

