# Harbor-Management-System-HMS-
## Project Overview:
### The Harbor Management System (HMS) is an integrated logistics platform designed to optimize port operations. It focuses on the efficient handling of container arrivals, real-time vessel scheduling, and seamless coordination between terminal cranes and transport trucks to eliminate bottlenecks.
## Problems:
### - Vessel Congestion: Large volumes of containers arrive simultaneously when ships dock, leading to chaos without a structured unloading plan.
### - Operational Bottlenecks: Lack of synchronization between container discharge and truck arrival leads to long queues at the gate, wasting time and increasing costs.
### - Yard Inefficiency: Poor organization of container stacks (Yard) makes it difficult to retrieve specific containers, causing "double handling" delays.
### - Lack of Real-time Visibility: Manual tracking prevents stakeholders from responding quickly to delays or equipment failures.
## Solution:
### An automated, real-time management system that synchronizes the movement of vessels, containers, and trucks. The system utilizes an Intelligent Scheduling Algorithm to predict optimal container placement and provide real-time alerts for operational delays.
## Technology
### Documentation&Design: Draw.io (ERD, Use Case), Figma (UI/UX), Swagger (API Doc).
### Frontend(FE): ReactJS, Tailwind CSS, Axios, React Query.
### Backend(BE): Java 17+, Spring Boot 3, Spring Security (JWT).
### Real-time Communication: WebSockets (STOMP/SockJS).
### Database: MySQL (Primary), Redis (Caching/Session).
### DevOps & Deploy: GitHub, Docker, Railway (BE), Vercel (FE).
## Module&Feature:
### A. Vessel & Berthing Management
#### - Schedule Tracking: Manage Estimated Time of Arrival (ETA) and docking status.
#### - Manifest Management: Digitally record the list of containers on each vessel.
### B. Smart Yard Management (The "AI" Logic)
#### - Inventory Tracking: Real-time mapping of container locations in the yard (Row/Tier/Slot).
#### - Stacking Optimization: Heuristic-based suggestions for container placement to minimize retrieval time.
#### - Alert System: Automated notifications for hazardous materials or overdue containers.
### C. Gate & Truck Coordination
#### - Appointment System: Trucks register arrival times to prevent gate congestion.
#### - Real-time Dispatching: Notify truck drivers via the system when their container is ready for pickup.
