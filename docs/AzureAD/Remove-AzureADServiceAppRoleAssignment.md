# Remove-AzureADServiceAppRoleAssignment

> /servicePrincipals/{servicePrincipal-id}/appRoleAssignments/{appRoleAssignment-id}

## Data

+ AAD Command: [Remove-AzureADServiceAppRoleAssignment](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Remove-AzureADServiceAppRoleAssignment)
+ AAD Module: AzureAD
+ Graph Command: [Remove-MgServicePrincipalAppRoleAssignment](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/Remove-MgServicePrincipalAppRoleAssignment)
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|AppRoleAssignment.ReadWrite.All|
|Delegate|AppRoleAssignment.ReadWrite.All, Directory.AccessAsUser.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|AppRoleAssignmentId|AppRoleAssignmentId|System.String|System.String||
|ObjectId||System.String|||

