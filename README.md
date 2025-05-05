# 🔗 ForgeLink Frontend

[![Netlify Status](https://api.netlify.com/api/v1/badges/0d7204d7-ecd0-4869-80a8-3f5706736d10/deploy-status)](https://app.netlify.com/sites/forgelink/deploys)

> 🚫 **Proprietary License** – Not open source.  
> You may **not** clone, copy, mirror, modify, distribute, or otherwise use this code except for review in a hiring context.  
> See [LICENSE](./LICENSE) for full terms.

---

## 📖 Project Overview

**ForgeLink Frontend** is a lightweight, static user interface for the ForgeLink backend system—a cloud-ready, DDoS-protected URL shortener.  
It provides users a simple landing page to interact with backend services.

- Built using plain HTML, CSS, and minimal JavaScript for fast loading
- Deployed on **Netlify** for global availability and SSL support
- Linked directly to backend APIs secured via DuckDNS + NGINX reverse proxy

---

## 🌐 Live Deployment

- **Frontend URL**: [https://forgelink.netlify.app/](https://forgelink.netlify.app/)

---

## 🏗️ Architecture

- Static frontend served via Netlify CDN
- Backend APIs handled securely over HTTPS
- Designed for easy integration with FastAPI backend and Dockerized microservices

---

## 🧪 Local Setup Instructions

> _Note: You only need a browser to test locally._

1. Clone this repository:
   ```bash
   git clone https://github.com/SwayamY/ForgeLink-frontend.git
   cd ForgeLink-frontend
   ```
2. Open index.html directly in your browser or serve it using any local server (optional for testing CORS/API calls).

---

📌 Conclusion
This frontend is intentionally lightweight to focus on backend and DevOps showcase.
It demonstrates a clean separation of concerns: static delivery (frontend) and dynamic API-driven operations (backend).

For recruiters or reviewers:
Please review this project in conjunction with ForgeLink Backend to see the complete cloud + DevOps workflow.

🔗 For further inquiries, collaboration opportunities, or DevOps/backend roles, feel free to connect with me on 
[LinkedIn](https://www.linkedin.com/in/swayam-yadav-50b741283/) or reach out via email at swayam.science777@gmail.com.
