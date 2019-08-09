---
page_type: sample
languages: java
products: azure
services: Appservice
platforms: java
author: yaohaizh
---

## Getting Started with Appservice - Manage Web App With Authentication - in Java ##


  Azure App Service sample for managing authentication for web apps.
   - Create 4 web apps under the same new app service plan with:
     - Active Directory login for 1
     - Facebook login for 2
     - Google login for 3
     - Microsoft login for 4
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-authentication-for-web-apps.git

    cd app-service-java-manage-authentication-for-web-apps

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.