---
title: Initialize Storage Account
description:
category: SETUP
---

# Initialize the Storage Account

1. Get the name and key of the Storage Account.

   ![](/img/deployment/azure-storage-account.png)
   ​	
   ![Get the name and key of the storage account](/img/deployment/get-name-and-key-of-the-storage-account.png)

2. Execute the **src/Cloud/InitStorage.ps1** PowerShell script. 

   >**Note:** The PowerShell below will create necessary blob containers and queues.
   > Please Use the *Storage Account Name* and *Storage Account Key* associated with your Storage Account.

```PowerShell
./InitStorage.ps1 <<Your Storage Account Name>> <<Your Storage Account Key>>
```