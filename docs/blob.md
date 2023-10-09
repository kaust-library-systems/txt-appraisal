# Blob Storage

## Main Components

* __Storage Account:__ Every storage account has an unique namespace that is used to generate the address for the blob.
* __Container:__ The container is like a folder on the file system.
* __Blobs:__ Blobs are like files on the file system. In this way, the container holds the blobs.

## Data Access Authorization

For testing purpose use the Shared Key Authorzation.

> Disable _Anonymous public read access_.

1. [Configure Shared Key Authorization](https://learning.oreilly.com/library/view/microsoft-azure-storage/9780137593163/ch01.xhtml#ch01lev1sec3) to the blob.
1. Upload files to the blob.
1. Find PII.

### Blob Lifecycle Management

Decide what happens to the blob after a certain period. Move to a cool tier or delete?

### Static Website Hosting

Create a simple static website to server files in the blob without additional webserver infrastructure.