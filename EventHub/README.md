# EventHub ARM Template

This deploys an eventhub resource with the following secuirty settings:

Configuration
- Minimum TLS 1.2
- Public access disabled

Networking - VNET and Subnet required for the settings below
- Allow access from selected networks
- Private endpoint connection
  
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSolid-tom%2FARMTemplates%2Fmain%2FEventHub%2Fevent-hub-template.json)
