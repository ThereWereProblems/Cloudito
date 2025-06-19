# Cloudito ☁️

**Cloudito** is a lightweight, self-hosted cloud file storage solution inspired by platforms like OneDrive and Google Drive. Cloudito was created as both a personal utility.

This project is ideal for personal use, local NAS setups, or as a technical showcase of clean architecture, CQRS, file streaming, and secure authentication using JWT.

## 🔧 Features

- 🔐 User registration & authentication (JWT + refresh tokens)
- 📤 File upload with metadata
- 🔗 Shareable download links with expiration
- 🧱 Clean Architecture with CQRS
- 🐘 PostgreSQL for metadata & access control
- 📦 Local storage via Docker volume (bind-mounted)
- 🐳 Dockerized deployment

## 🛠️ Tech Stack

- **Frontend:** Angular 19
- **Backend:** .NET 10
- **Database:** PostgreSQL
- **Storage:** Local file system (Docker volume)
- **Auth:** Custom auth system using JWT + refresh tokens