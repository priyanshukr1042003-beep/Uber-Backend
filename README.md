🚖 Ride Booking Backend (Uber Clone)

A scalable backend system for a ride-booking platform inspired by Uber. This project demonstrates real-world backend architecture using asynchronous job processing, caching, and modular design.

✨ Features
🚀 RESTful APIs for rider & ride management
⚡ Asynchronous job processing using BullMQ
🧠 Redis-based caching & queue system
🗄️ MongoDB integration with Mongoose ODM
✅ Request validation using Zod
🛡️ Centralized error handling
📜 Request logging with Morgan
🧩 Modular architecture (controllers, services, workers, queues)
🛠️ Tech Stack
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Cache & Queue: Redis, BullMQ
Validation: Zod
Logging: Morgan
Environment: dotenv
🧠 Architecture Overview

This project follows a modular and scalable backend design:

Controllers → Handle incoming requests
Services → Business logic layer
Queues → Manage background jobs
Workers → Process async tasks
Database → Persistent storage (MongoDB)
Cache Layer → Redis for fast access & job queues
