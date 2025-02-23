# Add-AzureADDirectoryRoleMember

> /directoryRoles/{directoryRole-id}/members/$ref

## Data

+ AAD Command: [Add-AzureADDirectoryRoleMember](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Add-AzureADDirectoryRoleMember)
+ AAD Module: AzureAD
+ Graph Command: [New-MgDirectoryRoleMemberByRef](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/New-MgDirectoryRoleMemberByRef)
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|RoleManagement.ReadWrite.Directory|
|Delegate|Directory.AccessAsUser.All, RoleManagement.ReadWrite.Directory|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|RefObjectId||System.String|||
|ObjectId||System.String|||

