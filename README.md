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
<h3>🛠️ Technologies Used</h3>
<ul>
  <li><strong>Go (Golang)</strong> – Primary language for the authentication microservice; chosen for its high concurrency via goroutines and low memory overhead.</li>
  <li><strong>Python</strong> – Powers core microservices such as the order engine, matching logic, and backend utilities.</li>
  <li><strong>Flask</strong> – Lightweight framework used for backend APIs and newer microservices.</li>
  <li><strong>Django</strong> – Initially used for API development and dynamic web rendering; now partially replaced by Flask and Go services.</li>
  <li><strong>Vue.js</strong> – Modern JavaScript framework used to build the frontend UI, enabling reactive components and real-time updates.</li>
  <li><strong>HTML & CSS</strong> – Core frontend technologies for layout and styling.</li>
  <li><strong>SQL</strong> – PostgreSQL used for structured, transactional data storage.</li>
  <li><strong>NoSQL</strong>
    <ul>
      <li><strong>MongoDB</strong>: Stores stock transactions and user portfolios.</li>
      <li><strong>Redis</strong>: Used for fast-access caching and storing wallet balances in real-time trading.</li>
    </ul>
  </li>
</ul>

<hr>

<h3>🔧 Supporting Technologies</h3>
<ul>
  <li><strong>Docker</strong> – Containerizes each microservice for isolated, reproducible deployments.</li>
  <li><strong>Nginx</strong> – Acts as a reverse proxy and load balancer for routing API traffic efficiently.</li>
  <li><strong>JWT (JSON Web Token)</strong> – Provides stateless, secure authentication across services.</li>
  <li><strong>JSON</strong> – Standard format for inter-service API communication.</li>
  <li><strong>RESTful API Endpoints</strong> – Define clear boundaries between services and clients.</li>
  <li><strong>Postman</strong> – Used for API validation and testing across endpoints.</li>
  <li><strong>JMeter</strong> – Load testing tool used to validate performance under high concurrency.</li>
  <li><strong>Flask-CORS</strong> – Manages secure cross-origin requests between frontend and backend.</li>
  <li><strong>Dotenv</strong> – Manages environment variables for secure and flexible configurations.</li>
</ul>

<hr>

<h3>🚀 Architecture & Scalability Features</h3>
<ul>
  <li><strong>Microservices Architecture</strong> – Fully modular system enabling independent deployment and scaling of services.</li>
  <li><strong>Real-time Trading APIs</strong> – Implemented using REST and optimized for low-latency order execution.</li>
  <li><strong>Performance Optimizations:</strong>
    <ul>
      <li>Caching with Redis for rapid wallet access.</li>
      <li>Load Balancing with Nginx to distribute traffic across service instances.</li>
    </ul>
  </li>
  <li><strong>Concurrency Support</strong> – System is tested and proven to handle 15,000+ concurrent users under real-world conditions.</li>
</ul>
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

