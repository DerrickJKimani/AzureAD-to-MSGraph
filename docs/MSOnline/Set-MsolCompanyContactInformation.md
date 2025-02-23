# Set-MsolCompanyContactInformation

> /organization/{organization-id}

## Data

+ AAD Command: [Set-MsolCompanyContactInformation](https://docs.microsoft.com/en-us/powershell/module/MSOnline/Set-MsolCompanyContactInformation)
+ AAD Module: MSOnline
+ Graph Command: [Update-MgOrganization](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/Update-MgOrganization)
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|DeviceManagementServiceConfig.ReadWrite.All, Organization.ReadWrite.All|
|Delegate|DeviceManagementServiceConfig.ReadWrite.All, Directory.AccessAsUser.All, Organization.ReadWrite.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|MarketingNotificationEmails|MarketingNotificationEmails|System.String[]|System.String[]||
|TechnicalNotificationEmails||System.String[]|||
|TenantId||System.Nullable/System.Guid|||

