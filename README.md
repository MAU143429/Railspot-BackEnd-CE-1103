# 🚂 Railspot — Backend API CE-1103

## 📘 Overview

This repository contains the backend system for **Railspot**, an online platform for purchasing train tickets between cities in Costa Rica. The system is responsible for handling all logic related to user authentication, ticket transactions, route management, and discount calculations.

Railspot simulates a map of train routes using graph structures and allows both users and administrators to interact with the system through a RESTful API.

---

## 🔁 Features

- 🔐 Secure login & ticket ownership per user ID
- 🎟️ Ticket purchase, tied to user accounts
- 📉 Dynamic discount system (2% off each new ticket up to 90%)
- 📊 Graph-based route simulation with shortest path recommendation
- 🛠️ Admin operations:
  - Create, edit, and delete train routes
  - Modify prices or weights of connections
  - View historical ticket purchases by station

---

## 🛠️ Technologies Used

- **Language**: Java
- **Framework**: Spring Boot / REST
- **Data structures**: Graphs (custom algorithms for pathfinding)
- **Database**: H2 / PostgreSQL (configurable)
- **Security**: Basic authentication

