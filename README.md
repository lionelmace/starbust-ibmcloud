# IBM Cloud terraform-based environement for Starbust Data

This repository provides a terraform based IBM Cloud environment to deploy [Starbust Data Solution](https://www.starburst.io/).

This solution was tested in January 2023.

## Technical Requirements

This terraform will provision the following Cloud Services:

* A cluster IKS (IBM Cloud Kubernetes Service) version 1.23 with 3 worker nodes, each 8 vCPU and 32 GB RAM.
* A Postgres managed DB version 11 with 2 replicas, each replica 1GB RAM and 5GB Disk.
* A COS (Cloud Object Storage) with a bucket accessible via S3 API

## More information about Starbust Requirements

* [K8S Requirements](https://docs.starburst.io/latest/k8s/requirements.html)
* [DBaaS Requirements](https://docs.starburst.io/latest/admin/query-logger.html#requirements)
