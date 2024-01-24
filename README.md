# azure-mlops
a quick notes repo for applying azure-mlops-v2 accelerator. hope to supplement what's been already provided by azure

# Conceptual Architecture 
consists of 4 component:
1. Data Estate (the  data lakehouse)  - refer to #1
2. MLOps Administration and Setup (Data DevOps) refer to #2 , #4
3. Model Development (inner loop) (Dev environment)  refer to #3
4. Model Deployment (outer loop) (Test/PROD environment) refer to #5, #6, #7, #8, #9, #10
    * #6/ #7- Test/Prod Environment
    * #8 - monitoring , consist of both 1) Model & Data Monitoring; 2) Infrastructure  & Resource Monitorin
    * #9 - Trigger & Notification for model training --> Continuous Training / Re-training / data issue investigtion/ model issue investigation
    * #10 - Trigger for Infra support --> infra issue upport 

![mlops conceptual architecture ](https://github.com/Azure/mlops-v2/blob/main/documentation/architecture/media/AzureML_CML_Architecture.png)https://github.com/Azure/mlops-v2/blob/main/documentation/architecture/media/AzureML_CML_Architecture.png)
