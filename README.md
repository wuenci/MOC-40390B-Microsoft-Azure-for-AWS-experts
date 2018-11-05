# MOC 40390B Microsoft Azure for AWS experts

### Software aggiuntivo per amministrare i servizi di Microsoft Azure

Oltre al portale WEB (http://portal.azure.com) c'è la possibilità amministrare  Microsoft Azure tramite altri programmi come: 

 - Storage Explorer for Azure
   - https://azure.microsoft.com/en-us/features/storage-explorer
 - Azure CLI
   - https://docs.microsoft.com/en-us/cli/azure/install-azure-cli
 - PowerShell Azure Module
   - Install-Module -Name AzureRM -AllowClobber

> Il modulo di Powershell richiede l'installazione di Nuget per Powershell. È possibile installare Nuget automaticamente oppure manualmente con il comando seguente:  
- `Install-PackageProvider -Name NuGet -MinimumVersion 2.8.5.201 -Force`  
_La DLL verrà installa nella cartella: "C:\Program Files\PackageManagement\ProviderAssemblies"_

