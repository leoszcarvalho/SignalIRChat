# SignalR Real-Time Chat Playground

This project is a **simple real-time chat application** built with **ASP.NET Core** and **SignalR**, created to explore and test real-time communication concepts.

It demonstrates how to establish live message updates between users using SignalR, simulating conversations and online users in a controlled, in-memory environment.

---

## 🧠 Project Overview

The application allows authenticated users to:
- See a list of online users
- Start a conversation with another user
- Exchange messages in real time
- Receive instant updates without page refreshes

Conversations and users are simulated and stored **in memory**, making the project lightweight and focused on learning rather than persistence.

---

## ⚡ Real-Time Communication with SignalR

SignalR is used to:
- Push messages instantly to connected clients
- Keep chat conversations synchronized
- Enable real-time updates using WebSockets (when available)

This project serves as a hands-on introduction to real-time web applications using SignalR.

---

## 🧩 Application Structure

- **ASP.NET Core MVC**
  - Controllers and Views
- **SignalR**
  - Real-time message delivery
- **Authentication**
  - Endpoints protected with `[Authorize]`
- **In-memory data**
  - Simulated conversations and online users

---

## 🛠 Tech Stack

- C#
- ASP.NET Core
- SignalR
- MVC Pattern
- Real-Time WebSockets Communication

---

## 🚀 Key Features

- Real-time chat updates using SignalR
- Authenticated user access
- Simulated online users
- In-memory conversation management
- Simple and easy-to-understand architecture

---

## ▶️ Running the Application

```bash
dotnet restore
dotnet run
