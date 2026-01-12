# DeNote

DeNote is a full-stack web application for securely uploading, discovering, and accessing academic notes using decentralized storage (IPFS).

**Live Demo:** [https://denote-nu.vercel.app](https://denote-nu.vercel.app)

**Backend API:** [https://denote-igao.onrender.com](https://denote-igao.onrender.com)

---

## Overview

- Designed and built a **scalable full-stack application** with secure authentication and decentralized file storage.
- Enables users to upload notes, rate content, and discover high-quality academic material.
- Deployed with a **production-ready architecture**, separating frontend and backend services.

---

## Key Features

- JWT-based user authentication
- Decentralized file storage using IPFS (Pinata)
- MongoDB-backed metadata and user management
- Rating and discovery system for quality content
- PDF preview via IPFS gateway links
- Secure environment-based configuration

---

## Tech Stack

- **Frontend:** React 18, Vite
- **Backend:** Node.js, Express
- **Database:** MongoDB Atlas
- **Storage:** IPFS (Pinata)
- **Authentication:** JSON Web Tokens (JWT)
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## Architecture Highlights

- RESTful API design
- Stateless authentication with JWT
- Decentralized storage for data durability
- Scalable deployment with separate services

---

## Security & Best Practices

- Secrets managed via environment variables
- Sensitive files excluded using `.gitignore`
- Controlled access using CORS configuration
- MongoDB Atlas network access controls

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
