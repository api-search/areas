---
layout: area
slug: cloud-storage
name: Cloud Storage
description: Cloud Storage is a topic profile in the API Evangelist Network covering the major cloud and S3-compatible object, file, and block storage APIs. The topic indexes the canonical hyperscaler offerings (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside S3-compatible alternatives (Wasabi, Backblaze B2, MinIO, Cloudflare R2, IBM Cloud Object Storage, DigitalOcean Spaces, Linode Object Storage), file storage (Amazon EFS, Google Filestore, Azure Files), and block storage (Amazon EBS, Google Persistent Disk, Azure Managed Disks). It is the parent topic to more specialized profiles in the network such as cloud-storage-and-data-acquisition.
tags:
- Block Storage
- Cloud
- Cloud Storage
- File Storage
- Object Storage
- S3 Compatible
- Storage
resource_count: 11
provider_count: 231
resources:
- name: Amazon S3
  description: Amazon Simple Storage Service (S3) is the de-facto standard cloud object store. Its REST API at s3.amazonaws.com supports buckets, objects, multipart uploads, lifecycle rules, server- side encryption, replication, and event notifications.
  url: https://aws.amazon.com/s3/
  tags:
  - AWS
  - Object Storage
  - REST
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html
- name: Google Cloud Storage
  description: Google Cloud Storage provides unified object storage with the JSON API at storage.googleapis.com. It supports buckets, objects, IAM, customer-managed encryption keys, and Pub/Sub change notifications.
  url: https://cloud.google.com/storage
  tags:
  - GCP
  - Object Storage
  - REST
  properties:
  - type: Documentation
    url: https://cloud.google.com/storage/docs/json_api/v1
- name: Azure Blob Storage
  description: Azure Blob Storage offers block, append, and page blob types through the Blob service REST API. It supports access tiers, lifecycle management, lease semantics, and Event Grid integration for change notifications.
  url: https://azure.microsoft.com/en-us/services/storage/blobs/
  tags:
  - Azure
  - Object Storage
  - REST
  properties:
  - type: Documentation
    url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api
- name: Cloudflare R2
  description: Cloudflare R2 is a zero-egress-fee object store with an S3-compatible API. R2 buckets are accessed at <accountid>.r2.cloudflarestorage.com and integrate with Cloudflare Workers for edge-computed access patterns.
  url: https://www.cloudflare.com/products/r2/
  tags:
  - Cloudflare
  - Egress-Free
  - Object Storage
  - S3 Compatible
  properties:
  - type: Documentation
    url: https://developers.cloudflare.com/r2/api/
- name: Backblaze B2 Cloud Storage
  description: Backblaze B2 Cloud Storage provides low-cost object storage with a native B2 API and an S3-compatible API. It is widely used as a backup and media storage target.
  url: https://www.backblaze.com/cloud-storage
  tags:
  - Backblaze
  - Object Storage
  - S3 Compatible
  properties:
  - type: Documentation
    url: https://www.backblaze.com/apidocs
- name: Wasabi Hot Cloud Storage
  description: Wasabi Hot Cloud Storage offers S3-compatible object storage at a flat per-TB price with no egress or API request fees. It is positioned as a hot tier replacement for S3.
  url: https://wasabi.com/
  tags:
  - Object Storage
  - S3 Compatible
  - Wasabi
  properties:
  - type: Documentation
    url: https://docs.wasabi.com/v1/docs/api-guide
- name: MinIO
  description: MinIO is a high-performance, S3-compatible object store designed for AI/ML, analytics, and on-premises private cloud use cases. It can be deployed standalone or as a distributed erasure-coded cluster.
  url: https://min.io/
  tags:
  - Object Storage
  - On-Premises
  - Open Source
  - S3 Compatible
  properties:
  - type: Documentation
    url: https://min.io/docs/minio/linux/developers/minio-drivers.html
- name: IBM Cloud Object Storage
  description: IBM Cloud Object Storage exposes an S3-compatible API and Aspera high-speed transfer integrations. It supports SmartTier placement and Immutable Object Storage.
  url: https://www.ibm.com/cloud/object-storage
  tags:
  - IBM
  - Object Storage
  - S3 Compatible
  properties:
  - type: Documentation
    url: https://cloud.ibm.com/docs/cloud-object-storage?topic=cloud-object-storage-compatibility-api
- name: DigitalOcean Spaces
  description: DigitalOcean Spaces is an S3-compatible object store with a built-in CDN, designed for developers building on the DigitalOcean platform.
  url: https://www.digitalocean.com/products/spaces
  tags:
  - DigitalOcean
  - Object Storage
  - S3 Compatible
  properties:
  - type: Documentation
    url: https://docs.digitalocean.com/reference/api/spaces-api/
- name: Amazon EFS
  description: Amazon Elastic File System (EFS) is a managed NFS file system for Linux workloads. The control-plane API manages file systems, mount targets, lifecycle policies, and access points.
  url: https://aws.amazon.com/efs/
  tags:
  - AWS
  - File Storage
  - NFS
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/efs/latest/ug/api-reference.html
- name: Amazon EBS
  description: Amazon Elastic Block Store (EBS) provides persistent block volumes for EC2. The control-plane API manages volumes, snapshots, encryption, and direct snapshot access.
  url: https://aws.amazon.com/ebs/
  tags:
  - AWS
  - Block Storage
  - Volumes
  properties:
  - type: Documentation
    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_Operations.html
providers:
- slug: cloud-storage
  name: Cloud Storage
  description: Cloud Storage is a topic profile in the API Evangelist Network covering the major cloud and S3-compatible object, file, and block storage APIs. The topic indexes the canonical hyperscaler offerings (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside S3-compatible alternatives (Wasabi, B…
  api_count: 11
  score_band: minimal
  score_composite: 15.9
  shared: 7
- slug: pure-storage
  name: Pure Storage
  description: Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet management, along with Portworx for Kubernetes data services…
  api_count: 4
  score_band: developing
  score_composite: 45.8
  shared: 5
- slug: gcp-cloud-storage
  name: Google Cloud Storage
  description: Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.
  api_count: 2
  score_band: developing
  score_composite: 46.8
  shared: 4
- slug: rook
  name: Rook
  description: Rook is a CNCF graduated cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for Ceph distributed storage systems to natively integrate with cloud-native environments. It automates the deployment, configuration, provisioning, scaling, upgrading, and moni…
  api_count: 4
  score_band: developing
  score_composite: 45.9
  shared: 4
- slug: ceph
  name: Ceph
  description: Ceph is an open source, distributed storage platform that provides unified object, block, and file storage on commodity hardware with no single point of failure. The Ceph Manager (ceph-mgr) ships with a RESTful API that exposes the same operations available in the Ceph Dashboard for managing pools,…
  api_count: 1
  score_band: minimal
  score_composite: 17.9
  shared: 4
- slug: backblaze
  name: Backblaze
  description: Backblaze is a cloud storage and data backup provider offering B2 Cloud Storage - a low-cost, S3-compatible object storage service. Backblaze provides both a native B2 API and an S3-compatible API, enabling developers to build applications that store unlimited data at a fraction of major cloud prov…
  api_count: 2
  score_band: strong
  score_composite: 61.2
  shared: 3
- slug: azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 3
- slug: microsoft-azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 3
  score_band: developing
  score_composite: 51.1
  shared: 3
- slug: aws-s3
  name: Amazon S3 API
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance for storing and retrieving any amount of data.
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 3
- slug: cubefs
  name: CubeFS
  description: CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot and cold data tiers, and is widely used to back cloud-native…
  api_count: 2
  score_band: developing
  score_composite: 47.9
  shared: 3
- slug: tigris-data
  name: Tigris
  description: Tigris is a globally distributed, multi-cloud, S3-compatible object storage service. Data is automatically placed close to where it is read for low latency worldwide, with no egress fees. The storage API speaks the AWS S3 protocol at https://t3.storage.dev (formerly fly.storage.tigris.dev) so exist…
  api_count: 6
  score_band: thin
  score_composite: 33.6
  shared: 3
- slug: wasabi
  name: Wasabi
  description: Wasabi Hot Cloud Storage is an S3-compatible object storage service offering a REST API that mirrors the Amazon S3 API for storing, retrieving, and managing objects and buckets. Wasabi provides always-consistent storage at lower cost than hyperscale providers, with no egress fees, no API request fe…
  api_count: 4
  score_band: thin
  score_composite: 30.1
  shared: 3
- slug: azure-file-storage
  name: Azure Files
  description: Azure Files is a fully managed cloud file share service from Microsoft Azure that provides hosted SMB and NFS file shares accessible from cloud and on-premises clients using standard file system protocols and the FileREST HTTPS API. It supports identity-based authentication via Active Directory and…
  api_count: 2
  score_band: minimal
  score_composite: 19.3
  shared: 3
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 54
  score_band: strong
  score_composite: 65.6
  shared: 2
- slug: amazon-efs
  name: Amazon EFS
  description: Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files.
  api_count: 1
  score_band: strong
  score_composite: 61.8
  shared: 2
- slug: amazon-ebs
  name: Amazon EBS
  description: Amazon Elastic Block Store (EBS) provides persistent block storage volumes for use with Amazon EC2 instances. EBS volumes are highly available and reliable storage volumes that can be attached to any running instance in the same Availability Zone, offering consistent and low-latency performance for…
  api_count: 1
  score_band: strong
  score_composite: 60.9
  shared: 2
- slug: amazon-s3
  name: Amazon S3
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
  api_count: 3
  score_band: developing
  score_composite: 58.7
  shared: 2
- slug: amazon-storage-gateway
  name: Amazon Storage Gateway
  description: AWS Storage Gateway is a hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage. It seamlessly connects on-premises environments to AWS cloud storage, providing low-latency data access with local caching.
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: google-cloud-storage
  name: Google Cloud Storage
  description: Google Cloud Storage is a managed service for storing unstructured data such as images, videos, backups, and other binary or text objects. It provides a single API for accessing both simple storage and highly available, globally redundant storage, with automatic data encryption, built-in redundancy…
  api_count: 1
  score_band: developing
  score_composite: 52.6
  shared: 2
- slug: microsoft-azure-queue-storage
  name: Azure Queue Storage
  description: Azure Queue Storage is a Microsoft cloud service for storing large numbers of messages, enabling decoupled and asynchronous communication between application components. Messages can be accessed via authenticated HTTP/HTTPS calls and support visibility timeouts, peeking, and metadata for reliable p…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 2
- slug: google-drive
  name: Google Drive
  description: The Google Drive API allows developers to integrate with Google Drive to create, read, update, and delete files and folders stored in Google Drive. The v3 REST API supports file metadata operations, content upload and download, folder hierarchies, sharing and permissions, and search across a user's…
  api_count: 1
  score_band: developing
  score_composite: 45.1
  shared: 2
- slug: dell-technologies
  name: Dell Technologies
  description: Dell Technologies is a global Fortune 500 technology company that designs, develops, manufactures, and supports a wide range of computing products, including PCs, servers, storage, networking equipment, and software services. Dell publishes a developer platform exposing APIs and SDKs for managing P…
  api_count: 1
  score_band: thin
  score_composite: 43.2
  shared: 2
- slug: microsoft-onedrive
  name: Microsoft OneDrive
  description: Microsoft OneDrive is a cloud-based file storage and synchronization service. It provides APIs through Microsoft Graph for accessing, managing, and sharing files and folders stored in OneDrive personal and OneDrive for Business.
  api_count: 2
  score_band: thin
  score_composite: 42.7
  shared: 2
- slug: filebase
  name: Filebase
  description: Filebase is an S3-compatible object storage and IPFS pinning platform that combines familiar cloud storage APIs with decentralized, blockchain-backed infrastructure. Developers can store, manage, and pin files to IPFS using standard S3 tooling, a dedicated IPFS Pinning Service API, and an IPFS RPC…
  api_count: 4
  score_band: thin
  score_composite: 42.2
  shared: 2
related:
- slug: cloud-storage-and-data-acquisition
  name: Cloud Storage and Data Acquisition
  shared: 2
- slug: cloud
  name: Cloud
  shared: 1
repo: https://github.com/api-evangelist/cloud-storage
overview: 'Cloud Storage on the [APIs.io](https://apis.io/) network is a curated area collecting 11 resources — specifications, tools, and documentation — for this subject.


  24 providers on the network work in this area, including Cloud Storage, Pure Storage, Google Cloud Storage, Rook, Ceph, Backblaze, and 18 more — each links out to that provider''s APIs, schemas, and governance artifacts.


  Related areas: Cloud Storage and Data Acquisition and Cloud. Browse every area at [areas.apis.io](https://apis.io/areas/).'
---
