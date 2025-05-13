# SIT737-Cloud Native Application Development
## Adding a database to your application


This is a full-stack web application that uses:

- **Frontend**: HTML/CSS/JavaScript (or React)
- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Backup**: MongoDB backup using Kubernetes CronJob

---
## 📹 Demo

Check out the demo video showing all CRUD operations:
[📽️ crud-demo.mp4](./crud-demo.mkv)

---

## 🔒 Security

MongoDB root credentials are stored securely using Kubernetes Secrets:
```yaml
apiVersion: v1
kind: Secret
metadata:
  name: mongo-secret
type: Opaque
```

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Docker
- Kubernetes
- HTML/CSS/JS or React
- GitHub

---
