


# Azure Blob Storage

## why this topic matters as it relates to what Iam studying in this module?

.NET developers should pay attention to this, as the Azure Blob Storage client library for .NET allows connections to Azure Blob Storage and operations on containers, blobs, and other features. As a result, we will be able to store large amounts of unstructured data, such as images, documents, videos, audio, log files, etc.


## Summary


Azure provides cloud storage as one of its primary services. In this way, we are able to store different types of artifacts in the Cloud. This includes Tables, Queues, Files, and Containers. Among the types of files that can be stored in containers are text files, images, video files, etc. (Blobs) can be stored in containers.


## Storage accounts

You may create a storage account in Azure to house your data in a unique namespace. The address of every object you store in Azure Storage includes your unique account name. Your storage account's base address is formed by the combination of your account name and the Blob Storage endpoint.



## Blob storage is designed for :
- Serving images or documents directly to a browser.
- Writing to log files.
- Streaming video and audio.
- Storing files for distributed access.
- Storing data for backup and restore, disaster recovery, and archiving.
- Storing data for analysis by an on-premises or Azure-hosted service.



## Blobs
### Azure Storage supports three types of blobs:

- Block blobs are used to store binary and text data. Each block blob consists of a set of data blocks that can be managed separately. A block blob can store up to about 190.7 terabytes of data.

- Append blobs are composed of blocks similar to block blobs, but are optimized for append operations. The use of append blobs is ideal for scenarios such as logging data collected from virtual machines.

- A page blob consists of random access files that may have a size of up to 8 TB. In Azure, page blobs serve as disks for virtual machines and store virtual hard drive (VHD) files.




## Benefits of Azure Storage

- It is possible for you to encrypt your data and control who has access to it through an Azure storage account.

- Through Azure storage, you keep your data safe and accessible by replicating it across different locations.

- You can store and process large amounts of data using an Azure storage account, and Azure manages the hardware for you.

