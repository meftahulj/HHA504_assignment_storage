# HHA504_assignment_storage
## Upload Files Using the GUI
### *Azure Blob Storage*

![Azure Storage](https://github.com/user-attachments/assets/6690a0fc-c296-41a9-8c75-9d0d149b3a72)
![Azure Blob]()
### *GCP Blob Storage*
![GCP Storage]()
![GCP Blob]()
# Explore Storage Features
### *Azure*
Azure offers robust access control features, including Shared Access Signatures (SAS), which provide limited access to Blob storage resources without exposing the account key. Data security is a priority, with automatic encryption for data stored in Blob storage, and users can manage their own encryption keys through Azure Key Vault. Data in transit is also encrypted using HTTPS to ensure confidentiality. Azure’s data management system includes Blob storage tiers: the hot tier for frequently accessed data, the cool tier for infrequently accessed data with lower storage costs but higher retrieval costs, and the archive tier for data that is rarely accessed and intended for long-term storage.

### *GCP*
Google Cloud Platform (GCP) uses Identity and Access Management (IAM) to control access to resources, alongside Access Control Lists (ACLs) for more granular control over buckets and objects. GCP also offers the ability to generate signed URLs for temporary access to specific objects. Data in Google Cloud Storage (GCS) is automatically encrypted with Google-managed keys, and bucket policies can be used to enforce access conditions. For data management, GCP provides lifecycle management, allowing users to set rules to automate actions like deleting objects after a certain period or moving them to different storage classes. These classes include standard for frequently accessed data, nearline for data accessed less than once a month, coldline for data accessed less than once a year, and archive for rarely accessed data meant for long-term storage.
