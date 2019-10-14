# AzureWebJobTriggersAndBindings

This code sample demonstrate how Triggers and bindings work in WebJobs in Azure. Here is what this code base is doing

When a message is placed in particular Storage Queue in Azure, Web job will read a Table and write all records in a file that was specified in the message
and then save that as a blob storage on Azure. 

Topics touched:
- Storage Accounts
- Queues
- Blobs
- Web Jobs
