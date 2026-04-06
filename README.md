\# Persistent Storage in Kubernetes Using AWS EBS CSI Driver



\## Project Overview

This project demonstrates persistent storage in Kubernetes using the AWS EBS CSI Driver on Amazon EKS.



By default, Kubernetes pods are ephemeral, meaning data inside the pod can be lost if the pod is deleted or restarted. To solve this, this project uses AWS Elastic Block Store (EBS) with Kubernetes Persistent Volumes.



\## Objective

The objective of this project is to deploy a MySQL application on Amazon EKS with persistent storage and prove that the data remains available even after pod deletion and recreation.



\## Technologies Used

\- Amazon EKS

\- AWS EBS

\- AWS EBS CSI Driver

\- Kubernetes

\- kubectl

\- eksctl

\- MySQL

\- YAML



\## Project Files

\- `storageclass.yaml` - Defines dynamic storage provisioning

\- `pvc.yaml` - Requests persistent storage for the application

\- `mysql-deployment.yaml` - Deploys MySQL with persistent volume mounting

\- `mysql-service.yaml` - Exposes the MySQL service inside the cluster



\## Workflow

1\. Created Amazon EKS cluster

2\. Installed AWS EBS CSI Driver

3\. Created StorageClass

4\. Created Persistent Volume Claim

5\. Deployed MySQL using persistent storage

6\. Inserted sample data

7\. Deleted the pod

8\. Verified that data persisted after pod recreation



\## Screenshots

Screenshots of cluster setup, storage resources, MySQL data, pod deletion, and persistence verification are available in the `screenshots` folder.



\## Result

The project successfully proves that Kubernetes persistent storage using AWS EBS CSI Driver retains data even after pod deletion.



\## Author

Sindhu Sahithi  

Sreenidhi Institute of Science and Technology

