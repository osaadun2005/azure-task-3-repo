# azure-task-3-repo

To Configure Container Environment Variables For Container App BackEnd



1. **Task Overview**

-  Owner: Intern/ Osa Adun

-  Instructor: Gabriel Mekuleyi
  
-  Start Date :26th October, 2025
  
-  Status: Ongoing
  
- Configure Container Environment

- Create Container App

- Deploy Coniainer App To BackEnd

- Add Variables To BackEnd



 2. **Perequisite**

- Microsoft Azure Platform
  
- Azure CLI installed (az)

- Azure subscription and resource group

- Docker image pushed to a container registry (e.g., Azure Container Registry or Docker Hub)

- Azure PostgreSQL Database


3. **Steps to Deploy**
   
  - Step 1: Login to Azure

    <img width="1080" height="1080" alt="image" src="https://github.com/user-attachments/assets/aaeb9246-0161-4f76-bc70-462986c82fc6" />

   
    <img width="941" height="674" alt="image" src="https://github.com/user-attachments/assets/96f1ca85-fd68-4829-9698-da9d90123aac" />

  - Step 2. Locate Existing Managed Environment Created From Task 2

    ![WhatsApp Image 2025-10-30 at 4 33 20 PM](https://github.com/user-attachments/assets/3b5d0e9a-6caa-412e-9c54-e3d1bd0bf775)


    ![WhatsApp Image 2025-10-30 at 4 36 47 PM](https://github.com/user-attachments/assets/3fde0d5d-52ed-4c26-8fd3-9c490ffb0a4d)



  - Step 3. Go To Apps 

    -  Click Apps
   
       <img width="1280" height="744" alt="image" src="https://github.com/user-attachments/assets/4aca1e00-eb8c-42fa-891f-83c81e204ee1" />

    - + Create 

      <img width="1280" height="653" alt="image" src="https://github.com/user-attachments/assets/d329c44c-b566-4e8d-9daf-4113796cbc7b" />

    - Choose Container App from window drop
   
      <img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/73f8d704-3a26-4b53-8d24-de2200248d05" />

    - Configuration Of Setting for Container App
   
    - Basic Setting
   
      ![WhatsApp Image 2025-10-30 at 5 31 23 PM](https://github.com/user-attachments/assets/0ebec98a-7552-4b9a-9a14-b249c27c4baf)

      <img width="993" height="489" alt="image" src="https://github.com/user-attachments/assets/fe005e22-8e3c-4966-95e9-585d0760e9c6" />


     - Container Setting
   
       <img width="972" height="565" alt="image" src="https://github.com/user-attachments/assets/4cbf55c9-7a81-4c4c-8940-5687cbfb3e6f" />

       <img width="965" height="518" alt="image" src="https://github.com/user-attachments/assets/119061a3-fc5d-4073-bc30-f710efc8510a" />

    - Ingress Setting to port **8000*
   
      <img width="983" height="520" alt="image" src="https://github.com/user-attachments/assets/70447178-8ff1-4f8a-8617-22f47dc6c4cf" />
 
      <img width="988" height="664" alt="image" src="https://github.com/user-attachments/assets/c6ebd35f-2063-4104-bb76-fd68de1c274e" />

    - Tags Seting
   
      ![WhatsApp Image 2025-10-30 at 5 48 36 PM](https://github.com/user-attachments/assets/c72e9c15-9746-49a2-9850-cc6fe38a1e23)


    - Review + Create

      <img width="1003" height="552" alt="image" src="https://github.com/user-attachments/assets/90dbb091-19b3-4bcb-9cdc-10f30de01e0a" />

      <img width="1003" height="687" alt="image" src="https://github.com/user-attachments/assets/abdf6fb1-8bd4-4c31-a4ea-66d017aef2bb" />

      <img width="1008" height="608" alt="image" src="https://github.com/user-attachments/assets/54d6b29a-1516-4921-ad50-621008ae5a36" />


  - 4. Configurationg and Setting of BackEnd App Deployed
   
      - Revisions And Replicas
   
        <img width="956" height="473" alt="image" src="https://github.com/user-attachments/assets/b36506a6-7e2c-4779-8f8f-2ed0ad56db31" />

    - Containers 
   
       ![WhatsApp Image 2025-10-31 at 9 40 34 AM](https://github.com/user-attachments/assets/9b59900f-81f9-4d3e-ab01-46e812dcf6be)

       ![WhatsApp Image 2025-10-31 at 9 49 29 AM](https://github.com/user-attachments/assets/dc9bcef8-3e2c-4c07-82d3-bc4ca16bbc8c)


    - Security

      
       ![WhatsApp Image 2025-10-31 at 9 52 27 AM](https://github.com/user-attachments/assets/6645848b-3c82-416a-9b22-1834df1099c6)

    - Secret: + Add


       ![WhatsApp Image 2025-10-31 at 9 57 26 AM](https://github.com/user-attachments/assets/e133b22b-28de-4472-b970-16e06d101ee9)

       ![WhatsApp Image 2025-11-03 at 3 46 26 PM](https://github.com/user-attachments/assets/0b2acb1a-1aae-4152-beff-c73de2561ef6)




    - Connections
   
     
    - Go To The Created PostgreSQL
   
      ![WhatsApp Image 2025-11-03 at 4 05 51 PM](https://github.com/user-attachments/assets/26fffdc0-ae23-40af-946b-0c1d9359a4e3)

      <img width="1280" height="580" alt="image" src="https://github.com/user-attachments/assets/8711826c-6a56-4211-b4c8-255e457db76a" />

   
    - Choose The Preferred Language Variable

      <img width="1280" height="653" alt="image" src="https://github.com/user-attachments/assets/2adfd5c8-4178-47db-a0af-65c8e1be1798" />
      
      <img width="1280" height="613" alt="image" src="https://github.com/user-attachments/assets/11d37c9b-3172-4323-ae03-1ad79beb7da4" />

    - Value of Secret


      <img width="1280" height="568" alt="image" src="https://github.com/user-attachments/assets/b139e423-9f5c-44ad-8b92-4a631622d704" />

    - Add Secret

      <img width="1280" height="732" alt="image" src="https://github.com/user-attachments/assets/f31c69f5-2138-4985-8bea-11a1ee30e105" />

    - + Add To Create Secret


      <img width="1280" height="885" alt="image" src="https://github.com/user-attachments/assets/468bfdbf-b075-417b-a2f1-abf09a96746b" />


  - Go Back To Application

  -  Container
    <img width="1280" height="589" alt="image" src="https://github.com/user-attachments/assets/ae8cec79-a824-4f45-a720-6e43173caf06" />

  - Environment Variables

    <img width="1280" height="591" alt="image" src="https://github.com/user-attachments/assets/a84ea862-7632-43e7-9e06-c1702b295cb5" />

  - + Add

     <img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/68daf692-403a-4a18-b793-0647089d77c6" />

  - Choose Parameters In Dropbox
  - Name
  - Source
  - Value

  
    <img width="1280" height="600" alt="image" src="https://github.com/user-attachments/assets/7a7ad1db-432a-493f-849f-f5f6cede72b4" />

 - Save And Deploy Revision

   <img width="999" height="556" alt="image" src="https://github.com/user-attachments/assets/b926acf1-e14a-423c-83b2-3802b9b83542" />


   <img width="1280" height="603" alt="image" src="https://github.com/user-attachments/assets/ee8976d1-7856-4f19-aac4-d7955bc7ba80" />
   

   <img width="1280" height="603" alt="image" src="https://github.com/user-attachments/assets/c1b5cf2a-ab9c-48e5-85fb-937065fd8b1b" />

   
 
- Revions And Replicas
  
  <img width="1280" height="489" alt="image" src="https://github.com/user-attachments/assets/200bb565-4d84-4303-8f20-092cb4cbd335" />

  <img width="1280" height="601" alt="image" src="https://github.com/user-attachments/assets/9b87f657-5f6c-48fc-9a4a-1ad5d7b58faa" />


5. **Testing And Benefit**

  - az containerapp logs show --name demo-app --resource-group app-demo-rg
    
  - Verify PostgreSQL access:
    
  - psql -h demo-postgres.postgres.database.azure.com -U pgadmin -d demo_db

  - Simplified deployment of microservices
    
  - Serverless scalability
    
  - Secure connection using managed identities
    
  - Cost-effective and easy to monitor


  

6. **Conclusion**

- Application successfully deployed on Azure Container Apps
  
- PostgreSQL database configured and connected
  
- Container environment variables securely set



    
7. **Resources**

   
- Instructor: Gabriel Mekuleyi

- Azure Portal

- Azure CLI

- Azure Container Apps

- Docker Hub

- GitHub Repository












