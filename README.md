# springboot-azureSQL

Addition to the tutorial

1) Need to create a firewall connection between Azure App Service and Azure SQL Database.
Step to be followed is mentioned in
https://docs.microsoft.com/en-us/azure/mysql/howto-connect-webapp
2) For Testing, we can open access to all Azure Services 
    1) Open Azure SQL DB
    2) Connection Security -> Allow access to Azure services 
3) When implementing a PROD ready model, need to implement the firewall rules.
