# Docker_WebApp_Assignment 
Containerized Web Application with PostgreSQL using Docker Compose and IPvlan
Project Assignment 1
Containerization and DevOps

This project demonstrates a containerized web application using FastAPI and PostgreSQL. Both services run in separate Docker containers and are orchestrated using Docker Compose. Networking is implemented using IPvlan with static IP addresses.

     Project Architecture
    
   <img width="1205" height="401" alt="image" src="https://github.com/user-attachments/assets/1def231f-c23c-4b48-b436-25cc73a579d0" />

     Prerequisites
    
     Verify Docker installation.
      
 <img width="1217" height="91" alt="image" src="https://github.com/user-attachments/assets/580ac1b2-5eb4-4ec3-a305-7fe9955d4b06" />

 Output

 <img width="946" height="142" alt="image" src="https://github.com/user-attachments/assets/21304eb3-3dae-4371-a4c2-abc1420c0a37" />

 Step 1 — Create Project Directory
 <img width="1232" height="90" alt="image" src="https://github.com/user-attachments/assets/d3a97e45-6048-4eae-a568-a717ce15b26a" />

Output

<img width="651" height="47" alt="image" src="https://github.com/user-attachments/assets/b8fe6aad-b9ca-4090-9a79-d0ecadb6b7e1" />

Step 2 — Create Backend and Database Directories
<img width="1238" height="122" alt="image" src="https://github.com/user-attachments/assets/aa1f5385-74bf-4d92-9533-598509ea6cba" />

Output

<img width="1225" height="57" alt="image" src="https://github.com/user-attachments/assets/d70fb365-925d-4842-8344-f3b6c619f42d" />

Step 3 — Backend Files

Backend directory contains:
<img width="1229" height="161" alt="image" src="https://github.com/user-attachments/assets/17cb3839-c3fe-42eb-a661-9a76882cfc6d" />

Output

<img width="922" height="102" alt="image" src="https://github.com/user-attachments/assets/a1520161-76fe-4dea-bed7-cd77bede87b4" />

Step 4 — Database Files

Database directory contains:

<img width="1195" height="145" alt="image" src="https://github.com/user-attachments/assets/7fd4ca4a-6103-4731-838f-39d4fe259d32" />

Output

<img width="902" height="72" alt="image" src="https://github.com/user-attachments/assets/efdebc4a-8fa9-47fe-8f07-f966330686b2" />

Step 5 — Create IPvlan Network

<img width="1135" height="57" alt="image" src="https://github.com/user-attachments/assets/ff982644-a891-4f38-9836-ac4c3391b60f" />

Output

<img width="1238" height="65" alt="image" src="https://github.com/user-attachments/assets/0b45429c-7e9f-4dc0-bfda-b9c84cb29a62" />

Step 6 — Verify Docker Networks

<img width="1225" height="75" alt="image" src="https://github.com/user-attachments/assets/7b7c8d2b-a9b9-4caf-823b-4109dcaf52f7" />

Output

<img width="1213" height="174" alt="image" src="https://github.com/user-attachments/assets/0655447f-b3ef-4017-95f8-9abf7c35b8ef" />

Step 7 — Inspect Network

<img width="1207" height="68" alt="image" src="https://github.com/user-attachments/assets/361d0291-93ff-473c-a9f1-194d93c09b75" />

Output

<img width="1232" height="392" alt="image" src="https://github.com/user-attachments/assets/86e94e46-1ff3-4dc8-81aa-5f9c9e66f316" />

Step 8 — Build and Start Containers

<img width="1173" height="55" alt="image" src="https://github.com/user-attachments/assets/01046023-6ad0-4695-b68b-7367957b79bc" />

Output
<img width="1241" height="255" alt="image" src="https://github.com/user-attachments/assets/a8ed4ec9-dd5a-43e5-b66b-3c999267585e" />

Step 9 — Verify Running Containers

<img width="1200" height="72" alt="image" src="https://github.com/user-attachments/assets/4235aa53-555a-43ce-a4f8-2665f3008c28" />

Output

<img width="1203" height="92" alt="image" src="https://github.com/user-attachments/assets/92cdff45-218f-4c4a-8c6c-895ee05e8861" />

Step 10 — Verify Container IP Addresses

<img width="1246" height="96" alt="image" src="https://github.com/user-attachments/assets/c5e13d48-8762-4de7-afcd-99ccffc4838a" />

Output

<img width="1222" height="117" alt="image" src="https://github.com/user-attachments/assets/945517ca-8ee5-4834-a11b-e48a76d63a43" />

Step 11 — Test API: Health Endpoint

Request

<img width="1222" height="50" alt="image" src="https://github.com/user-attachments/assets/0b493f40-44c3-40cc-8c7f-ea14bee54134" />

Response

<img width="1237" height="122" alt="image" src="https://github.com/user-attachments/assets/8a4519e3-3389-4a7f-ad17-b89732be6313" />


























    

