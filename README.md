Hi,

This repository contains a simple NGINX Kubernetes application used to learn and practice Argo CD GitOps workflow.
It includes Kubernetes manifests for deployment and service resources, managed fully through Argo CD.

How it works:-
1- Argo CD monitors this repository.
2- On any commit, Argo CD detects drift.
3- Sync applies manifests directly to the Kubernetes cluster.
4- NGINX deployment becomes live instantly through GitOps.

This project serves as a hands on environment to:-
Understand GitOps fundamentals
Learn Argo CD application configuration
Practice debugging broken deployments
Build confidence managing Kubernetes apps from GitHub

=================================
with default namespace.


<img width="908" height="171" alt="image" src="https://github.com/user-attachments/assets/7a3fe351-d1bb-439b-9527-c63c6e820a0d" />

<img width="1440" height="352" alt="image" src="https://github.com/user-attachments/assets/a7fe12b3-58b0-4ec8-af15-11272392b87b" />

<img width="1437" height="623" alt="image" src="https://github.com/user-attachments/assets/fce75fef-3f9b-41b6-a344-1966e61beaa5" />



==================================
UPDATE namespace to argocd and sync



<img width="1079" height="167" alt="image" src="https://github.com/user-attachments/assets/c23e270a-8bb8-4b7c-891f-c3ab8881d092" />

<img width="1440" height="352" alt="image" src="https://github.com/user-attachments/assets/b78664c0-5c55-4134-85d7-e336cc95bae4" />

<img width="1255" height="559" alt="image" src="https://github.com/user-attachments/assets/d72ca253-e753-4c30-b1c9-fe4b79486530" />

