# Docker_WebApp_Assignment
Containerized Web Application with PostgreSQL using Docker Compose and IPvlan

Project Assignment 1
Containerization and DevOps

This project demonstrates a containerized web application using FastAPI and PostgreSQL. Both services run in separate Docker containers and are orchestrated using Docker Compose. Networking is implemented using IPvlan with static IP addresses.

Project Architecture

<img width="657" height="301" alt="image" src="https://github.com/user-attachments/assets/4ac1bcad-6173-4c26-ab16-4e2a54158e0c" />

Prerequisites

Verify Docker installation.

<img width="955" height="67" alt="image" src="https://github.com/user-attachments/assets/cd93f55b-fc6b-4ba6-bc7b-bef8b1fcc1dc" />

Output

<img width="716" height="116" alt="image" src="https://github.com/user-attachments/assets/5964bf5f-d96d-4b70-8629-7535bdb13615" />

Step 1 — Create Project Directory

<img width="728" height="62" alt="image" src="https://github.com/user-attachments/assets/1ec57f17-2cb4-4d8b-ad74-cb3e2f8e996a" />

Output

<img width="753" height="44" alt="image" src="https://github.com/user-attachments/assets/88b795ee-4a9d-4819-8f11-52e8f5a25974" />

Step 2 — Create Backend and Database Directories

<img width="933" height="82" alt="image" src="https://github.com/user-attachments/assets/88adc9fc-ec90-48d7-9780-fb1c45d8349f" />

Output

<img width="956" height="55" alt="image" src="https://github.com/user-attachments/assets/3af03bf4-d528-44e3-8f38-dd9e339e8c50" />

Step 3 — Backend Files

Backend directory contains:

<img width="950" height="124" alt="image" src="https://github.com/user-attachments/assets/991c08ba-c073-483e-819e-b68e4aefe50b" />

Output

<img width="761" height="97" alt="image" src="https://github.com/user-attachments/assets/f108ee11-e164-4bf0-9f8b-578414a9c051" />

Step 4 — Database Files

Database directory contains:

<img width="958" height="103" alt="image" src="https://github.com/user-attachments/assets/9fdeccdf-4262-4ee9-b4d7-5cbca0e51257" />

Output

<img width="769" height="76" alt="image" src="https://github.com/user-attachments/assets/765bd5c5-971c-4297-93ec-783abddd7f65" />

Step 5 — Create IPvlan Network


Output

<img width="980" height="52" alt="image" src="https://github.com/user-attachments/assets/5859a806-b4ac-4300-9a80-3c66fade7b91" />

Step 6 — Verify Docker Networks

<img width="971" height="52" alt="image" src="https://github.com/user-attachments/assets/ba362135-5c82-44e7-978c-304299af9114" />

Output

<img width="975" height="125" alt="image" src="https://github.com/user-attachments/assets/398c89ba-b7e9-4a50-9889-4791d79de967" />

Step 7 — Inspect Network

<img width="972" height="51" alt="image" src="https://github.com/user-attachments/assets/d007e296-f90e-4b0b-933c-9cbd5799063d" />

Output

<img width="967" height="297" alt="image" src="https://github.com/user-attachments/assets/8d1af72f-1c00-4152-bbbc-451db858c531" />

Step 8 — Build and Start Containers

<img width="977" height="51" alt="image" src="https://github.com/user-attachments/assets/1255b8ab-1804-46ce-a29e-19b25bb4d518" />

Output

<img width="965" height="181" alt="image" src="https://github.com/user-attachments/assets/0c83cf0d-af45-412d-8a1e-e62d6781bddf" />

Step 9 — Verify Running Containers

<img width="967" height="49" alt="image" src="https://github.com/user-attachments/assets/5fba992e-1e8a-4a7e-a8da-b8ca490aa92f" />

Output

<img width="972" height="87" alt="image" src="https://github.com/user-attachments/assets/530e2f51-a4da-42f4-9f05-2006a3e568c5" />

Step 10 — Verify Container IP Addresses

<img width="965" height="62" alt="image" src="https://github.com/user-attachments/assets/f962fba7-4925-4715-9676-29c08acbc6a8" />

Output

<img width="970" height="81" alt="image" src="https://github.com/user-attachments/assets/9d0d7f7f-06f8-4b4d-8505-3f1c5b84fa00" />

Step 11 — Test API: Health Endpoint

Request

<img width="963" height="52" alt="image" src="https://github.com/user-attachments/assets/718f4785-8189-44af-81ee-78a0cd88eede" />

Response


Step 12 — Insert Record

Request

<img width="968" height="51" alt="image" src="https://github.com/user-attachments/assets/efeafe06-8801-4c48-8fc7-cda537540315" />

Response

<img width="954" height="107" alt="image" src="https://github.com/user-attachments/assets/35ac3e25-f792-4e38-82bb-dffa6c4b4717" />

Step 13 — Fetch Records

Request

<img width="958" height="51" alt="image" src="https://github.com/user-attachments/assets/4eddd857-03a3-494a-aa5b-807968ef5711" />

Response

<img width="954" height="145" alt="image" src="https://github.com/user-attachments/assets/7c66b444-582d-4a7a-be34-9525367fb994" />

Step 14 — Volume Persistence Test

Insert record first.

<img width="972" height="53" alt="image" src="https://github.com/user-attachments/assets/390228ed-a6c6-4ff4-babc-2a3830fbe8a0" />

Stop containers:

<img width="972" height="54" alt="image" src="https://github.com/user-attachments/assets/31a23ff7-3d66-456a-a175-e662c542e52f" />

Restart containers:

<img width="968" height="50" alt="image" src="https://github.com/user-attachments/assets/c1e4a7b2-9417-483f-b7de-75af860b246b" />

Fetch records again:

<img width="958" height="57" alt="image" src="https://github.com/user-attachments/assets/973bf04a-88be-4529-80fd-935c6e718f7d" />

Output

<img width="938" height="143" alt="image" src="https://github.com/user-attachments/assets/d17512a8-5624-4696-966b-6fab21842abf" />

Data persists even after container restart.

Step 15 — Docker Volume Verification

<img width="960" height="53" alt="image" src="https://github.com/user-attachments/assets/f3f861dc-b05a-4082-83bf-c2bc634cee07" />

Output

<img width="972" height="74" alt="image" src="https://github.com/user-attachments/assets/49b17977-71bf-4023-b6ce-349957c14137" />

Build Optimization Explanation

Several optimizations were implemented while building Docker images.

• Multi-stage builds reduce final image size.
• Slim base images reduce unnecessary dependencies.
• .dockerignore prevents unnecessary files from being copied into the container.
• Non-root user execution improves container security.
• Docker volumes ensure persistent database storage.

These optimizations improve performance, portability, and security of the containerized application.

Image Size Comparison

Image	Approx Size
python:3.11	~1GB
python:3.11-slim	~150MB
Using slim images significantly reduces image size and improves container startup time.

Macvlan vs IPvlan Comparison

Feature	Macvlan	IPvlan
MAC Address	Each container gets unique MAC	Containers share host MAC
Network Load	Higher load on switches	Lower load
Scalability	Limited	Highly scalable
Use Case	Small LAN environments	Cloud / virtual environments
Conclusion

This project successfully demonstrates containerized application deployment using Docker.

Key components implemented include:

• FastAPI backend container
• PostgreSQL database container
• Docker Compose orchestration
• IPvlan networking with static IP assignment
• Persistent storage using Docker volumes
• Optimized Docker image builds

The system ensures scalability, portability, and reliability in a containerized environment.
