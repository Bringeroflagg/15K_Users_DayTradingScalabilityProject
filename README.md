<p align="center">
  Author: Ayush Mattoo
  <hr>
</p>
Steps to run project:

Step 1: docker-compose down -v

Step 2: docker-compose up --build
<hr>
15,000 Users MicroServices Architecture:
![image](https://github.com/user-attachments/assets/b4dece2b-85a0-49dc-8364-5129ff8c7532)
<hr>
Technologies Used:
🛠️ Technologies Used
Go (Golang) – Primary language for the authentication microservice; chosen for its high concurrency via goroutines and low memory overhead.

Python – Powers core microservices such as the order engine, matching logic, and backend utilities.

Flask – Lightweight framework used for backend APIs and newer microservices.

Django – Initially used for API development and dynamic web rendering; now partially replaced by Flask and Go services.

Vue.js – Modern JavaScript framework used to build the frontend UI, enabling reactive components and real-time updates.

HTML & CSS – Core frontend technologies for layout and styling.

SQL – PostgreSQL used for structured, transactional data storage.

NoSQL –

MongoDB: Stores stock transactions and user portfolios.

Redis: Used for fast-access caching and storing wallet balances in real-time trading.
<hr>
🔧 Supporting Technologies
Docker – Containerizes each microservice for isolated, reproducible deployments.

Nginx – Acts as a reverse proxy and load balancer for routing API traffic efficiently.

JWT (JSON Web Token) – Provides stateless, secure authentication across services.

JSON – Standard format for inter-service API communication.

RESTful API Endpoints – Define clear boundaries between services and clients.

Postman – Used for API validation and testing across endpoints.

JMeter – Load testing tool used to validate performance under high concurrency.

Flask-CORS – Manages secure cross-origin requests between frontend and backend.

Dotenv – Manages environment variables for secure and flexible configurations.
<hr>
🚀 Architecture & Scalability Features
Microservices Architecture – Fully modular system enabling independent deployment and scaling of services.

Real-time Trading APIs – Implemented using REST and optimized for low-latency order execution.

Performance Optimizations:

Caching with Redis for rapid wallet access.

Database Sharding & Replication in MongoDB for horizontal scaling and redundancy.

Load Balancing with Nginx to distribute traffic across service instances.

Concurrency Support – System is tested and proven to handle 15,000+ concurrent users under real-world conditions.
<hr>
10,000 Users MicroServices Architecture:
![image](https://github.com/user-attachments/assets/189847b2-d76d-4f1d-8f15-26cebe53fbe9)

1 User MicroServices Architecture:
![image](https://github.com/user-attachments/assets/fafca5f1-27e8-460e-81c4-3a749c16d90b)


**Jmeter Functionality Tests Screenshot:**
![image](https://github.com/user-attachments/assets/c91e23f2-0b7d-4c42-93c5-c54c5bf3da11)


**Running Docker Containers:**
<img width="1512" alt="image" src="https://github.com/user-attachments/assets/b7982143-e7de-42b8-99a9-b535a6d2878a" />

--- Database Schema ---

**MongoDB and Redis:**
![image](https://github.com/user-attachments/assets/d69b42e5-83c9-4508-aef1-11a1018c5ddc)

![image](https://github.com/user-attachments/assets/b984d8cb-a464-4648-af5b-d1229a590e3a)

Front-End:
![image](https://github.com/user-attachments/assets/667b6d8e-4b87-4920-877f-a464cdb37310)
![image](https://github.com/user-attachments/assets/665f7cbf-6a94-4ccb-9996-19aa979b27ee)

