---
services: Managed
platforms: .Net
author: anuchandy
---

# Getting Started with Managed - Create Virtual Machine Using Specialized Disk From Vhd - in .Net #

          Azure Compute sample for managing virtual machines.
           - Create an un-managed virtual machine from PIR image with data disks
           - Create managed disks from specialized un-managed OS and Data disk of virtual machine
           - Create a virtual machine by attaching the managed disks
           - Get SAS Uri to the virtual machine's managed disks


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-net/blob/Fluent/AUTH.md).

    git clone https://github.com/Azure-Samples/managed-disk-dotnet-create-virtual-machine-using-specialized-disk-from-VHD.git

    cd managed-disk-dotnet-create-virtual-machine-using-specialized-disk-from-VHD

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.