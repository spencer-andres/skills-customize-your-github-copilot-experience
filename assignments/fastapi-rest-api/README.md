# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Students will create a small REST API using FastAPI that implements authentication, file uploads, initiation of long-running processes, and long-running process updates via datastreaming.

## 📝 Tasks

### 🛠️ Implement REST API with FastAPI

#### Description
Build a REST API using FastAPI that includes authentication, data management, long-running processes, and file uploads.

#### Requirements
Completed program should:

- REST endpoints for at least three data objects including a user for authentication
- Server data stored in JSON that initializes to the same value every time the server starts and gets updated by the REST endpoints
- Authentication for the User object with access guarding on endpoints for data creation, update, or delete
- Long-running data operations that are initiated by calls to the REST API
- Updates on long-running processes via datastreaming and websockets
- File uploads by an authenticated user