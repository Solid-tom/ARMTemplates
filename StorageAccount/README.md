# Storage Account
This templates provisions a storage account using the default setting for Account kind 'StorageV2' and type 'Standard_LRS'.

Enable HNS if required to use Hierarchical Namespace for Azure Data Lake. 

Configuration
- Allow Blob public access disabled
- Minimum TLS 1.2
- Blob access tier Hot

Networking - VNET and Subnet required for the settings below
- Allow access from selected networks
- Private endpoint connection

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2FSolid-tom%2FARMTemplates%2Fblob%2Fmain%2FStorageAccount%2Fstorage-acc-template.json)
