# Get-AzureADApplication

> /applications | /applications/{application-id}

## Data

+ AAD Command: [Get-AzureADApplication](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Get-AzureADApplication)
+ AAD Module: AzureAD
+ Graph Command: [Get-MgApplication](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/Get-MgApplication)
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Application.Read.All, Application.ReadWrite.All, Directory.Read.All|
|Delegate|Application.Read.All, Application.ReadWrite.All, Directory.AccessAsUser.All, Directory.Read.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|ObjectId||System.String|||
|Filter|Filter|System.String|System.String||
|Top|Top|System.Nullable/System.Int32|System.Int32||
|SearchString||System.String|||
|All|All|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||

